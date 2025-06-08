# Pseudocode – Ball and Beam Controller

## Goal
Use a feedback control loop to keep a steel ball balanced at the center of a beam.

## Flow
- [ ] Measure ball position using IR/ultrasonic sensors
- [ ] Compare with desired setpoint (e.g., center = 0)
- [ ] Apply PID control:
  - Output = motor PWM to tilt beam
- [ ] Update control every 50 ms
- [ ] Log position and error over time
