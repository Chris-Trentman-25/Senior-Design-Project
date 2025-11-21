| Requirement Description |	Category |	Metric / Acceptance Criteria |
| ----------------------- | -------- | ----------------------------- |
| The system shall store energy by lifting a mass to a specified height. | Energy Storage | Achieve m·g·h ≥ required energy target. |
|	The system shall release energy by lowering the mass in a controlled manner. |	Energy Storage |	Descent speed controlled within ±5%. |
|	The system shall deliver enough power to support a 10 W load for 10 s. |	Electrical Output |	Minimum 0.028 Wh output (10 W × 10 s). |
|	The system shall achieve a minimum round-trip efficiency of 80% . |	Performance |	Efficiency measured as (E_out / E_in) × 100%. |
|	The lifting subsystem shall support a payload mass of 10 kg. |	Mechanical 	| Verified through static load test with safety factor 2.0. |
|	The tower shall withstand static and dynamic loads without structural failure. |	Structural |	Stress ≤ allowable stress; safety factor ≥ 2.0. |
|	The system shall lift the mass to full height within T_lift seconds. |	Mechanical |	Full lift achieved under T_lift (team-selected). |
| The braking system shall stop the mass safely during descent. |	Safety / Mechanical |	Emergency stop distance ≤ X cm. |
|	The motor-generator shall operate as a motor during charging. |	Electromechanical |	Lifts mass at required torque. |
|	The motor-generator shall operate as a generator during discharge. |	Electromechanical |	Generates stable output voltage within ±10%. |
|	The electrical subsystem shall regulate voltage to load requirements. |	Electrical |	Output voltage within ±10% of nominal. |
|	The system shall include appropriate power conditioning (rectifier/regulator). |	Electrical |	Meets load requirements per specification. |
|	The system shall measure mass position. |	Controls / Sensors |	Position accuracy ±1 cm or better. |
|	The system shall measure generator speed or RPM. |	Controls / Sensors |	RPM accuracy ±5%. |
|	The system shall detect faults such as overspeed or overcurrent. |	Controls / Safety |	System enters shutdown within <100 ms after detection. |
|	The system shall automatically manage lift/lower operations. |	Controls |	Embedded controller executes operation cycle. |
| Users shall have manual control (start, stop, lift, lower). |	User Interface |	Interface implemented and functional. |
|	The system shall have a physical emergency stop button. |	Safety |	E-stop cuts power and brakes system. |
|	The design shall prevent user contact with moving or high-voltage parts. |	Safety |	Enclosure and interlocks verified. |
|	Subsystems shall interface mechanically and electrically without interference. |	Integration |	Verified through integration testing. |
| The system shall allow easy access to components for maintenance. |	Integration |	Access panels or open architecture included. |
|	The system shall be testable with accessible points for electrical and mechanical measurements. |	Testing |	Measurement ports included. |
|	The system shall operate for 10 cycles without significant degradation. |	Reliability |	Passes repeatability cycle testing. |
| The system shall operate safely within indoor lab conditions. |	Environment |	Verified in lab temperature/humidity ranges. |
