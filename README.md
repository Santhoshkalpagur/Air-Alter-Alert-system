Project Title: Air Alter Alert system: A Mobile Environmental Monitoring and GPS Tracking Platform
Long Description
This project is our first-place winning entry from the iot-ignite hackathon. Our goal was to build a versatile, low-cost mobile rover capable of navigating an area while simultaneously collecting and transmitting critical environmental data in real-time.

The foundation of the rover is a custom-built chassis controlled by an ESP8266 microcontroller. The ESP8266 hosts a self-contained web server, making the rover accessible to any device with a web browser on the same Wi-Fi network. The web interface, served directly from the rover, provides intuitive controls for movement—forward, backward, left, and right. The server code is designed to parse URL requests to precisely manage the speed and direction of the left and right motors, allowing for nuanced navigation through its environment.




We elevated this remote-control platform by integrating two critical sensor modules:

GPS Tracking: A GPS module is connected to the ESP8266, allowing the rover to acquire its precise geographical coordinates. This data is streamed to the web interface, enabling us to track the rover's location live on a map and create a data log of its path.

Air Quality Sensor: An onboard air quality sensor actively measures airborne particulates and harmful gases. This allows the rover to function as a mobile environmental monitoring station, providing real-time air quality index (AQI) readings for its specific location.

The unified web dashboard is the core of the user experience, presenting the motor controls, live GPS coordinates, and up-to-the-second air quality data in a single, accessible view. This fusion of mobility, precise location tracking, and environmental sensing created a powerful and practical IoT device that can be deployed for tasks like mapping urban pollution, assessing conditions in areas unsafe for humans, or monitoring agricultural environments. It was this comprehensive, integrated solution that we believe secured our first-place victory.
