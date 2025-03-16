# Greeting Robot for Events

![Robot Image 1](images/1.jpg)

## Overview

The Greeting Robot for Events is designed to enhance guest experiences by providing personalized greetings at various events. Utilizing facial recognition technology, the robot identifies attendees and delivers customized messages, making each interaction unique.

## Features

- **Facial Recognition**: Accurately identifies guests using pre-trained models.
- **Personalized Greetings**: Delivers tailored messages based on recognized individuals.
- **Event Adaptability**: Suitable for various events such as conferences, weddings, and corporate functions.

## Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/muhammedfayiz122/Greeting-Robot-for-events.git
   ```

2. **Navigate to the Project Directory**:

   ```bash
   cd Greeting-Robot-for-events
   ```

3. **Download Training and Testing Data**:

   Download the train and test data from [this link](https://drive.google.com/file/d/1C_FsSPhjMcGhJOHwRSURyYACwwX7xAZM/view?usp=sharing) and place the contents in the project's root directory.

4. **Install Dependencies**:

   Ensure you have Python installed. Install the required packages using:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **With Hardware**:

   To run the robot with connected hardware components:

   ```bash
   python main.py
   ```

2. **Without Hardware**:

   For simulation purposes without hardware:

   ```bash
   python without_hardware.py
   ```

## Directory Structure

```
Greeting-Robot-for-events/
├── haarcascades/         # Contains Haar Cascade classifiers for face detection
├── images/               # Directory for storing images (e.g., 1.jpg, 2.jpg, 3.jpg)
├── model/                # Pre-trained models for facial recognition
├── main.py               # Main script for running the robot with hardware
├── without_hardware.py   # Script for running the robot without hardware
└── README.md             # Project documentation
```

## Images

![Robot Image 2](images/2.jpg)

![Robot Image 3](images/3.jpg)

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Acknowledgements

Special thanks to the open-source community for providing tools and libraries that made this project possible.
