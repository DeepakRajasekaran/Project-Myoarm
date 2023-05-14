# Project-Myoarm
An robotic arm that works using EMG signals
Control the InMoov robotic arm using Arduino and servo motors.

## Description

This project allows you to control the movements of an InMoov robotic arm using an Arduino board and servo motors. By manipulating the servo motors connected to each finger, you can open and close the hand and perform various gestures. The arm movements are triggered by the input from a muscle sensor connected to the Arduino board.

## Features

- Open and close the hand of the InMoov arm.
- Control individual finger movements.
- Use a muscle sensor to detect hand gestures.
- Adjustable threshold for hand open/close detection.

## Installation

1. Clone the repository to your local machine.
2. Connect the servo motors and muscle sensor to the appropriate pins on the Arduino board.
3. Upload the Arduino sketch (`EMG_read.ino`) to your Arduino board.
4. Run the Arduino sketch to start controlling the InMoov arm.

## Usage

1. Ensure that all the connections are properly set up.
2. Open the Arduino IDE and upload the sketch to your Arduino board.
3. Open the Serial Monitor to view the sensor values and adjust the threshold if needed.
4. Perform hand gestures to control the InMoov arm.
5. Refer to the Arduino sketch for customization and advanced usage.

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or improvements, feel free to open an issue or submit a [pull request](https://github.com/DeepakRajasekaran/Project-Myoarm/compare).

## License

This project is licensed under the MIT License. See the [LICENSE-MIT](LICENSE-MIT) for more details.

## Acknowledgements

- The InMoov project: [https://inmoov.fr/](https://inmoov.fr/)
- Arduino: [https://www.arduino.cc/](https://www.arduino.cc/)
- Servo Library: [https://www.arduino.cc/en/Reference/Servo](https://www.arduino.cc/en/Reference/Servo)
