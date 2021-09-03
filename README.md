# webcamtest

webcamtest.cpp

This is a simple example webcam test program using SDL2. It only support yuy2 format. The UVC device should have VID:0x04b4&PID:0x00f9.

Tested Platform: RaspberryPi 400 & Ubuntu

Author: Eddie Zhao

Version : 1.02

Date: 8/12/2021Cancel changes

Build:

sudo apt-get install libusb-1.0-0-dev libsdl2-dev

git clone http://github.com/zhao1mh/webcamtest.git
cd webcamtest
./configure
make
