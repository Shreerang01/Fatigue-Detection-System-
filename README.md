
# Fatigue detection system for Driver’s Safety

Road accidents are an alarming concern, with fatigue and drowsiness accounting for a substantial portion of these incidents. Approximately 50% of accidents are attributed to road-related factors, including insufficient driving practices, as well as the presence of drowsy or inebriated drivers. Addressing the challenges associated with preventing these accidents has become imperative. In this context, the integration of IoT-based innovations emerges as a practical and effective approach. IoT, with its real-time capabilities, eliminates the need for human intervention and enables seamless data transfer.

Fatigue, in particular, remains a complex safety issue that has not received comprehensive attention from most countries. Its elusive nature makes it challenging to quantify or observe, unlike more tangible issues such as alcohol and drug impairment, which can be assessed through clear indicators and readily available tests. This project centers on an IoT-based system meticulously crafted to curtail the multitude of mishaps caused by drowsy driving. By monitoring critical aspects such as drivers' eye movements and health-related indicators like heart rate and dizziness, this system aims to significantly enhance road safety and reduce accidents attributable to driver fatigue.

## Table of Contents

- Installation
- Project Link
- Project Components
- Features
- Getting Started
- Schematic
- Usage
- Contributing
- Acknowledgements
- License
## Installation

```bash
  -Go to my project link below
  -Tinker/Copy it on your account
  -Run Locally by starting Simulation
```
    
## Poject Link

https://www.tinkercad.com/things/lSF7QlCoVxk?sharecode=xE1bOHucXAtwlHYiL61o93zvqxn4biqKFKvn-fZG85E
## Project Components

- Board HD Camera (currently using Laptop webcam for testing)
- Arduino UNO
- Potentiometer (250 Kohm)
- Resistor (220 Ohm)
- Resistor (1 Kohm)
- Powerful LED  
- Piezo Buzzer
- LCD 16 x 2
- Bread Board
- Jumping wires





## Features

- **Real-Time Monitoring:** The system continuously monitors the driver's condition in real-time, providing immediate feedback and alerts.

- **Driver Fatigue Detection:** It employs sophisticated algorithms to detect signs of driver fatigue, such as slow or erratic eye movements and changes in vital signs.

- **Health Monitoring:** In addition to detecting drowsiness, the system monitors the driver's health indicators, including heart rate, to identify potential health issues such as heart attacks or dizziness.

- **Alert Mechanisms:** When fatigue or health issues are detected, the system triggers alert mechanisms, including a buzzer and LED indicators, to prompt the driver to stay alert and respond to potential health concerns.

- **Data Logging:** The system records and stores data for analysis, allowing for post-incident review and performance evaluation.

- **IoT Connectivity:** Data can be transmitted in real-time to a remote server or mobile app via IoT connectivity, enabling remote monitoring and analysis.

- **Customizable Alert Thresholds:** Users can customize alert thresholds to adjust the sensitivity of the system to individual driver characteristics and conditions.
## Getting Started

For Actual Implementation

    1. Clone this repository to your local machine.

    2. Open the `Fatigue Detection Hardware.ino` file using the Arduino IDE.

    3. Upload the code to your Arduino UNO R3.

    4. Wire up the hardware components as per the provided schematic.

    5. Power on your Arduino and interact with the system.

    6. Open the python file for Fatigue detection.

    7. Note the Obeservations
## Schematic

![Schematic](https://github.com/Shreerang01/Fatigue-Detection-System-/assets/113919844/cc72423f-2a13-41d6-9ffd-17e2620c7ef9)

## Circuit Diagram

![Circuit Diagram](https://github.com/Shreerang01/Fatigue-Detection-System-/assets/113919844/1b56f06a-4a8a-42d3-ae40-74f057a35d43)


## Usage

- **Vehicle Safety Enhancement:** The primary use of the system is to enhance vehicle safety by continuously monitoring the driver's condition, detecting signs of fatigue, and issuing alerts to ensure the driver remains alert while driving.

- **Commercial Fleets:** Companies that manage commercial vehicle fleets, such as trucking and delivery services, can deploy this system to protect their drivers and reduce the risk of accidents caused by drowsiness.

- **Public Transportation:** Public transportation services, including buses and trains, can implement the system to ensure the safety of passengers and prevent accidents due to driver fatigue.

- **Ride-Sharing Services:** Ride-sharing and taxi companies can integrate this technology to enhance passenger safety and provide reassurance to riders.

- **Long-Distance Travel:** Vehicles used for long-distance travel, such as tour buses and intercity buses, can benefit from fatigue detection systems to protect both passengers and drivers during extended journeys.



## Contributing

Contributions are always welcome!

See `contributing.md` for ways to get started.

Please adhere to this project's `code of conduct`.

Anyone can contribute to the project by simply tinkering the project to your local machine and adding new features and functionalities and and making it more useful.

## Acknowledgements

 - [Arduino Documentation  ](https://docs.arduino.cc/hardware/uno-rev3 )

 - [ijraset.com](https://www.ijraset.com/research-paper/iot-based-driver-drowsiness-detection-and-smart-alerting-system  )

 - [sciencedirect ](https://www.sciencedirect.com/science/article/abs/pii/S2542660523000288 )

 - [ieeexplore](https://ieeexplore.ieee.org/document/8550026 )

 - [youtube](https://www.youtube.com/watch?v=Ta7I0OB_RWU&ab_channel=RSAIreland   )

 - [kaggle.com](https://www.kaggle.com/code/adinishad/driver-drowsiness-using-keras  )
 


 



## License

[MIT](https://choosealicense.com/licenses/mit/)

