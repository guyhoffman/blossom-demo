# Blossom Demo Code

Demo Code for Blossom Video Tracking

<<<<<<< HEAD
Robot setup:
- Plug in HDMI, power, keyboard, mouse
- Connect to wifi through wifi logo in menu bar
- Hover over wifi logo in menu bar to get IP address from wlan0 *OR* use ifconfig in terminal 
- ssh into the Pi from your computer using the IP address found
    - ssh pi@{ip address}
- If it asks something along the lines of “The authenticity of host … can’t be established”, say “yes”
- Password is projblossom

In pi, start RMS:
- cd RMS
- sudo java -jar javaExt-all-1.0-SNAPSHOT.jar blossom cli
- make sure that the server is up and running
    - After sequences are loaded, it should say 
    - WLAN0 Device IP: {ip address}
    - Server UP and running on port 5555
- Init robot (see video)
    - Reel in motors and hold head down 
    - Press enter
    - Type reset
    - Press enter

On local computer:
- In the google_demo.html file in the google_demo folder, edit “url_list” on line 136 to the IP address found in the previous step
    - var url_list = [“{ip address}”]
- Open google_demo.html in a browser
- Play video
=======
## Instructions

### Robot Side (Raspberry Pi)

- Plug in the robot's RPi using its power supply
- Connect HDMI, USB Keyboard, and USB Mouse

### Video Browser Side (Web)
>>>>>>> 0a854ae600e5db8a975a0a9edb587213be6bd3b4
