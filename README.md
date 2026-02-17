# FEA-simulations-for-inserts
<img width="1417" height="433" alt="Screenshot 2025-12-20 152119" src="https://github.com/user-attachments/assets/2641988b-62c6-48f9-bb41-6d9c46c350c4" />
<img width="1474" height="741" alt="Screenshot 2025-12-20 152944" src="https://github.com/user-attachments/assets/7881ae50-d637-4355-b23d-9dc89667cf69" />
<img width="1223" height="341" alt="Screenshot 2025-12-20 153511" src="https://github.com/user-attachments/assets/23ff1074-0649-44dd-9456-a0aab1ed30de" />
# FEA Simulations for Composite Inserts – Structural Integrity Study

## Project Overview

This project investigates the structural behavior of composite insert regions within a CFRP structure subjected to mechanical loading.

The objective was to evaluate:

- Stress concentration mechanisms around metallic inserts
- Composite failure index distribution
- Load transfer efficiency between insert and laminate
- Structural integrity under representative load cases

---

## Engineering Context

In composite structures, metallic inserts introduce stiffness mismatch and stress concentration zones.

Improper geometric transition or laminate design can lead to:

- Local delamination
- Matrix cracking
- Fiber failure
- Premature structural degradation

This study evaluates the structural reliability of insert integration using FEA.

---

## Numerical Setup

Solver: OptiStruct (Linear Static)

Elements:
- Composite laminates → 2D shell elements
- Insert region → Solid elements

Failure Criterion:
- Composite Failure Index (CFAILURE)

Boundary Conditions:
- Fixed constraints at structural support interface
- External mechanical load applied to simulate service condition

---

## Stress Distribution (Von Mises – Insert Region)

The von Mises contour reveals:

- Localized stress concentration at insert edges
- Load amplification at stiffness transition zone
- Peak stresses occurring near geometric curvature changes

Mechanics Interpretation:

The insert acts as a rigid inclusion within a compliant laminate matrix.

This stiffness mismatch generates stress gradients at the interface, particularly under bending-dominated loading.

---

## Composite Failure Index Analysis

The Composite Failure Index plot highlights:

- Elevated failure index at the lower laminate surface near the insert
- Progressive stress diffusion away from insert interface
- Critical zones aligned with bending tensile side

Engineering Insight:

Failure is not governed solely by peak stress magnitude but by the interaction between:

- Insert geometry
- Laminate stacking sequence
- Load direction

Proper geometric blending reduces stress amplification and delays failure initiation.

---

## Structural Design Implications

To improve insert reliability:

1. Increase transition radius around insert region
2. Modify laminate stacking sequence for better load redistribution
3. Introduce local reinforcement plies
4. Evaluate progressive failure behavior in nonlinear analysis

---

## Skills Demonstrated

- Composite FEA modeling
- Failure index interpretation (CFAILURE)
- Insert-laminate load transfer analysis
- Stress concentration assessment
- Structural integrity reasoning
