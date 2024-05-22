# Installation of Simplicity studio -V5
To know more about Simplicity Studio, you can go through the user guide
(https://docs.silabs.com/simplicity-studio-5-users-guide/5.3.0/ss-5-users-guide-overview/)
Search Silicon labs Simplicity Studio on a browser,
Create an Account in Simplicity Studio and
Click on Required Installer
<img src="https://github.com/Joswitha-123/wisunreadme/blob/main/Screenshot%202024-05-22%20104138.png" alt="MLBC">

Go through the below video for complete installation process
(https://youtu.be/ONrmMEgFYMo?si=FESHt9YXUVKaqHwz)
SDK Version: Gecko SDK Suite v4.4.2
# Getting Started with Wi-SUN
#Setting Up Wi-SUN Border Router
To setup Wi-SUN Br follow the below repository
(https://github.com/SiliconLabs/wisun-br-linux)
# Installation of Wi-SUN Border Router GUI
Follow the below Repository to setup BR GUI
(https://github.com/SiliconLabs/wisun-br-gui)
# Cockpit Launch

Cockpit features are accessible through its Web interface. It is available at http://[border router server]:9090/.
If the plugin was installed correctly, it should appear in the left side panel of Cockpit's Web interface as Wi-SUN Border Router.
After setting up login by providing the required credentials

<img src="https://github.com/Joswitha-123/wisunreadme/blob/main/Screenshot%202024-05-22%20105145.png" alt="MLBC">

# Wi-SUN Dashboard

The Wi-SUN Dashboard tab provides direct access to wsbrd.conf configuration file. It gives the ability to change your wsbrd configuration without the need to physically access the Raspberry Pi. The Wi-SUN Border Router service box allows the user to start, restart or stop the Wi-SUN Border Router service by clicking the three dots dropdown. The other boxes expose the Wi-SUN Border Router active configuration.
<img src="https://github.com/Joswitha-123/wisunreadme/blob/main/Screenshot%202024-05-22%20105200.png" alt="MLBC">
# FAN1.1-FSK-Application:
Node Monitoring
Wi-SUN Node Monitoring is an extendable node monitoring application that provides information on the device, board, application, and connection statistics. It can be easily extended to monitor sensors and control actuators.
# Adding Required Repositories:
Add the Wi-SUN Applications Repository to Simplicity Studio
1. Open Simplicity Studio and connect the Main board.
<img src="https://github.com/Joswitha-123/wisunreadme/blob/main/Screenshot%202024-05-22%20110119.png" alt="MLBC">
2. Navigate to `Window` -> `Preferences` -> `Simplicity Studio` -> `External Repos`.
<img src="https://github.com/Joswitha-123/wisunreadme/blob/main/Screenshot%202024-05-22%20110129.png" alt="MLBC">
<img src="https://github.com/Joswitha-123/wisunreadme/blob/main/Screenshot%202024-05-22%20110141.png" alt="MLBC">
<img src="https://github.com/Joswitha-123/wisunreadme/blob/main/Screenshot%202024-05-22%20110151.png" alt="MLBC">
3. Click on `Add` and paste the URI of the repository: 
(https://github.com/SiliconLabs/wisun_applications.git)
<img src="https://github.com/Joswitha-123/wisunreadme/blob/main/Screenshot%202024-05-22%20110202.png" alt="MLBC">
<img src="https://github.com/Joswitha-123/wisunreadme/blob/main/Screenshot%202024-05-22%20110212.png" alt="MLBC">
<img src="https://github.com/Joswitha-123/wisunreadme/blob/main/Screenshot%202024-05-22%20110223.png" alt="MLBC">
<img src="https://github.com/Joswitha-123/wisunreadme/blob/main/Screenshot%202024-05-22%20110232.png" alt="MLBC">

# Adding Repository for updated codes:
Clone the below Repository in your system 
(https://github.com/vaibhavnaware01/FAN11_FSK_FG25.git)

# Create Bootloader Project:
1.	Click on `Bootloader- SoC SPI Flash Storage( 1024)` and then click on `Create`.
<img src="https://github.com/Joswitha-123/wisunreadme/blob/main/Screenshot%202024-05-22%20112354.png" alt="MLBC">
2.check the project configuration
<img src="https://github.com/Joswitha-123/wisunreadme/blob/main/Screenshot%202024-05-22%20112402.png" alt="MLBC">
3.Open Configuration File
   - Open the `.slcp` file in your project directory.
<img src="https://github.com/Joswitha-123/wisunreadme/blob/main/Screenshot%202024-05-22%20112412.png" alt="MLBC">
4.Configure Software Components- Configure the necessary software components as required for your project.
<img src="https://github.com/Joswitha-123/wisunreadme/blob/main/Screenshot%202024-05-22%20112421.png" alt="MLBC">
Install LZMA
<img src="https://github.com/Joswitha-123/wisunreadme/blob/main/Screenshot%202024-05-22%20112429.png" alt="MLBC">
5.Build the Project- Build the project to compile the code and prepare it for flashing.
<img src="https://github.com/Joswitha-123/wisunreadme/blob/main/Screenshot%202024-05-22%20112440.png" alt="MLBC">
Ensure the build completes with zero errors.
<img src="https://github.com/Joswitha-123/wisunreadme/blob/main/Screenshot%202024-05-22%20112448.png" alt="MLBC">
6.Erase and Flash to the Device:
   - Navigate to the `.s37` file in the binaries folder.
   - First, erase the existing firmware on the device.
   - Then, program and flash the new firmware onto the device.
<img src="https://github.com/Joswitha-123/wisunreadme/blob/main/Screenshot%202024-05-22%20112502.png" alt="MLBC">
<img src="https://github.com/Joswitha-123/wisunreadme/blob/main/Screenshot%202024-05-22%20112514.png" alt="MLBC">




