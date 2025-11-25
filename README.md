# Serial-USB-Communication
The following source code demonstrates USB serial communication with an Arduino board (UNO) by combining legacy C code for serial port connection with Objective-C for the MacOS interface.  Threading is employed to simultaneously print and plot data values.  An Arduino sketch that may be used for testing is included at the bottom of the source code.

Code may be run in XCode by following these steps:

1. Create a new App Project in XCode using Objective-C
2. Delete both pre-supplied AppDelegate files (demo has its own AppDelegate)
3. Delete the entire contents of the 'main.m' file and copy/paste the code below.
4. Very Important: Set App SandBox to NO or app will not run.
5. Hit 'Run' in XCode to run the app.
6. Make sure the Arduino board is plugged into the USB port of your system with the source code at the bottom uploaded to it.
7. Select your Arduino board, set the baud rate to 9600, then hit the 'Connect' button.  You should see a sawtooth pattern plotted in the GraphView.
8. Hit 'Disconnect' when done.

<img width="759" height="225" alt="sandbox" src="https://github.com/user-attachments/assets/e9fa307d-c76d-4047-8b96-ba19ee91b8af" />
<img width="758" height="536" alt="serial" src="https://github.com/user-attachments/assets/7daf8887-416d-402e-bf68-f3bb16d5aeb7" />
