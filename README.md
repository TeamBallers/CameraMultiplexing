# CameraMultiplexing

## AdapterTestDemo.py
This script uses the GPIO pins to control multiplexer and I2C to write to it and inform it of cameras to be used. It also uses libcamera to take pictures. If successful, there will be four pictures in the same directory at the end of the script. This is unmodified from Arducam's RaspberryPi repository. 

## previewOpencv.py
This script would only theoretically work if AdapterTestDemo.py also works. It is an application that takes images two at a time from each camera in sequence. The delay between switching cameras was set to 200ms. Pictures are saved as .jpg files. This is a modified version of the script found on Arducam's RaspberryPi repository to change output from being visualized on a GUI to saved as files. 
