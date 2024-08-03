
### Project Summary: Satellite Orbit and Attitude Control Simulation
#### Main Objective:
Develop a software simulation to model the orbits and attitudes of satellites, including perturbations, orbital maneuvers, and attitude control.

#### Sub-Objectives:
1. Implement guidance algorithms for orbital transfers and station-keeping.
2. Simulate navigation using sensor data.
3. Develop control systems for attitude stabilization and orientation.
4. Integrate AOCS algorithms to ensure precise attitude control and minor orbit adjustments.
    

### Project Components and Their Focus Areas:
#### 1. Orbital Dynamics and Perturbations (GNC)
- Orbital Dynamics Model: Implement numerical integrators for satellite motion.
- Perturbations: Include effects like J2 perturbation, atmospheric drag, and solar radiation pressure.

#### 2. Guidance System (GNC)
- Hohmann Transfer Algorithm: For simple orbital changes.
- Continuous Low-Thrust Trajectory Optimization: For more complex maneuvers.
- Station-Keeping Algorithms: To maintain satellite position.

#### 3. Navigation System (GNC)
- Sensor Data Simulation: Generate synthetic data for GPS, IMU, and star trackers.
- State Estimation: Implement Kalman filters for sensor fusion.

#### 4. Control System (GNC and AOCS)
- Attitude Dynamics Model: Develop equations for rotational dynamics (AOCS).
- Attitude Control Algorithms: Design PID controllers for reaction wheels and thrusters (AOCS).
- Orbital Control: Implement control systems for orbital maneuvers (GNC).

#### 5. AOCS-Specific Components (AOCS)
- Attitude Determination: Use algorithms for precise attitude determination using star trackers, sun sensors, and gyroscopes.
- Attitude Control: Develop control algorithms to maintain or change orientation.
- Orbit Control: Integrate minor orbit correction algorithms for trajectory adjustments due to perturbations.

#### 6. Testing and Validation (GNC and AOCS)
- Unit Testing: Test individual components.
- Integration Testing: Ensure components work together.
- Validation: Compare simulation results with real-world data or validated models.
    
#### 7. Iteration and Improvement (GNC and AOCS)
- Refine algorithms and models based on testing.
- Add advanced features such as detailed atmospheric models and enhanced sensor models.

### GNC vs. AOCS Highlights:
#### GNC (Guidance, Navigation, and Control):
- Guidance: Path planning, orbital transfers, station-keeping.
- Navigation: Sensor simulation, state estimation using Kalman filters.
- Control: Control systems for orbital maneuvers.
    
#### AOCS (Attitude and Orbit Control Systems):
- Attitude Determination: Algorithms for precise orientation using sensors.
- Attitude Control: PID controllers for reaction wheels, thrusters for orientation changes.
- Orbit Control: Minor corrections to maintain and adjust orbit due to perturbations.
    