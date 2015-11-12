# makey-arduino
Files for using a Sparkfun MakeyMakey as an Arduino.  These instructions are for OSX.

Before plugging in the MakeyMakey, download the Arduino programming environment (if you don't already have it):

https://www.arduino.cc/en/Main/Software

Unzip the Arduino file, place the Arduino app in Applications, then launch the Arduino app.  
Once Arduino programming environment is up and running, quit the application.

Download and unzip both of the above zip files.  
Place both files in your "Arduino" folder which should have been automatically set-up in your "Documents" folder.

Plug in the MakeyMakey into a USB port.

Relaunch the Arduino app, under the tools menu there is an item called "Board"
This is a long list of all the possible Arduino boards, at the very end of the list should be "Sparkfun MakeyMakey"

Select this board, then under the next menu item under "Port:" select the port that your MakeyMakey is connected to
- it should be some sort of "USBModem" port on a Mac.

You should be set to program the MakeyMakey as an Arduino...to upload the original MakeyMakey Arduino sketch 
into the MakeyMakey open the "makeyMakey.ino" that you unzipped into your Arduino folder (in "Documents) and upload that file.

Or upload a file of your choosing, like one of the sensor sketches from this repo:
https://github.com/deviceofmind/arduino-processing

And try the Makey - nee Arduino - with Processing.

