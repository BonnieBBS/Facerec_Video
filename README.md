This is a demo of facial recognition from video.
You can find much more detail from here: http://docs.opencv.org/trunk/modules/contrib/doc/facerec/tutorial/facerec_video_recognition.html

It contains the code and testing data.
All you need is in the demo_src folder.
Run the demo by the following steps:
1. Install relative packages, opencv and cmake.
2. [Optional] Copy files from the demo_src folder which can make the folder clean.
3. Go to the directory of those files and input the commands
    $ cmake .
    $ make
    $ ./T </path/to/haar_cascade> </path/to/csv.ext> </path/to/device id>  // </path/to/device id> is /dev/video0 in my case
4. Enjoy the result
