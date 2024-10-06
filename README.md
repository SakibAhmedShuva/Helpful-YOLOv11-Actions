# Helpful YOLOv11 Actions

This repository demonstrates helpful actions using YOLOv11. It includes functionality for loading a pre-trained model, performing training, continuing training after an early stoppage, performing inference, updating class labels, etc.

## Overview

This notebook demonstrates how to:
1. Set up the necessary dependencies
2. Load a pre-trained YOLO model
3. Download a custom dataset from Roboflow
4. Train the model on the custom dataset on GPU
5. Continue training the model from the last epoch
6. Export the trained model to ONNX format

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

## Usage

1. Open the notebook in a Jupyter environment
2. Execute the cells in order
3. The trained model will be saved and can be exported to ONNX format

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Ultralytics](https://github.com/ultralytics/ultralytics) for the YOLO implementation

## Contributing

Feel free to open issues or submit pull requests for any improvements.
