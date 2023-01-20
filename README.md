ACES, 2nd year

IoT project

Bear Detection System

### Description
The purpose of this project is to detect the presence of bears in areas populated by humans and notify one or more people. In order to achieve this an ultrasonic sensor will measure periodically the distance to the nearest object. If the distance is small enough, it means something came in front of the sensor and a camera will take a photo of it. Afterwards, a neural network will analyze if in the photo there is a bear of not. If there is a bear, the photo of the bear will be uploaded via WiFi on a Firebase server and emailed to one ore more people.

### Results
Overall the implementation of the system is not done. I made the neural network for detecting bears, and put it on the ESP32-CAM. The ultrasonic sensor also works well. The problems I am currently facing are connecting to the Firebase and to the SMTP server. I was able to connect to Firebase with the current ESP32-CAM and upload images unitil recently, as can be seen in the image from chapter 3.2. One challenge I encountered on working on this project were the faulty ESP32-CAMs (one arrived broken and 2 became broken after a few hours of usage). As I can't see exactly the images taken is also hard to adapt the neural network for correct inference on the board.
