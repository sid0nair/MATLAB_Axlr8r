# MATLAB Simulations for Formula Student Vehicle Dynamics

This repository contains MATLAB codes designed for simulating various forces and conditions experienced by a Formula Student (FS) vehicle. The simulations focus on the forces acting on the A-arms, bolt safety factors, and event-specific car conditions such as acceleration, skidpad, and endurance.

## Overview
The codes in this repository help to simulate the real-world dynamics and stresses experienced by a Formula Student vehicle. It allows for:
- Calculating the forces on the suspension A-arms.
- Analyzing the safety factors of bolts used in different vehicle components.
- Simulating car conditions for various FS events, including acceleration, skidpad, and endurance.

## Getting Started
1. Clone the repository:
    ```bash
    
    ```
2. Open MATLAB and navigate to the cloned directory.

## Simulation Descriptions

### 1. A-Arm Force Simulation
This script calculates the forces acting on the A-arms during various dynamic conditions such as cornering, braking, and accelerating. The simulation considers parameters like suspension geometry, load transfer, and tire forces.

- **Script**: `acceleration_model.mlx`
- **Usage**: This code can be used to determine the optimal design and material choice for the A-arms to ensure safety and performance.

### 2. Bolt Safety Factor Analysis
This script analyzes the safety factors of bolts used in critical areas like suspension, steering, and drivetrain components. It considers the forces acting on the bolts during different dynamic conditions and calculates the safety factors based on material properties and loading conditions.

- **Script**: `BoltSafetyFactor.m`
- **Usage**: Useful for selecting appropriate bolt grades and ensuring reliability in high-stress situations.

### 3. FS Event Simulations
These scripts simulate the car's behavior in different FS events to predict performance and identify potential weaknesses.

#### a. Acceleration Event
Simulates the car's performance in a straight-line acceleration run, focusing on aspects like power delivery, traction, and weight distribution.

- **Script**: `AccelerationEvent.m`
- **Usage**: Can be used to optimize gear ratios, tire selection, and launch control strategies.

#### b. Skidpad Event
Simulates the lateral dynamics of the car during a skidpad event to analyze handling, tire behavior, and weight transfer.

- **Script**: `SkidpadEvent.m`
- **Usage**: Helps in tuning suspension settings to maximize cornering speed and stability.

#### c. Endurance Event
Models the car's endurance performance, including factors such as fuel/energy consumption, tire wear, and thermal management over an extended period.

- **Script**: `EnduranceEvent.m`
- **Usage**: Useful for strategy planning, ensuring component durability, and optimizing vehicle performance for long-duration events.

## Dependencies
- MATLAB R2020b or later
- Optimization Toolbox (for bolt safety factor analysis)
- Vehicle Dynamics Toolbox (for event simulations)

## Usage
1. Open the respective MATLAB script (e.g., `AArmForceSim.m`).
2. Modify the input parameters (e.g., vehicle geometry, material properties) as needed.
3. Run the script to view results and visualizations.
4. Output results can be saved for further analysis or documentation.

## Contributing
Contributions are welcome! If you have suggestions for improvements or additional simulations, please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
