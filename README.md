# Bunny Game Engine Framework: 2D and 3D Development for Multiple Platforms

## Introduction
Bunny is a versatile game engine framework designed to empower developers to create immersive experiences across various platforms. With support for both 2D and 3D game development, Bunny offers a comprehensive suite of tools and features to streamline the development process.

## Features

### Cross-Platform Compatibility
Bunny supports deployment across multiple platforms, including:
- Windows
- macOS
- Linux
- iOS
- Android
- Web (HTML5)

### 2D and 3D Rendering
Utilizing modern rendering techniques, Bunny enables developers to create captivating 2D and 3D graphics with ease. Whether it's pixel-perfect 2D sprites or complex 3D environments, Bunny provides the flexibility and performance needed to bring visions to life.

# Build from Source 
Developers have the option to build Bunny from source using CMake, a widely-used build system. This allows for easy customization and integration into existing development pipelines. By following the provided CMake configuration, developers can compile Bunny with their preferred settings and dependencies, ensuring a seamless integration into their projects.


### Installion 
To build Bunny from source using CMake, follow these steps:

1. **Clone the Repository**: Start by cloning the Bunny repository from the source control system of your choice (e.g., GitHub).
   
   ```bash
   git clone https://github.com/bunnyengine/bunny.git
   ```

2. **Navigate to the Build Directory**: Create a directory for the build files and navigate into it.

   ```bash
   cd bunny
   mkdir build
   cd build
   ```

3. **Configure the Build with CMake**: Use CMake to configure the build. You can specify build options and settings during this step.

   ```bash
   cmake ..
   ```

   Optionally, you can specify additional options such as the installation directory or build type.

   ```bash
   cmake -DCMAKE_INSTALL_PREFIX=/path/to/installation/directory -DCMAKE_BUILD_TYPE=Release ..
   ```

4. **Build the Project**: Once CMake has configured the project, you can build Bunny using your preferred build tool (e.g., Make, Visual Studio, Xcode).

   ```bash
   cmake --build .
   ```

   This command will invoke the appropriate build tool based on your platform and configuration.

5. **Install (Optional)**: If desired, you can install Bunny to the specified installation directory using the following command:

   ```bash
   cmake --build . --target install
   ```

   This will copy the necessary files to the designated installation directory for later use.

6. **Run Examples and Tests**: After building Bunny, you can run provided examples and tests to ensure everything is working as expected.

   ```bash
   ./bin/examples
   ```

   This command will execute the examples included with Bunny, allowing you to explore its capabilities and functionality.

By following these steps, you can successfully build Bunny from source using CMake. Adjust the configuration options and build settings as needed to fit your specific requirements and development environment.


### Flexible Scripting
Developers can harness the power of scripting languages such as Lua or JavaScript to create game logic and behaviors. Bunny's flexible scripting interface allows for rapid prototyping and iteration, empowering developers to iterate quickly and efficiently.

### Physics Engine Integration
Bunny seamlessly integrates with popular physics engines like Box2D and Bullet Physics, enabling realistic simulations and interactions within game worlds. Whether it's simulating realistic object dynamics or implementing complex collision detection, Bunny's physics engine integration simplifies the development process.

### Audio Support
From immersive soundscapes to dynamic sound effects, Bunny provides robust audio support to enhance the gaming experience. Developers can easily integrate audio assets and control playback to create engaging auditory experiences.

### User Interface Design
With Bunny's built-in UI toolkit, developers can design intuitive user interfaces for their games. Whether it's menus, HUD elements, or interactive widgets, Bunny's UI system simplifies the creation and customization of user interfaces.

### Asset Management
Bunny includes a powerful asset management system to streamline the organization and loading of game assets. From textures and models to audio files and scripts, Bunny manages assets efficiently, optimizing performance and simplifying project management.

## Conclusion
Bunny Game Engine Framework offers a comprehensive solution for 2D and 3D game development across multiple platforms. With its extensive feature set, flexible scripting, and robust toolset, Bunny empowers developers to unleash their creativity and create compelling gaming experiences. Whether you're an indie developer or part of a studio, Bunny provides the tools and support needed to bring your vision to life.
