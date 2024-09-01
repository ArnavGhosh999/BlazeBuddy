<h1 align = "center">WILDFIRE SMOKE DETECTION USING YOLOv8</h1>
<h3>Overview</h3>
This project leverages YOLOv8 (You Only Look Once) for detecting wildfire smoke in images. The model is trained on a custom dataset and can be used to identify smoke in new images.

<h3><b>Table of Contents</b></h3>

- Installation
- Usage
- Training
- Inference
- Results
- License



<h3>Training Configuration</h3>
The model training configuration includes the following parameters:

Data Path: data.yaml (path to the dataset configuration file)
- Epochs: 50
- Image Size: 640
- Batch Size: 16
- Optimizer: Adam
- Learning Rate: 0.001
- Weight Decay: 0.0005


<h3>To set up this project, follow these steps</h3>


1. Clone the Repository

```
git clone https://github.com/yourusername/Wildfire-Smoke-Detection-using-Yolov8.git
cd wildfire-smoke-detection
```

2. Set Up the Environment:

```
pip install ultralytics
```

3. Mount Google Drive (if using Google Colab):
```
from google.colab import drive
drive.mount('/content/drive')
```

