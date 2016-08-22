# Rosserial Mbed Libraries #
=====================================

This repository consists of he contents of the `ros_lib` directory created by
running the script `rosrun rosserial_mbed make_libraries.py`.

It exists just to be uploaded to the PlatformIO Library Registry.

## Changes for PlatformIO ##
=====================================

To make it compile under PlatformIO, 2 changes has been made:

1. In file **MbedHardware.h**, changed 
```
#!c++
#include "BufferedSerial.h"
```
to
```
#!c++
#include "BufferedSerial/BufferedSerial.h"
```

2. In file **BufferedSerial/BufferedSerial.h**, changed 
```
#!c++
#include "Buffer.h"
```
to
```
#!c++
#include "Buffer/Buffer.h"
```