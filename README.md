# Object Detection and Distance Measurement with Point Cloud Integration

## Project Description
This project implements a real-time object detection system for live traffic analysis. The system utilizes the YOLO (You Only Look Once) model to detect vehicles, pedestrians, and traffic signs from video feeds. Additionally, it integrates point cloud data from LiDAR sensors with YOLO's detection output, allowing precise distance measurement and spatial positioning of objects in dynamic traffic environments.

## Features
- **Real-time Object Detection**: Detect vehicles, pedestrians, and traffic signs from video using the YOLO algorithm.
- **LiDAR Integration**: Integrate LiDAR point cloud data to accurately measure distances and provide the spatial positioning of detected objects.
- **Dynamic Traffic Environment**: Works efficiently in real-time traffic conditions, handling changing objects and positions.

## Technologies
- **Python**: Programming language used for implementing the system.
- **Machine Learning**: YOLO model for object detection.
- **Computer Vision**: OpenCV for processing video feeds and object recognition.
- **SQL**: For storing traffic-related data, object information, and analysis results.
- **LiDAR (Point Cloud Data)**: Integrates 3D data for distance measurement and positioning.

## Installation Instructions
To set up the project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/object-detection-lidar.git
   cd object-detection-lidar
   ```

2. **Install required dependencies**:
   Make sure you have Python 3.x installed, then create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   pip install -r requirements.txt
   ```

3. **Setup LiDAR and Camera**: 
   - Connect the LiDAR sensor and ensure it's providing point cloud data.
   - Configure your camera for real-time video feed (make sure the YOLO model can access it).

4. **Run the system**:
   ```bash
   python main.py
   ```

## Usage
1. **Start the system**: Once the system is running, it will start processing the video feed and integrating the LiDAR data.
2. **Detect Objects**: The system will detect vehicles, pedestrians, and traffic signs in the video feed.
3. **Measure Distance**: Using the LiDAR data, it will also output the distance and spatial positioning of each detected object.
4. **View Results**: The output (detected objects with distances) will be shown on the screen or saved to a database, depending on your configuration.

## Acknowledgements
- **YOLO (You Only Look Once)**: For object detection.
- **LiDAR**: For accurate distance measurement and 3D mapping.
- **OpenCV**: For video processing and computer vision.

## Watch the Demo
Check out the demo of the object detection and distance measurement system:

[Download and Watch the Video](https://github.com/Farhin-saiyed/Object-Detection-and-Distance-measurement
/output.mp4)
