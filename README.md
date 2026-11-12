# FRC Swerve Drive Prototype

## About the Project

This repository contains an experimental FRC (FIRST Robotics Competition) robot prototype developed using Java and WPILib 2026. The main goal of this project is to explore and develop a Swerve Drive system, allowing the robot to move in multiple directions, rotate independently, and simulate the behavior of its four individual wheel modules.

The project is currently in an early development stage and should be considered a work in progress. Although some of its basic movement and simulation features have been implemented, the current version may contain bugs, inaccurate physics calculations, incomplete functionality, and unexpected behavior. Some features may not work exactly as intended, and the simulation does not yet represent a complete physical model of a real FRC robot.

I intend to continue improving this project over time, correcting existing problems, refining the movement calculations, improving the behavior of the four Swerve modules, and developing a more accurate and reliable simulation. Additional features and improvements will be introduced as development progresses.

## Requirements

To open and run this project, you will need WPILib 2026 installed on your computer, along with its recommended Visual Studio Code environment and Java development tools. An Xbox-compatible controller is also recommended if you want to interact with the robot during simulation.

The project was developed around the WPILib Java framework, so using the appropriate WPILib version is important to avoid compatibility issues with the libraries and build configuration.

## How to Run

First, download or clone this repository to your computer and open the project folder using the WPILib Visual Studio Code environment. Make sure you open the main project directory, where the `build.gradle` file is located, rather than opening individual Java files.

Once the project is open, allow Gradle to finish synchronizing its dependencies. You can then open the WPILib command menu in Visual Studio Code by pressing `Ctrl + Shift + P` and searching for `WPILib: Build Robot Code`. This will compile the project and check whether the source code and dependencies are configured correctly.

After a successful build, open the command menu again and select `WPILib: Simulate Robot Code`. Choose the appropriate simulation configuration and wait for the simulation environment to start. The robot simulation should then become available through the WPILib simulation tools.

## Controller Configuration

The current implementation is designed to use an Xbox controller connected to the computer through USB. The controller is configured on port `0`, so make sure it is recognized by your operating system before starting the simulation.

The left analog stick is used to control forward, backward, and sideways movement, while the right analog stick controls the robot's rotation. The robot must be enabled through the Driver Station simulation before the controller inputs will affect its movement.

## Current Development Status

The current version focuses primarily on the basic Swerve Drive movement calculations and the simulation of four independent wheel modules. It is not yet a complete representation of a competition-ready FRC robot, and its simulation should not be treated as an accurate substitute for real-world testing.

The 3D visualization also requires a compatible visualization environment and model configuration. The simulation code alone does not automatically provide a complete 3D robot model.

## Future Development

This project will continue to receive modifications and improvements as development progresses. The main objective is to gradually transform the current prototype into a more complete and reliable FRC Swerve Drive simulation, with improved movement accuracy, module behavior, physics calculations, visualization, and overall stability.

Contributions, suggestions, and feedback are welcome. Since this is an experimental project, any feedback that helps identify problems or improve the implementation is appreciated.

**This is only the beginning of the project. More improvements are planned for future versions.**
