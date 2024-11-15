# Sahil-Gorde_AI-Enhanced-Engagement-Tracker-for-Young-Learners_-Infosys_Internship_Oct2024
## Image Processing
### Libraries or Frameworks Used
- **OpenCV**: Version 4.10.0.84
- **NumPy**: For array manipulation

### Developed Logics

#### A) Image Concatenation
Resizes two images to a specified pixel range and merges them both horizontally and vertically, displaying the results in separate windows.
- **Input**:
- <img src="https://github.com/user-attachments/assets/488a9a57-3ead-4da9-ac7a-c586b4f9d6a9" alt="concat" width="400">
- <img src="https://github.com/user-attachments/assets/7a649422-b004-493b-b602-5333a2cf9d21" alt="concat" width="400">

- **Output**:
-  <img src="https://github.com/user-attachments/assets/1499a03e-3496-447c-95eb-cb59248586d3" alt="concat" width="400">


#### B) Image Contour Detection
Identifies contours in a grayscale image using a binary threshold and `cv2.findContours()`. Draws these contours on the original image in green.
- **Input**:
- **Output**:

#### C) Image Cropping
Extracts and displays a defined region of an image based on specified pixel coordinates.
- **Input**:
- **Output**:

#### D) Image Dilation & Erosion
Performs morphological operations to enlarge and shrink image features, enhancing and reducing specific areas respectively.
- **Input**:
- **Output**:

#### E) Edge Detection
Uses the Canny edge detection algorithm to highlight edges within a grayscale image.
- **Input**:
- **Output**:

#### F) Histogram Equalization
Improves the contrast of a grayscale image through histogram equalization.
- **Input**:
- **Output**:

#### G) HSV Conversion
Converts a color image from the BGR format to the HSV color space.
- **Input**:
- **Output**:

#### H) Morphological Transformations
Applies opening and closing operations on a grayscale image to minimize noise and fill small gaps.
- **Input**:
- **Output**:

#### I) Image Resizing
Adjusts the dimensions of an image according to specified width and height.
- **Input**:
- **Output**:

#### J) RGB to Grayscale Conversion
Transforms a color image to a grayscale representation.
- **Input**:
- **Output**:

#### K) Image Rotation
Rotates an image 90 degrees around its center point.
- **Input**:
- **Output**:

#### L) Image Blurring
Applies a Gaussian blur to an image to reduce noise and soften details.
- **Input**:
- **Output**:

#### M) Noise Removal & Gap Closing
Removes noise and closes gaps in an image using morphological operations.
- **Input**:
- **Output**:

## Video Processing Project Overview

### Libraries and Frameworks Utilized
- **OpenCV**: Version 4.10.0.84 

### Developed Functionalities

#### A) Video_multivideo
Reads and showcases images from a given directory, printing the dimensions of each image to the console for batch image analysis.
- **Input**:
- **Output**:

#### B) Video_fps
A real-time video capture function that displays a live video feed while calculating and showing the frames per second (FPS) for performance monitoring.
- **Input**:
- **Output**:

#### C) Video_save
Captures live video from the webcam and writes it to a specified output file, allowing easy recording and saving of video content.
- **Input**:
- **Output**:

#### D) Video_stack
Reads two separate video files, resizes them, and combines them side by side for synchronized dual-video playback, ideal for comparing footage.
- **Input**:
- **Output**:

#### E) Video_stream
Captures and streams live video feed from the webcam, displaying it in real-time. Useful for basic video streaming applications.
- **Input**:
- **Output**:

## Annotations Project Overview

### Libraries and Frameworks Utilized
- **OpenCV**: Version 4.10.0.84 for advanced image processing
- **LabelImg**: Version 1.8.6 for image annotation

### Developed Functionalities

#### A) data_segregate
Organizes images and label files into separate directories for matched and unmatched pairs, aiding in dataset preparation for ML projects.
- **Input**:
- **Output**:

#### B) label
Draws bounding boxes on images based on annotation data, useful for visualizing object detection outcomes.
- **Input**:
- **Output**:

#### C) label_manipulate
Updates class numbers within label files, enabling easy reclassification in object detection tasks.
- **Input**:
- **Output**:

## Face Recognition Project

### Libraries or Frameworks Used
- **OpenCV**: Version 4.10.0.84
- **LabelImg**: Version 1.8.6
- **dlib**: Version 19.24.6
- **face_recognition**: Version 1.3.0
- **imutils**: Version 0.5.4

### Developed Logics

#### A) Face_recognition
#### B) Attendence_save
#### C) test
#### D) tools
#### E) excel_sc
#### F) excel_sc_dt
#### G) landmark
#### H) atten_score
#### I) avg_atten_score

