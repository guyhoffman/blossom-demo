# Blossom Demo Code

Demo Code for Blossom Video Tracking

Robot setup:
- Plug in HDMI, power, keyboard, mouse
- Connect to wifi through wifi logo in menu bar
- Hover over wifi logo in menu bar to get IP address from wlan0 *OR* use ifconfig in terminal 
- ssh into the Pi from your computer using the IP address found
    - ssh pi@{ip address}
- If it asks something along the lines of “The authenticity of host … can’t be established”, say “yes”
- Password is projblossom

On pi, update movement files:
- Copy the files from the 'movement' folder to '/home/pi/RMS/robots/blossom/movement'

On pi, start RMS:
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
- In a terminal, navigate to the blossom-demo folder
- Run script to set IP address for video
    - ./set_ip.sh {ip address}
- Open google_demo.html in a browser
- Play video

