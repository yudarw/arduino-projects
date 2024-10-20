# Arduino Programming with VSCode
To start using VSCode for your Arduino projects, follow the steps below:

### Step1 - Download and Install Drivers
VSCode uses the drivers that are installed with the Arduino IDE, so we need to download and install that first.
1. Download the IDE from (https://www.arduino.cc/en/Main/Software).
2. After the download is complete, run the installer, leaving all the default selections and options.
3. Be sure to install the COM port and USB drivers if prompted.

### Step2 - Download and Install VSCode
### Step3 - Install the Arduino Extention
1. Once installed, Launch VSCode
2. Click the Extensions button on the left side of the editor (Ctrl+Shift+X) to display the extension marketplace.
3. Type Arduino in the search bar, to filter the extension to only those related to the Arduino platform.
4. Click the install button and when prompted allow installation of dependencies.
5. Click the Reload button to relaunch VSCode with the Arduino extension enabled.

### Step4 - Programming in VSCode
Now, we're set to start programming. To make sure everything installed properly, we'll start by opening up the example Blinky.
Open VSCode's Command Pallet with Ctrl+Shift+P. Once the command pallete is open, you can start typing to filter all the option or to search for useful commands.
1. Open Command Pallet and type Arduino, then select Arduino:Examples in the result list.
2. In the new pane to the right, select Built-in Examples>>01. Basics>>Blink. By default, this will open a new VSCode window, with the Blink skecth and a Blink.txt help file listed in the explorer pane on the left.
3. Select Blink.ino from the explorer pane to open the sketch in the editor.
4. Connect your Arduino board to your computer, and then, in the bottom bar of VSCode, you can specify the COM port for your Arduino and the board type.
5. Clicking COM opens a small selection window at the top of VSCode that should display your connected Arduino.
6. Clicking <Select Board Type> opens a new pane on the right where you can select the board type. If various configurations are available for your board, then you need to specify those as well. I'm using the Arduino Mega with the ATMega-2560.
7. Open the Command Pallete again (Ctrl+Shift+P) and type Arduino:Upload (Ctrl+Alt+U) to upload the Blink sketch to your Arduino. You should see LED13 start blinking about once per second.
   
 
