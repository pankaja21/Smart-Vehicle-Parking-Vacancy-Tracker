Hi! I am Pankaja Biradar!
This is my Mini Project on the Smart Vehicle Parking Vacancy Tracker using AIML.
A smart parking system I mentioned above, that can detect parking spaces in a given image and determined if a given parking space is available or occupied using a camera feed, preferably in real-time consists of two main steps:

1. Find all the parking spaces:
In a given space that the camera covers, it is crucial to know which of the spaces are designated parking spaces. Most of the parking lots specify parking area by drawing white boxes or white lines as shown in the images below. For us, it might be a simple task to identify a parking space, but it is a huge task for a computer to be able to look at those images as say how many parking spaces there are and draw a bod around the parking spaces.

2. Find if a parking space is available or occupied: Once we know which all are parking spaces, we can then proceed to step two which is detecting if a parking space is occupied or is available. As with the above step, it is easy for us to look at a parking space and say if it occupied or not.

My Experiment With Smart Parking
As part of my experimentation project this month, I implemented an AI algorithm that takes in an annotated image and draws a green coloured bounding box around the parking space if it is available and a red coloured bounding box if it is occupied. This included training a deep convolutional neural network to detect if a parking space is occupied or not.

