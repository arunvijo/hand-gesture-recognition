# Hand gesture recognition in Python using OpenCV      
This guide will teach you how to code a computer vision program that recognizes simple hand gestures:

+ Waving
- Pointing (one finger extended)
+ Scissors (two fingers extended)
* Rock (no fingers extended)

# Objectives
+ Objective 0: Get acquainted and plan ahead
- Objective 1: Write the base for the program
  - Step 1a: Import libraries and create global variables
  - Step 1b: Write a loop to get camera input
  - Step 1c: Set up variables for image analysis
+ Objective 2: Create tools for hand data and screen writing
  - Step 2a: Create an object class to hold hand data
  - Step 2b: Create a function that writes hand data on the screen
- Objective 3: Recognize when a hand is in the region of interest
  - Step 3a: Get the background ready for averaging
  - Step 3b: Average the first CALIBRATION_TIME background frames
  - Step 3c: Use differencing to isolate a hand from the background
+ Objective 4: Recognize when the user waves
  - Step 4a: Program the system to get the hand's center point
  - Step 4b: Create a function for handData to check for waving
+ Objective 5: Count fingers
  - Step 5a: Create a function to count fingers crudely
  - Step 5b: Create a list of gestures to choose the most frequent one

 # Screenshots 
![Screenshot 2024-05-30 080818](https://github.com/arunvijo04/hand-gesture-recognition/assets/108383137/ced0b5c2-9ac8-41c1-b9e5-4ff6be3b630c)
