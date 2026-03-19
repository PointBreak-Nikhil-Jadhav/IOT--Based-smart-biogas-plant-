# IOT--Based-smart-biogas-plant
Overview:
This project is an IoT-based monitoring system designed to track the internal conditions of a miniature biogas plant in real-time. Built around the ESP8266 microcontroller, the system continuously measures critical anaerobic digestion parameters—temperature, pressure, and pH levels—using submerged hardware sensors.

How it Works:
Instead of relying on external cloud services or internet connectivity, the ESP8266 acts as a standalone local web server. It processes the raw sensor data and hosts a responsive, custom web dashboard. Any device (smartphone, tablet, or computer) connected to the same local Wi-Fi network can access this dashboard via a standard web browser to view live metrics.

Key Features:

Real-Time Data: Utilizes AJAX to automatically refresh sensor readings on the web page every two seconds without requiring a page reload.

Edge Computing: All sensor calibration, data processing, and web hosting are handled locally on the ESP8266.

Core Metrics Tracked:

Temperature: Monitored via a waterproof DS18B20 sensor.

Gas Pressure: Monitored via an I2C BMP280 sensor.

Slurry pH: Monitored via an analog pH probe.

Cost-Effective & Scalable: Uses off-the-shelf, affordable components that can be easily scaled up for larger digesters or adapted to include cloud logging in the future.

Key concept :- by monitoring temperature and pressure and ph of the plant we can control the microbiological process of gas production which increases the production of the Biogas .
