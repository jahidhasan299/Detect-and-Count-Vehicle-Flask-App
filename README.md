# Detect-and-Count-Vehicle-Flask-App
# Step to run application:
1. Step 1: Create the copy of the project. 
2. Step 2: Open command prompt and change your current path to folder where you can find 'app.py' file. 
3. Step 3: Create environment by command given below- conda create -name 
4. Step 4: Activate environment by command as follows- conda activate 
5. Step 5: Use command below to install required dependencies- python -m pip install -r requirements.txt 
6. Step 6: Run application by command; python app.py You will get url copy it and paste in browser. 
7. Step 7: You have sample_data folder where you can get images to test.

# THE STEPS ARE TAKEN TO COMPLETE THIS PROBLEM
1. Loading the image from the internet.
2. Resizing the image and convert it into a numpy array.
3. Converting image into greyscale.
4. Load the xml file which contains the haar cascade.
5. Using haar cascade to detect the vehicle on the image.
6. Use the contours to create a rectangle around all the detected vechicles(Cars)
7. Similarly we will perform these operations for another image for bus detection.
8. Will us bus_detection xml for bus detection.
9. We will aslo perform these operations on a video.
10. Save the video with object detection.

# Vehicle Detect-Count
1. In this project, we will be working on detecting and counting vehicles in a given image or a video. We will be using OpenCV for image processing and Haar cascade which is used for object detection. We can also create our own customized haar cascade classifier.
2. As haar cascase is used for object detection we have a very vast scope for this project. It can be used for any type of object detection. we can also create our own custom haar cascade for specific objects.
3. With this kind of indentification and localization, object detection can be used to count objects in a scene and determine and track their precise locations, all while accurately labeling them.

# Scope:
As haar cascade is used for object detection we have a very vast scope for this project. It can be used for any type of object detection. We can also create our own custom haar cascade for specific object.
