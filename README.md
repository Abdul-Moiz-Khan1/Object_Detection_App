
#  Object Detection Android App

A real-time object detection app built with Kotlin, Camera2 API, and google ml kit.it detects objects from a live camera feed and draws bounding boxes with labels and confidence scores.

## Description

A real-time object detection app built using Kotlin, Camera2 API, and TensorFlow Lite. It uses google ml kit object detection model to detect and classify objects from the live camera feed, drawing bounding boxes with labels and confidence scores. The app is lightweight, fast, and works entirely on-device,no internet required.
        
## Technologies Used

    1. Kotlin 
    2. Camera2 API
    3. TensorFlow Lite
    4. MVVM principles
    5. Google ML kit

## Working

1. Camera Initialization

        a. The app uses Android’s Camera2 API to access the rear camera.
        b. Live camera feed is displayed using a TextureView.

2. Frame Processing

        a. Each frame from the camera is captured in real-time.
        b. The current frame (Bitmap) is passed to Google ML Kit’s Object Detection model.

3. Object Detection

        a. ML Kit analyzes the image and detects multiple objects.
        b. It returns:
        c. Object bounding box coordinates
        d. Object category label (e.g., "cat", "person")
        e. Confidence score
        f. Drawing Results
        g. The app creates a mutable copy of the frame.

4. For each detected object:

        a. A bounding box is drawn using Canvas and Paint.
        b. Label and confidence score are rendered inside or near the box.

Display Output

    a. The annotated image is shown on an ImageView (image1), overlaying results over the live feed. 

Performance

    a. The app runs entirely on-device (no internet required).
    b. Efficient real-time performance even on mid-range devices

## Screenshots

<img width="250" height="500" alt="objectDetection1" src="https://github.com/user-attachments/assets/5c82b012-a2f2-4cb5-a731-15878c60eb45" />

<img width="250" height="500" alt="objectDetection2" src="https://github.com/user-attachments/assets/7a25c158-883e-40df-8f1a-f7eb95b7cc88" />
<img width="250" height="500" alt="objectDetection3" src="https://github.com/user-attachments/assets/935f4ca4-fedf-42ed-b61a-0a0c8242d74a" />
<img width="250" height="500" alt="objectDetection4" src="https://github.com/user-attachments/assets/52311ad5-b9fe-4ca6-8608-275bf530ce9a" />




    




