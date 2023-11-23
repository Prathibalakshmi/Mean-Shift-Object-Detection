# Mean-Shift-Object-Detection

Object tracking is one of the most popular areas of video processing. The main purpose of object tracking is to estimate the position of the object in images continuously and reliably against dynamic scenes. This can be achieved by using the mean shift object tracking algorithm. The mean shift algorithm is an efficient approach to tracking objects whose appearance is defined by histograms. Thus, it can be used to track non-rigid objects by discovering clusters in a smooth density of samples.

Question:
Using OpenCV implement a single object tracker. Steps to be implemented: a) Use a pre-recorded video or your webcam to have a video Capture object. b) Mark the region of interest (ROI or the object you want to track) using it coordinates in the first frame. c) Calculate the histogram of the ROI. d) Iteratively calculate the histogram at each location (using cv2,calcBackProject) and then apply mean shift to get the updated location of the ROI

Procedure
- Import Libraries
- Initialize the video captre from either a pre-recorded video or web cam
- Specific video path (Live – streaming path, recorded – log path)
- Creating ROI (Region of Interest)
- Number plate (ROI) – Value
- Create a condition to check whether that input of ROI is visible in the screen which being captured or not.
- Calculate the histogram of ROI
- Perform normalization with respect to CV2
- We need to create a frame start tracking loop to the frame end tracking .
- When the object is about to start, tracking loop must start
- If the object reached the destination, the tracking loop must stop (Terminate)
- Uber (Ride sharing – GPS vehicle. Tracking loop starts from source, terminates when object reaches destination)
