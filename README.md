# Motion Sensing using OpenCV

This Python script captures live video from the webcam and detects motion using OpenCV. When motion is detected, an alarm is triggered, and you can toggle the motion-sensing mode by pressing "t". The script allows you to activate and deactivate motion sensing based on your needs.

## Prerequisites

- Python 3
- OpenCV library (`cv2`)
- Imutils library (`imutils`)

## Installation

1. Clone this repository:

   ```sh
   git clone https://github.com/malto101/Motion_dectection.git
   ```
## Usage
1. Run the script:

   ```sh
   python script.py
   ```
   
2. Press "t" to toggle motion sensing mode.

3. Press "q" to exit the script.

## Script Details

- The script uses the OpenCV library to capture live video from the webcam.
- It detects motion by calculating the difference between consecutive frames.
- The script allows you to activate and deactivate the motion sensing mode using the "t" key.
- An alarm is triggered and printed to the console when motion is detected.

## Notes
- Make sure your webcam is connected and accessible by the script.
- Customize the script to adjust motion detection sensitivity and alarm behavior.
- The script assumes basic familiarity with Python and OpenCV.

