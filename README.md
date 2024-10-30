# Flask Video Streaming Application

This is a simple web application that streams live video from a webcam using Flask, OpenCV, and HTML. The application is designed to run on a Raspberry Pi but can also work on other systems with a compatible webcam.

## Features

- Live video streaming through a web browser.
- Easy setup and deployment on a Raspberry Pi or other Linux systems.

## Prerequisites

- **Python 3.x**
- **Flask** and **OpenCV** Python libraries
- **Webcam** connected to your Raspberry Pi or other hardware (e.g., USB camera, Raspberry Pi camera module)


## Usage

1. **Clone the Repository:**

   ```
   git clone https://github.com/yourusername/VideoWebApp.git
   cd VideoWebApp

2. #**Install Required Package:**

Use pip to install the necessary Python libraries.

 ```pip3 install flask opencv-python ``````
 
3. **Run the Flask Python:**

```python3 main.py```

4. **Access the Video Stream:**

Open a web browser and go to:

```http://<raspberry_pi_ip>:5000```


