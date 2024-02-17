# Frame Differencing for Vehicle Detection in Video

This Python script utilizes frame differencing to detect vehicles in a video. It processes each frame by performing frame differencing, thresholding, and contour detection to identify vehicles within the designated detection zone.

## Requirements
- Python 3
- OpenCV (cv2)
- NumPy
- Matplotlib
- Imutils

## How to Use
1. Ensure all required libraries are installed.
2. Place the video file in the same directory as the script or specify the path to the video file.
3. Run the script.

## Code Overview
- **`import` Statements**: Import necessary libraries.
- **Frame Loading**: Load frames from the video.
- **Frame Differencing**: Compute the absolute difference between consecutive frames.
- **Thresholding**: Apply thresholding to create binary images.
- **Image Dilation**: Enhance the binary image using dilation.
- **Contour Detection**: Detect contours in the binary image.
- **Vehicle Detection Zone**: Define the zone for vehicle detection.
- **Contour Filtering**: Filter contours based on size and position.
- **Visualize Results**: Draw contours on frames and display vehicle count.
- **Save Output Frames**: Save frames with detected vehicles.
- **Generate Output Video**: Create a video from the processed frames.