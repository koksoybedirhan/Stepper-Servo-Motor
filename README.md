Commands 1,2(steering) and 3(brake) sent randomly from Arduino Uno are received from another Arduino Uno. A4988 Stepper Motor Driver is connected to Arduino Uno which reads random codes and the connected Stepper Motor Driver US-17HS4401 drives the Stepper Motor. In addition, the interrupt process is applied by serial communication and pin activation from another Arduino connected to the Servo Motor, and when the brake is pressed while the steering wheel is turning, the brake command is given priority and the steering wheel turns passive until the brake switches to the self-collection process.


Visual state of the system:
![Stepper-Servo-Motors](https://user-images.githubusercontent.com/71734713/155784021-897471b3-cc98-4016-9451-d003ecefb80a.jpeg)
