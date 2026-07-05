---

# SlideSense

## An Intelligent Landslide Detection and Alert System

SlideSense is an IoT-based landslide monitoring and early warning system designed to identify environmental conditions that may lead to landslides and provide timely alerts. The project integrates sensor data acquisition, microcontroller-based processing, and a web-based monitoring dashboard to improve disaster preparedness and reduce potential risks to life and infrastructure.

---

## Features

* Real-time monitoring of environmental parameters
* Early detection of landslide-prone conditions
* Web-based dashboard for live data visualization
* Alert mechanism for risk notification
* IoT-enabled sensor integration
* Simple and user-friendly interface

---

## Technology Stack

### Hardware

* Microcontroller (Raspberry Pi Pico or equivalent)
* Environmental sensors (soil moisture, tilt, vibration, etc.)
* I2C communication module

### Software

* Python – Sensor data acquisition and processing
* PHP – Backend logic and data handling
* HTML / CSS – Frontend user interface
* JavaScript – Dashboard interaction
* MySQL (optional) – Data storage

---

## Project Structure

```bash
SlideSense/
│
├── i2c.py              # I2C communication with sensors
├── pico.py             # Microcontroller control logic
├── index.php           # Landing page
├── dashboard.php       # Monitoring dashboard
├── assets/             # CSS, JavaScript, images
├── README.md           # Project documentation
```

---

## System Workflow

1. Sensors continuously collect environmental data
2. The microcontroller processes and evaluates sensor readings
3. Processed data is transmitted to the server
4. The web dashboard displays real-time monitoring information
5. Alerts are generated when predefined safety thresholds are exceeded

---

## How to Run the Project

### Prerequisites

* Python 3.x
* PHP server (XAMPP, WAMP, or LAMP)
* Microcontroller with connected sensors

### Steps

1. Clone the repository:

   ```bash
   git clone https://github.com/harshrmeshram/SlideSense.git
   ```
2. Upload `pico.py` to the microcontroller
3. Place the PHP files in the server root directory
4. Start the PHP server
5. Open `index.php` in a web browser to access the dashboard

---

## Future Scope

* SMS and email-based alert notifications
* AI-based landslide prediction models
* Cloud-based data storage and analytics
* Mobile application integration
* GPS-based location tracking

---

## Authors

**Harsh Rahul Meshram**
B.Tech – Artificial Intelligence and Data Science
Nagpur, Maharashtra, India

Email: [harshr.meshram@gmail.com](mailto:harshr.meshram@gmail.com)
GitHub: [https://github.com/harshrmeshram](https://github.com/harshrmeshram)

**Rutika Joge**
Co-Author and Project Contributor

---

## Patent and Copyright Notice

This project, *SlideSense – An Intelligent Landslide Detection and Alert System*, is protected under applicable patent and copyright laws.

* Patent status: Applied / Filed
* Copyright: © All rights reserved by the authors

Unauthorized copying, reproduction, modification, distribution, or commercial use of this project, in whole or in part, without explicit written permission from the authors is strictly prohibited.

This repository is made available solely for academic, demonstration, and evaluation purposes.

---

## License

This project is not open-source.
Usage is restricted to educational and non-commercial review purposes unless prior permission is obtained from the authors.

---
