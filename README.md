# YOLOv11 Training

This repository contains a Jupyter notebook for training with YOLOv11

## Overview

This notebook demonstrates how to:
1. Set up the necessary dependencies
2. Load a pre-trained YOLO model
3. Download a custom dataset from Roboflow
4. Train the model on the custom dataset
5. Export the trained model to ONNX format

## Prerequisites

- Python 3.10 or later
- Jupyter Notebook environment / Kaggle / Google Colab
- GPU support (recommended for training)

## Installation

Install the required packages:

```bash
pip install ultralytics
pip install roboflow
pip install -U ipywidgets
```

## Dataset

The notebook uses a custom dataset from Roboflow. The dataset is automatically downloaded using the Roboflow API during execution.

## Model

The base model used is `yolo11x-seg.pt`, which is then fine-tuned on the custom flower dataset.

## Training

The model is trained with the following parameters:
- Epochs: 600
- Image size: 640x640
- Batch size: 4
- Workers: 4
- Random seed: 101

## Usage

1. Open the notebook in a Jupyter environment
2. Execute the cells in order
3. The trained model will be saved and can be exported to ONNX format

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Ultralytics](https://github.com/ultralytics/ultralytics) for the YOLO implementation
- [Roboflow](https://roboflow.com/) for dataset management

## Contributing

Feel free to open issues or submit pull requests for any improvements.

---

⭐ Star this repository if you find it helpful!

