# RAM-Dump-Collection-Tool
A cross-platform tool to link multiple different technologies under a single executable which can collect live RAM dumps or acquire old RAM dumps generated automatically during a crash.

This tool is supposed to achieve the following tasks:
# OS-Responsive
  # Windows
  Prompt the user to acquire an old dump file or create a new live dump using PowerShell script and save it in a USB drive for further analysation.
  
  # Linux or MacOS
  Prompt the user to acquire an old dump file or create a new live dump using Bash script and save it in a USB drive for further analysation.
  
# OS-Not-Booting
In this case we'll provide a lightweight bootable OS which can be configured from the BIOS to boot into and then automatically copy the old RAM dump file to the USB drive.

# Cross-Platform-Linking
We somehow need a single executable which can detect the OS and execute the corresponding script after prompting the user. Possible solution HTML->JavaScript->Node.js (Still working on a solution).

# Dedicated-Installer
An OS specific installer which can download and install only the required components as per use case basis of the user.
