Rosserial Mbed Libraries
===========================

This repository consists of he contents of the `ros_lib` directory created by
running the script `rosrun rosserial_mbed make_libraries.py`. It exists just
to be uploaded to the PlatformIO Library Registry.

To make it compile, 2 changes has been made:
1. In file MbedHardware.h, changed import BufferedSerial.h to BufferedSerial/BufferedSerial.h
2. In file BufferedSerial/BufferedSerial.h, changed import Buffer.h to Buffer/Buffer.h
