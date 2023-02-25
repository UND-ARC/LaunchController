# Launch Controller
The main controller for the UND ARC rocket launch system. This repository contains the all the CAD files, Circuit 
Diagrams, and Code for the launch system.

### Description
There are 2 main components to the system, the controller and 
the launcher. The launcher remains by the pad and directly connects to the 

### User Guide
WIP

### Software Requirements
- PlatformIO
  - Python 3.11
- CLion IDE
  - PlatformIO Plugin
- Solidworks Student Edition 2022
- GIT
- Circuit-Diagram.org (for schematic editing)
- Vector Graphic Software/reader (browser should be able to open files)

### Hardware
See part list spreadsheet. Note that all circuits are currently built on proto PCB. Custom PCBs are currently in 
development.

### Installation (WIP)
1. Create a GitHub Account
2. Download and install Git [LINK](https://git-scm.com/downloads)
3. Clone the repository: [https://github.com/UND-ARC/LaunchController.git](https://github.com/UND-ARC/LaunchController.git)
4. Set your local path to 'C:/Projects/Launch Controller'. Note, you may need to create manually the parent "Projects"
folder (do not create the "Launch Controller" repository folder)
5. Install python 3.11
   - (Windows) add the python directory to the PATH variable. Note some version of Windows have additional program Alias
   settings that override the path variable, the Python alias will need to be disabled.
6. Run the get-platformio.py script from the terminal. DO NOT launch it directly since CMD will auto close at the script. 
Follow the prompts to complete the installation.
7. Install CLion. You will need to make a JetBrains Account with your university email to get an education license for
the software.
8. Add the platformio plugin to CLion. You may need to add the platformio scripts path to the plugin settings.
9. Open the project in CLion and change the build target from test to uno.
10. Re-init platformio
11. The project should now build
11. Message Neko'z in discord to get added to the members list for write access.

## Version History
### Alpha 1.0

## Authors
- [Neko'z](mailto:zachariah.palmer@und.edu)
- [Galbatorix](mailto:mason.motschke@und.edu)
- [JRLemker](mailto:joseph.lemker@und.edu)
## License
[MIT](LICENSE)
