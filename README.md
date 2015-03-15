# Voice-controlled-robot
Controlling an irobot using voice. The irobot doesnt have a voice module thus my team used a software called Julian with a library called Julius to give the robot input using BAM(Bluetooth module).
Julius saved the voice input in the form of a file. We then scaned the file for the input if the modification time of the file is changed, thus making sure that there has been a new command.We then deleted the file and ran an infinite loop to make the code realtime.
1)Installing Julian:
  a)sudo apt-get install julian
2)Download julius:
  a)http://julius.sourceforge.jp/en_index.php#latest_version
