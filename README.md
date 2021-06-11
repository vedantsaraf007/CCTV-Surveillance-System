# CCTV Surveillance System

Object detection and LIVE surveillance feed by using Raspberry Pi 3
The camera will send you an email with an image of any objects it detects. It also runs a server that provides a live video feed over the internet.

I also used the latest version of Raspberry Pi 8mp camera which initially needs to be configured on your device.

This project uses openCV to detect objects in the video feed and to view it we must go to the unique IP address of our Raspberry Pi on the browser
To view on any other network oyher than this , we used ngrok to expose a new local tunnel.

Use of external elements :- 
Raspberry Pi (any version)
Hardware Framework of CCTV
imutils functions
Raspberry Pi camera
Flask-BasicAuth 0.2.0
