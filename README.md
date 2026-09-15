# EEELunarRover-Project

This is a team project completed at Imperial College London for Electrical and Electronic Engineering students. The rover can be controlled through a browser using a keyboard or a ps4 controller, and uses sensors to identify simulated lunar rocks. Our team finished 3rd out of 30 teams.

##My Contribution

- Developed a browser interface using HTML, CSS and JavaScript to control the rover over WiFi, with
real-time controller inputs, visual user feedback and adjustable controls.
- Collaborated with team members to integrate their sensor-processing code with the rover’s movement
controls and browser interface.
- Applied differential-drive control in C++ on the rover’s microcontroller and reduced HTTP requests by
78% through iterative testing, while keeping the rover movement and the browser interface smooth.

The WiFi setup was mostly done by the starter code that was given to us. All the code in webpage.html was written by me, however the code that is to due with processing data from teh sensors themselves in src/main.cpp was not written by me, but was written by my teammates instead.

The browser currently sends requests to `192.168.0.21`. To run it you would need to update the network settings and browser IP address.

##Files
- webpage.html — browser interface and control requests.
- src/main.cpp — movement controls, sensor processing and web-server code.
- platformio.ini — board configuration and library dependencies
