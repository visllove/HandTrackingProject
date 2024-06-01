# Finger Tracking Project

This project demonstrates tracking finger movements using OpenCV and MediaPipe. The project includes two applications:
1. Volume Control Application
2. Mouse Cursor Control Application

Based on lessons from [Computer Vision Zone](https://www.computervision.zone).

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
  - [Volume Control](#volume-control)
  - [Mouse Control](#mouse-control)
- [Hand Tracking Module](#hand-tracking-module)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/visllove/handtrackingproject.git
    cd handtrackingproject
    ```

2. Create and activate a virtual environment:
    ```sh
    python -m venv venv
    .\venv\Scripts\activate  # For Windows
    source venv/bin/activate  # For Unix-based systems
    ```

3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

### Volume Control

To use the volume control application, run the following command:
```sh
python VolumeControl.py
