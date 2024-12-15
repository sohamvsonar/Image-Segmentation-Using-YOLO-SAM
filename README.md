# Image Segmentation using YOLOv11 and SAM v2

This repository contains an advanced image segmentation project that leverages the powerful object detection capabilities of YOLOv11 and the state-of-the-art segmentation capabilities of SAM (Segment Anything Model) v2. The project demonstrates how these models can work together to achieve accurate and efficient image segmentation for a variety of use cases.

## Features

- **Object Detection with YOLOv11**: Utilizes the YOLOv11 model for real-time object detection with high precision.
- **Segmentation with SAM v2**: Applies the Segment Anything Model (SAM) v2 for accurate and flexible segmentation.
- **Pipeline Integration**: Combines the strengths of YOLOv11 and SAM v2 into a seamless image segmentation pipeline.
- **Easy Customization**: Modular codebase for adapting to different datasets and use cases.

## Applications

- Autonomous driving
- Medical image analysis
- Agricultural monitoring
- Industrial inspection
- Any domain requiring precise object segmentation

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/sohamvsonar/Image-Segmentation-Using-YOLO-SAM.git
   cd Image-Segmentation-Using-YOLO-SAM
   ```

2. Install the required dependencies:
   ```bash
   pip install tensorflow pytorch roboflow
   ```


## Usage

### 1. Input Preparation


### 2. Run the Segmentation Pipeline

- Execute the script to perform object detection and segmentation:
  ```bash
  python main.py
  ```

### 3. View Results

- Segmented images will be saved in the `output_images/` directory.
- Visualizations will include bounding boxes (from YOLOv11) and segmentation masks (from SAM v2).

## Project Structure


## How It Works

1. **YOLOv11 Detection**: Detects objects in the input image and generates bounding boxes.
2. **SAM v2 Segmentation**: Extracts segmentation masks for the detected objects using SAM v2.
3. **Output Generation**: Combines detection and segmentation results for visualization.

## Dependencies

- Python 3.8+
- PyTorch 1.12+
- OpenCV
- NumPy
- Matplotlib

See `requirements.txt` for the full list of dependencies.

## Demo

![Segmentation Example](demo/demo_image.png)

## Contributing

Contributions are welcome! Please open an issue or submit a pull request to suggest improvements or report bugs.

## Acknowledgements

- [YOLOv11](#): For object detection capabilities.
- [Segment Anything Model (SAM) v2](#): For segmentation capabilities.

## Contact

For questions or feedback, please contact [sohamvsonar](soham.sonar427@gmail.com).

---

Feel free to fork this repository and adapt it to your own use cases!

