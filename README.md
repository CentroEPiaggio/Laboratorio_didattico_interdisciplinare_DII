# DEMO - Robotica autonoma e resiliente

This repository collects the material needed for the challenge you have to complete.

## ROS 2

The installation guide is for Ubuntu.
On Windows, you can use WSL(2) to run Ubuntu and follow the same instructions. Since WSL is already based on Docker, no need to double containerize it.

Two options:
- **Dockerized Installation**: you can follow [Docker + ROS + NVIDIA](https://github.com/ddebenedittis/docker_ros_nvidia) for a minimal docker setup with GUIs and NVIDIA support. If you do not have an NVIDIA GPU, remove the `gpus=all` flag from the `docker/run.bash` command.
- **Classical Installation**: follow [this](https://docs.ros.org/en/humble/Installation/Ubuntu-Install-Debs.html).

It is recommended to follow the Dockerized Installation to not be constrained by the host OS and have a reproducible environment.

Note that each ROS distribution is targeted at a specific Ubuntu version.

### Tutorials

[Official ROS 2 tutorials](https://docs.ros.org/en/humble/Tutorials.html).

Fundamentals:
- From Concepts:
  - Basic Concepts
- From Tutorials:
  - Beginner: CLI tools
  - Beginner: Client libraries
  - From Intermediate:
    - Launch
    - tf2
    - Testing
    - URDF
    - RViz
  - From Advanced:
    - Simulators -> Gazebo
- From Concepts:
  - Intermediate Concepts

It is recommended to read and understand these tutorials without however fully memorizing the syntax. Just knowing what is possible within ROS 2 and where to find the information when needed is sufficient. \\
On the other hand, memorizing the CLI commands is useful as they are used often.

Know the difference between Gazebo Classic and Gazebo (ex. Ignition Gazebo).
- [Gazebo Classic](https://classic.gazebosim.org/) is the "old" Gazebo, now EOL.
- [Gazebo](https://gazebosim.org/home) is the new generation simulator. In CF, we use this one.

## Limo

- Read the local LIMO Pro manual: <https://github.com/agilexrobotics/limo_pro_doc/blob/master/Limo%20Pro%20Ros2%20Foxy%20user%20manual(EN).md>
- Use the course Docker setup: <https://github.com/CentroEPiaggio/docker_humble_limo>

The Limo repo contains:
- `Limo Pro Ros2 Foxy user manual(EN).md`: reference manual for LIMO Pro commands, modes, mapping, navigation, camera, and optional arm workflows.
- `DEMO.png`: demo image for the assignment/materials.

## Asking Questions

Use the repository's Issues section for questions about the assignment, setup problems, or unclear steps. Include the command you ran, the error output, and what environment you are using.
