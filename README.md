# Video Analysis

## Project Description
This project focuses on implementing and evaluating pedestrian tracking using a combination of the YOLOv5 object detection model and the DeepSORT tracking algorithm. The primary goal is to accurately track pedestrian movement across video frames captured from urban environments.

## Technology Stack
- **Python**: Primary programming language used for implementing the algorithms.
- **OpenCV**: Used for video processing and drawing utilities.
- **PyTorch**: Utilized for running the YOLOv5 object detection model.
- **NumPy**: Employed for data manipulation and processing.
- **Jupyter Notebook**: For interactive code development and evaluation.

## Features
- **Pedestrian Detection**: Implementing YOLOv5 to detect pedestrians in each frame of the video.
- **Tracking**: Applying DeepSORT to track the movement of detected pedestrians across frames.
- **Performance Evaluation**: Calculating metrics such as the Multiple Object Tracking Accuracy (MOTA) to assess the effectiveness of the tracking.

## Repository Structure
```plaintext
.
├── notebooks                  # Jupyter notebooks for demonstration
│   ├── A5.ipynb
├── data                       # Data folder for storing input videos and models
│   └── videos                 # Video files for testing
├── results                    # Output results and analysis
│   ├── output_videos          # Tracked output videos
│   └── performance_metrics.csv # Tracking performance metrics
└── README.md
