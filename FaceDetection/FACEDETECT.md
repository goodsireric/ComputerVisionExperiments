# OpenCV Face Detection  

This project tests face and eye position detection. The goal was to benchmark opencv 4 cascade classifier on the Rockchip RK3399, which is an SoC 6-core Cortex-A72 and A53 ARM. 
https://en.t-firefly.com/product/rk3399.html

The results were less than impressive, at a frame rate of only 2 frames per second on a 480x640, grayscale image:

![Image showing face detection, with a frame rate in the top corner showing 2 fps](Images/Capture%20-%20Face%20detection_screenshot_26.06.2022.png "OpenCV cascade classifier face detect FPS")

----
### Setup 
The Firefly RK3399 bord was configured with Linux, Ubuntu 18.04.6 LTS, based on the instructions on the firefly website:
https://wiki.t-firefly.com/en/Firefly-RK3399/index.html

