# Smart-Home-Security-Using-Arduino
This Repository Contains Files of Electronics Module: Arduino Programming, and Machine Learning Module: Facial Recognition, Part of Project: "Smart Home Security System"

## Project Description
     ### Problem Statement - Smart Home Security System
1. Develop a smart home security system with the following functionalities:
2. Motion Detection: A sensor detects motion in front of the door.
3. Camera Activation: The motion detection triggers a camera to take a picture.
4. Person Recognition:
    a. If no person is detected, no further action is taken.
    b. If a person is detected and matches the database of household members, the door opens.
    c. If the person is not recognized, the doorbell rings.
5. User Feedback: A display at the front door informs the person whether they are recognized or not.

## Modules
### Electronics Module
This module is developed using Arduino in TinkerCad and includes various components to achieve the functionalities described above. Here is a brief overview of the process:

  a. Motion Detection: A PIR sensor detects motion in front of the door.
  b. Camera Activation: When motion is detected, the camera takes a picture of the person standing at the door.
  c. Person Recognition: The system then checks the captured image against a database of known faces.
If the person is recognized, the system shows a green light and opens the door.
If the person is not recognized, a red light is displayed, and a buzzer rings to alert the household members.

#### Files in this Module
   - bom.csv: Bill of materials listing all the components used.
   - smart_home_security_arduino.png: Image of the actual model created in TinkerCad.
   - smart_home_security_block_diagram.pdf: Block diagram of the system.
   - smart_home_security_model.brd: Board layout of the electronic components.

### Machine Learning Module - Person Recognition
This module utilizes a machine learning approach to recognize faces. The process is as follows:

A database of household members is maintained, with folders for each person containing their images.
When the camera captures an image of the person at the door, the system scans the face.
If the face matches a person in the database, the system greets the person and opens the door.
If the face does not match anyone in the database, the doorbell rings to notify the household members.

## Integration
In a real-world scenario, both modules are integrated seamlessly:
  1. The camera in the electronics module works in conjunction with the person recognition code.
  2. If the person is recognized, the system shows a green light, greets the person, and opens the door.
  3. If the person is not recognized, a red light is displayed, and the doorbell rings.

# Conclusion
This smart home security system combines Arduino-based hardware with machine learning-based facial recognition to create an efficient and secure entry system. The project demonstrates the potential of integrating electronics and AI to enhance home security.
