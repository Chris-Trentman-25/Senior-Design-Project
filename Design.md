# Design Goal
## Mission Statement
Design and build a lab-scale tower gravity energy storage system capable of storing and releasing mechanical potential energy under automated control while measuring efficiency and ensuring safe operation.
## Non-goals
* not grid-scale
* not optimized for cost
# Engineering Requirements
## Implied Requirements
| Phrase                | Implies                      |
|-----------------------|------------------------------|
| lab-scale             | Size, mass, and power limits |
| tower gravity         | vertical lift, guided mass   |
| energy storage        | measurable stored energy     |
| storing and releasing | bidirectional operation      |
| automated control     | controller and sensors       |
| measuring efficiency  | power and energy measurement |
| safe operation        | redundant safety features    |
## Quantitative System Requirements
| ID  | Requirement            | Target / Constraint    |
|-----|------------------------|------------------------|
| R1  | stored energy capacity | >= 2 Wh                |
| R2  | tower height           | <= 4 m                 |
| R3  | lifted mass            | <= 250 kg              |
| R4  | max discharge power    | 100 - 300 W            |
| R5  | charge time            | <= 2 minutes           |
| R6  | control mode           | fully automated        |
| R7  | measurement            | energy in/out logged   |
| R8  | efficiency calculation | round-trip efficiency  |
| R9  | safety                 | e-stop and hard limits |
| R10 | environment            | indoor lab operation   |
| R11 | budget                 | <= project budget      |
| R12 | reset capability       | repeatable cycles      |
## Acceptance Criteria
| Requirement | Acceptance Test                                         |
|-------------|---------------------------------------------------------|
| R1          | lift mass stores >= 2 Wh                                |
| R4          | system delivers >= 100 W to load                        |
| R6          | system completes lift/lower without manual intervention |
| R7          | voltage & current logged at >= 10 Hz                    |
| R8          | efficiency computed from logged data                    |
| R9          | e-stop halts motion within safe distance                |


