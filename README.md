# Social-Distance-Monitoring
Developed a real-time social distancing system with YOLOv3 for human detection, OpenCV for video processing, and Perspective transformation for bird's-eye view. Used Euclidean distance for accurate distance measurement, categorizing individuals into high, low, and no-risk groups for monitoring in public areas and workplaces.

   This tool has following features:

   * Detect humans in the frame with yolov3/ssd.
   * Calculates the distance between every human who is detected in the frame.
   * Shows how many people are at High, Low and Not at risk.

## Setup process

Install the following model files:

```
yolov3.cfg (create a folder named models inside the YOLO folder and save this file inside it)
yolov3.weights (create a folder named models inside the YOLO folder and save this file inside it)
SSD_MobileNet_prototxt.txt (save inside SSD folder)
SSD_MobileNet.caffemodel (save inside SSD folder)
```


## Running process

Run the below command:

```
streamlit run app.py
```