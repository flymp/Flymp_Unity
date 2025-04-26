# Paper Plane Wars - Unity Project

A Unity-based battle simulation game featuring paper planes set in a cozy home environment.

## About the Project

**Paper Plane Wars** is a simulation game where players engage in battles using origami-style paper planes across various rooms of a house, such as the bedroom, kitchen, and living room. Players can maneuver customizable planes and utilize a variety of weapon systems to gain an advantage.

## Installation

### Requirements

- Unity 2022.3 LTS or newer
- Git LFS (Large File Storage)

### Setting Up the Development Environment

1. Clone this repository:
    ```bash
    git clone https://https://github.com/flymp/Flymp_Unity.git
    ```

2. Open the project using Unity Hub.

## Branching Strategy

- `main`: Stable and production-ready releases
- `develop`: Ongoing development branch
- `feature/<feature-name>`: New feature development
- `bugfix/<bug-name>`: Bug fixes and patches

## Commit Guidelines

Use the following format for commit messages:

    [area]: Describe the action in the present tense

    - Detail 1
    - Detail 2
    
## Project Structure

- `Assets/Scripts`: C# script files
- `Assets/Prefabs`: Prefabricated objects
- `Assets/Models`: 3D model assets
- `Assets/Materials`: Material assets
- `Assets/Scenes`: Unity scenes
- `Assets/Plugins`: External plugins

## WebGL Build Instructions

This project can be built for the web using Unity’s WebGL platform and integrated with the React frontend. To build for WebGL:

1. Go to **File > Build Settings**.
2. Select **WebGL** as the target platform.
3. Configure the necessary settings in **Player Settings**.
4. Build the project.
5. Copy the generated build files into the designated folder of the web project.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
