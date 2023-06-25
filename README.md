# 4x4 Surveillance Vehicle
*tl;dr - Built an all-terrain surveillance vehicle to monitor agricultural land (soil moisture, etc.) with an ESP32 microcontroller and live feed accessed through a web interface*
</br>*all arduino code is in a single file, including that for the web UI*
</br>The Surveillance Car is an Internet of Things project for environmental monitoring that utilizes an ESP32 microcontroller to monitor and control a remote vehicle. The ESP32 is a low-cost, low-power microcontroller that is well suited for IoT projects due to its built-in Wi-Fi and Bluetooth capabilities. The remote-controlled car is meant to be used for surveillance purposes, and may be upgraded to include more sensors for monitoring conditions (e.g., if used on agricultural land, soil moisture sensor). The car is equipped with a camera, and connected to an ESP32 microcontroller, which processes data and transmits it back to a web interface which displays a live feed from the camera. The user controls the car from this web interface. The user can drive the car, adjust the camera, and adjust light levels remotely.
</br> Note: We cannot directly upload code to ESP32 module as it does not have a dedicated port for it. To mitigate this, an Arduino is used to upload the code for the ESP32 cam.
</br>
![image](https://github.com/omar-oahmad/camera-car/assets/56760327/c0217f78-a726-48e7-b076-c1ea7fe3a732)

