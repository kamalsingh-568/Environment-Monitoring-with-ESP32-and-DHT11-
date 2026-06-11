# Environment Monitoring with ESP32 and DHT11

## Objective

To monitor temperature using a DHT11 sensor interfaced with an ESP32 and generate an alert when the temperature exceeds a predefined threshold.

## Components Used

* ESP32 DevKit V1
* DHT11 Temperature Sensor
* Jumper Wires
* USB Cable

## Connections

* VCC → 3.3V
* GND → GND
* DATA → GPIO4 (D4)

## Working

The ESP32 reads temperature data from the DHT11 sensor every 2 seconds and displays it on the Serial Monitor. When the temperature exceeds 30°C, an alert message is displayed.

## Project Files

* Source Code (.ino)
* Real Hardware Setup Image
* Serial Monitor Output Screenshot
* Demo Video

## Output

Temperature values are displayed on the Serial Monitor, and an alert is generated when the threshold temperature is crossed.

