# DC-Motor-Control-Design-Simulink
Speed control of DC Motor using Lag and Lead Compensators in MATLAB/Simulink and performance analysis
# Project Description
This project models a physics-based DC Motor and implements two classical control strategies to regulate its speed. The core objective is to analyze the trade-off between speed recovery (transient response) and the actual voltage demanded from the actuator (control effort).
(Lead Compensator):Extremely fast response but demands an unrealistic initial impulse of ~160,000 Volts. This would cause actuator saturation or permanent hardware damage in real life.
(Lag Compensator):Slower response but operates within safe, practical voltage limits, making it the viable choice for physical implementation.
# Real-World Applications- The control logic designed in this simulation is heavily used in:
Electric Vehicle (EV) Powertrains:- Managing smooth torque and speed transitions without damaging the battery management system (BMS).
Robotic Actuators :-Ensuring precise speed and position control in robotic arms under varying load conditions.
Industrial Conveyor Systems:-Maintaining constant speed in assembly lines when heavy loads are added or removed.
# Methodology & Architecture
Plant:DC Motor Transfer Function
Software Used: MATLAB R2026a & Simulink
# Results
Control Effort Comparison
