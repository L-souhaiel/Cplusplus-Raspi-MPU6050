# MPU6050
A C++ module for accessing the MPU-6050 digital accelerometer and gyroscope on a Raspberry Pi.

![Layout](https://github.com/TitiLouati/Cplusplus-Raspi-MPU6050/blob/main/MPU_6050_Driver/mpu6050.png)

# Example
Assuming that the address of your MPU-6050 is 0x68, you can read accelerometer data from Test.cpp like this:

```
acceleration in x_achse : ...g.
acceleration in y_achse : ...g.
acceleration in z_achse : ...g.

Temperature : ...C

Rotation by x_achse : ...deg/s.
Rotation by y_achse : ...deg/s.
Rotation by z_achse : ...deg/s.

by Accelerometer  ==> Rotation Angle by the X achse : .... deg. 
by Accelerometer  ==> Rotation Angle by the Y achse : .... deg. 
by Accelerometer  ==> Rotation Angle by the Z achse : .... deg. 

```
# Dependencies
install G++ compiler by instaling : libc6-armel-cross libc6-dev-armel-cross binutils-arm-linux-gnueabi libncurses5-dev build-essential bison flex libssl-dev. 

# Installation
To install this project follow those seteps: 

```
git clone https://github.com/TitiLouati/Cplusplus-Raspi-MPU6050.git

```
Then:

from Test folder run : 

```
g++ -o test test.cpp ../mpu.cpp ../mpu.h && ./test

```

or run: 

```
python3 waf-2.0.20.py

```








