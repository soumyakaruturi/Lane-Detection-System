
# Lane Detection Prediction System

A Python-based computer vision project for detecting lane lines in images and video streams using OpenCV.  
Designed to assist autonomous and ADAS systems, it leverages color masks, edge detection, perspective transforms, and curve fitting to accurately identify and highlight road lanes.
With modular functions and a straightforward pipeline, it is ideal for educational purposes or as a foundation for advanced self-driving applications.

## Features

- **Accurate Lane Detection:** Identifies lane boundaries on straight and curved roads in real time.
- **Image and Video Support:** Processes both static images and video frames.
- **OpenCV Pipeline:** Implements color masks, Canny edge detection, Hough Transform, and perspective warping for lane identification.
- **Modular Design:** Organized code for easy extension or integration into larger systems.

## Technologies Used

- Python 3
- OpenCV (opencv-python)
- NumPy

## Getting Started

### Prerequisites

- Python 3.6 or higher
- OpenCV and NumPy libraries:
  ```
  pip install opencv-python numpy
  ```

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/soumyakaruturi/Lane-Detection-System.git
   ```
2. Navigate into the project directory:
   ```
   cd Lane-Detection-System
   ```
3. Run the main lane detection script:
   ```
   python lane_detection.py
   ```
   - Adjust script names as needed.

## Usage

- Place sample road images and/or videos inside the designated folder.
- Run the script; lane lines will be marked and output saved/displayed.
- Tweak parameters for specific environments or camera perspectives.

## Contributing

Pull requests are welcome!  
- Fork the repository, create your branch, and open a pull request to contribute improvements or new features.
