# Pose Estimation Video and Webcam with Logging

Hello, In this folder there is a file called **"Pose Estimation Video and Webcam.ipynb"** which is the file that runs the pose estimation application. This .ipynb file marks that this is a Python Notebook file and the code is ran cells, or snippets of code. 

## Prerequisites 
To run this program make sure you have Python installed on your computer. You can download Python from this link https://www.python.org/downloads/ or look it up. It is also recommended that you use Visual Studio Code to open and run this file. Here is the link https://code.visualstudio.com/. Once these are download you will also need to download a few Python libraries. To do so open "Terminal" or "Command Prompt" on Windows and enter this line **pip install opencv-python** then press enter to begin the installation. Then do the same for this line and put  **pip install matplotlib** in your Terminal or Command Prompt and press enter. 


## Opening the file

To open and run the code, first open your Visual Studio Code app. Then open the Pose Estimation Video and Webcam.ipynb in Visual Studio Code. This can be done by using the shortcut prompted on the homepage to open a file or you can drag the file into the app. 

## Run the code

To run the code you will run the code in each **"cell"** or snippet of code. On the top right corner of each of these cells there is a play button to run the code in each of these cells. Make sure that you select your Python version you downloaded to run your code. Continue to press the play button on the each of the cells to get an output and keep scrolling through the file. Make sure to run the cells one after the other, sequentially. (If you only want to test video or webcam, you can skip running those code cells).

## Video

While running the cells you will eventually get to a section that says "Perform this demo on video" After running the code you will see a video with points and lines on a human body. Make sure the video file named **"Screen Recording Sample"** is in the same directory as the "Pose Estimation Video and Webcam.ipynb" file and it is in a mp4 format.

## Webcam

At the end of the file you can run the pose estimation with a webcam that will give you real-time feedback. On the top left corner there is a timer for how long the application has been running, and below that is all the joints that are detected in the webcam, the frame they are in, and the coordinates of the joints. This information is also stored in **"joint_coordinates_log.txt"** which is created upon running this code and can be located in the same directory as the "Pose Estimation Video and Webcam.ipynb" file. This text file is created and has new data inserted into it every time it is ran. If you want to save the information from a specific webcam session you can duplicate the file by right clicking and select Copy and paste or right click and press Duplicate. 

## Webcam Examples 
I have already tested the real-time webcam and its logging capabilities, which you can see in the same folder this README is located in. There are 2 recordings of the webcam being used titled, **"Webcam - Front Facing.mp4**" and the other **"Webcam - Side Angle.mp4**". There are also 2 text files called **"Front Facing joint_coordinates_log.txt**" and **"Side Angle joint_coordinates_log.txt**" where all the information from webcam is being logged.  (Note: When you run this program it will create a file named joint_coordinate_log.txt as stated above and this will not override any data from the other file.). These videos show how the program looks when everything is running and what to expect. 

### If you have any questions please feel free to contact me at omar.jamjoum@sjsu.edu
### Thank you

	

#
#### Resources used
https://www.youtube.com/watch?v=9jQGsUidKHs&ab_channel=DeepLearning_by_PhDScholar

https://github.com/quanhua92/human-pose-estimation-opencv

https://github.com/opencv/opencv/blob/master/samples/dnn/openpose.py
