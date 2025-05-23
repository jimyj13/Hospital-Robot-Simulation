# Hospital-Robot-Simulation
Unity project folder &amp; code for Hopsital Robot Simulation Capstone Project under Prof. Joseph Vybihal (W2025)

## SYSTEM/VERSION REQUIREMENTS

### Unity Version: 2020.3.11f1

### OS 
* Windows: Windows 7 (SP+), Windows 10 and Windows 11, 64 bit versions only
* macOS: HIgh Sierra 10.13+
* Linux: Ubuntu 20.04, Ubuntu 18.04, and CentOS 7

### CPU
* Windows: x64 architecture with SSE2 instruction set support
* macOS: x64 architecture with SSE2 instruction set support
* Linux: x64 architecture with SSE2 instruction set support

### Graphics API
* Windows: DX10, DX11, and DX12-capable GPUs
* macOS: Metal-capable Intel and AMD GPUs
* Linux: OpenGL 3.2+ or Vulkan-capable, NVIDIA, and AMD GPUs

### Additional requirements:
* Windows: Hardware vendor officially supported drivers
* macOS: Apple officially supported drivers
* Linux: Gnome desktop environment running on top of X11 windowing system, Nvidia official proprietary graphics driver or AMD Mesa graphics driver. Other configuration and user environment as provided stock with the supported distribution (Kernel, Compositor, etc.)

## HOW TO RUN THE SIMULATION

In the Unity editor, move to the Robot_Menu scene in the scenes folder
While at this scene, click the play button at the top of the editor to start a runtime instance. 

### Controls
Esc: When in the RobotMenu scene, clicking ESC locates the simulation to the HospitalFloor scene
When in a different menu, clicking ESC locates the simulation to the RobotMenu scene
When in the HospitalFloor scene, clicking ESC locates the simulation to the RobotMenu scene

Assigning tasks to the robot is conducted within the RobotMenu scene, which would locate the simulation to a respective menu depending on the button option selected on the RobotMenu scene. The robot would then start conducting the task specified.

To end the simulation, click on the End Simulation button in the RobotMenu scene

## BRIEF OVERVIEW OF THE .CS FILES

