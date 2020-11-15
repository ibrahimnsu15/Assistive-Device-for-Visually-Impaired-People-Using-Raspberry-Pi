# Assistive Device for Visually Impaired People Using Raspberry Pi
Assistive device for visually impaired people can improve mobility as well as the safety of them. This device detects and localizes objects and yellow footway, and recognizes face of the known people. Then the information is sent to the visually impaired people by voice instruction. In addition, this device reads any printed text and converts into speech. Object detection is done by tensorflow object detection API. The yellow footway is detected using color detection in python with OpenCV and Haar feature based cascade classifier method is used for face recognition and human body detection. An OCR (optical character recognition) technology Python-tesseract (pytesseract) extracts text from images and processes the text. Converting all information to speech is done with the help of an offline python text to speech library named pyttsx3. GPS module is constructed in the device and it sends the location to the server and then from the server to the tracker app. This device will assist the blind and partially sighted people in the known and unknown environment without the help of other persons. 

# Development: Getting Started

# Requirement
You will need
* Python3
* Python-tesseract
* Pyttsx3
* Object-detection
* OpenCV

# Component
* Raspberry Pi 3 Model B
* Memory Card
* Raspberry Pi Camera Module
* GPS Module NEO6MV2
* Raspberry Pi Camera Ribbon
* Wearable Glasses
* Power Bank
* Switch

# Instrument Setup and Flow Chart
<p align="center">
  <img src="https://ml-news-files.s3.eu-west-2.amazonaws.com/cap.PNG" width="350" title="hover text">
</p>

<p align="center">
  <img src="https://ml-news-files.s3.eu-west-2.amazonaws.com/cap2.PNG" width="350" title="hover text">
</p>

## Example image
<p align="center">
  <img src="https://ml-news-files.s3.eu-west-2.amazonaws.com/cap3.PNG" width="350" title="hover text">
</p>

# Start App
```bash
$ python3 main.py
```





