# Hand-Gesture-Control-of-Your-Computer
This project consists of mainly three components – Arduino Uno, Ultrasonic sensors, and a laptop.
The ultrasonic sensors hooked to the Arduino are used to determine the gestures and the distance of
the hand from the ultrasonic sensors. The code loaded in Arduino finds the respective keyword for
the distance found and sends it to Windows OS. Python code that runs in the background
recognizes the keywords and generates the corresponding virtual keystrokes for Windows. The
hotkeys then control particular function of the application of intend to run, that is VLC Media
Player. The Arduino coding is done in “Arduino IDE” and uploaded to Arduino Uno. To run the
required python code, we need to complete a few more steps.
#
(1) Python 2.7.14 is downloaded and installed.
#
(2) “pip” function is upgraded, a tool to easily update python modules.
#
(3) PyAutoGUI module is downloaded using the pip function and downloaded through internet in
the Python command screen itself.
#
(4) Then we open “IDLE (Python GUI)”.
#
(5) We create a new file and type in the code.
#
(6) The file is then saved and run
#
With the above steps done, python will be able to receive feedback from the Arduino board and
hence generate virtual keystrokes in Windows OS. The keystrokes then control the hotkeys of the
VLC media player.
