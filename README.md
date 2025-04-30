# Humidity Regulator

## Overview
This project develops an automated smart humidifier system that regulates indoor humidity for optimal comfort and health using an ESP microcontroller and DHT11 sensor. The system activates the humidifier when the humidity falls below a set threshold and stops once it reaches the desired level, ensuring a comfortable indoor environment.

## Features
- **Automatic Humidity Regulation**: Monitors and adjusts room humidity levels automatically.
- **Smart Control**: Uses ESP microcontroller and DHT11 sensor for real-time data collection and control.
- **Energy-Efficient**: The system activates only when needed, optimizing energy use.
- **Health Benefits**: Helps prevent discomforts such as skin dryness, respiratory issues, and dehydration due to low humidity.

## Components Used
- **ESP Microcontroller**: Controls the system and triggers the humidifier.
- **DHT11 Sensor**: Measures humidity and temperature.
- **Piezoelectric Transducer**: Generates ultrasonic mist to increase humidity.
- **555 Timer IC**: Controls timing for ultrasonic mist generation.
- **MOSFET and Relay**: Switches high-power components like the mist maker.
- **Capacitors and Resistors**: Stabilize the timing and frequency of the system.

## Methodology
- **Data Collection**: Humidity and temperature data are collected over several hours.
- **Environmental Testing**: Data is recorded in different room conditions: closed room with fan, open room with air circulation, and closed room without airflow.
- **Graphical Analysis**: Visualized using graphs to analyze humidity and temperature fluctuations.

## Results
- The system effectively maintains humidity around 50% RH.
- A hysteresis control strategy reduced wear on the humidifier and stabilized humidity levels.
- Different environmental conditions impact the frequency of humidifier activation.

## Future Recommendations
- **Smart Home Integration**: Add support for remote control via mobile apps.
- **Energy Optimization**: Improve the efficiency of the mist generation system.
- **Additional Sensors**: Integrate air quality sensors (e.g., PM2.5, CO2) for better environmental control.

## References
- "Effects of Low Humidity on Human Health," Environmental Health Perspectives, 2020.
- "Ultrasonic Humidification Techniques," Journal of Applied Physics, 2019.
- "DHT11: Low-Cost Humidity and Temperature Sensor," Electronics Journal, 2018.

## Liscense 
This project is developed by students of IIT Delhi
- Maan Soni
- Ayush Chandra
- Tamme Mokshagna
