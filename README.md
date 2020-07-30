# Tello
What you need to program Tello EDU drone -

1. Download Python 3.8
2. Install openCV libraries using python pip
  a. pip3 install opencv-python
  b. pip3 install opencv-contrib-python

Tello drone in Interactive Mode
If you would like to run Tello in interactive mode, then run 'python Tello-Int.py'. In interactive session, you can type in commands (from Tello EDU SDK2.0 manual) and have Tello respond to them.

Tello drone in Command Mode
If you would like to run Tello in command (file) mode, then modify commands.txt file with sequence of commands you would like Tello to execute. Run 'python Tello-cmd.py'

Tello drone following an object (up/down/left/right/forward/backward)
If you would like Tello drone to track an object, please run 'python BallTracker.py'. It is pre-configured with circular blue object tracking. If you would like to change it, then modify self.ball_color_low and self.ball_color_high in the BallTracker.py file (line 21, 22). Please note that these values are not RGB, but rather HSV. If you would like to save an image snapshot (from your Tello live video), then press 's'. It will save the image file in directory specified at BallTracker.py (line 31).
