# STM32-MPU9250-Example
This project shows how to set up a communication between STM32 and MPU9250 over SPI.
To be specific, I configured SPI using STM32CubeMX and sampled Accelerometer and Gyroscope at 1 kHz. 
In addition, timer update interupt was used to control the sampling frequency. 

Datasheet MPU9250: https://invensense.tdk.com/wp-content/uploads/2015/02/PS-MPU-9250A-01-v1.1.pdf
Register map: https://invensense.tdk.com/wp-content/uploads/2015/02/RM-MPU-9250A-00-v1.6.pdf

STM32 board in this project: Nucleo-l476rg 

The video tutorial of this code can be found on this link:
https://youtu.be/UEnWlSgGPiE

If you want to get more exhaustive information about IMU sensors and attitude estimation, please visit:
https://www.steppeschool.com/courses/stm32-hal-orientation-estimation


