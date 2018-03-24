## Run Server
To run the server, follow the steps below for your operating system:
  a) Unix-based:
    i)  Navigate to this folder in the console
    ii) Execute the following commands
      chmod +x serverBash.sh
      ./serverBash.sh
  b) Windows:
    i)  Double click the serverBat.bat file in this folder

Note: You must have Java installed on the machine that the server is running on

## Run Client
ADB must be installed and accessible from command line.

1. Run adb devices to get simulator names. 
2. Run adb -s [emulator_name] install app-debug.apk 

The emulators should be Nexus 5 or Nexus 7 with Android 7.1.1 and API level 25.
