# Action Recognition with OpenVINO

This repository contains code and resources for building an action recognition system using TensorFlow, MoViNet, and OpenVINO.

## Project Structure
- [**1-data-preparation/**](1-data-preparation)
  - **Description:** Scripts for recording and annotating video data.
  - **Requirements:** Python 3.x

- [**2-action-recognition-training/**](2-action-recognition-training)
  - **Description:** Training scripts for action recognition using MoViNet-Stream architecture.
  - **Requirements:** Docker (Ubuntu + TensorFlow 2.9.0) + devices with GPU

- [**3-model-conversion-openvino/**](3-model-conversion-openvino)
  - **Description:** Scripts for converting MoViNet-Stream models to OpenVINO format.
  - **Requirements:** Python 3.x + OpenVINO Python API
    
- [**4-edge-inference/**](4-edge-inference)
  - **Description:** C++ code for running models on Intel CPU/iGPU using OpenVINO.
  - **Requirements:** C++ compiler + OpenVINO C++ API
    
- [**5-view-app/**](5-view-app)
  - **Description:** A simple C# application for displaying results and LED control.
  - **Requirements:** .NET runtime
    
## Performance Test

<img src="performance.jpeg" style="width:700px;">
