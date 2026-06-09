# Channel Attention on YOLO-v9

A Kaggle-style project for converting Pascal VOC annotations into YOLO format and preparing data for training YOLO-v9 with channel attention improvements.

## Project Overview

This repository contains the notebook used to:
- Download Pascal VOC 2007 and 2012 datasets
- Convert VOC XML annotations into YOLO `.txt` label files
- Create YOLO dataset configuration files
- Clone and install YOLO-v9 dependencies
- Prepare the dataset for model training and visualization

## Repository Contents

- `notebook2959095597.ipynb` - Main notebook with the full data preparation and YOLO-v9 setup workflow
- `README.md` - Project documentation
- `screenshots/` - Result images and visualizations
- `YOLO v9.mp4` - Side-by-side prediction video showing YOLOv9 and YOLOv9 with channel attention
- `.git/` - Git repository metadata

## Key Steps

1. Download Pascal VOC 2007 and 2012 archives
2. Extract VOC dataset files
3. Convert VOC annotations to YOLO format
4. Save class names and dataset YAML configuration
5. Verify generated YOLO label files
6. Clone YOLO-v9 repository and install required packages
7. Optionally visualize label bounding boxes on example images

## How to Use

1. Open `channel-attention-on-yolo-v9.ipynb` in Jupyter, VS Code, or Kaggle Notebook.
2. Run the notebook cells in order.
3. Confirm that YOLO label files are created under `yolo_labels/VOC2007` and `yolo_labels/VOC2012`.
4. Use the generated `data.yaml` to train YOLO-v9 on the prepared dataset.

## Expected Output

- YOLO label files with normalized coordinates, one `.txt` annotation file per image
- `classes.txt` containing the 20 Pascal VOC class names
- `data.yaml` with paths to training and validation images
- Visualized image examples showing bounding boxes over detected objects

## Results

> Add your project results and metrics here once available.

Example fields to include:
- Training accuracy / mAP
- Loss curves
- Validation precision and recall
- Inference sample images

## Media Files

This repository includes result images and a comparison video for the YOLOv9 experiments.

### Screenshot files

- `screenshots/data-preparation.png`
- `screenshots/detection-sample-1.png`
- `screenshots/detection-sample-2.png`
- `screenshots/detection-sample-3.png`
- `screenshots/detection-sample-4.png`
- `screenshots/confusion-matrix.png`
- `screenshots/pr-curve.png`

### Video file

- `YOLO v9.mp4` — side-by-side prediction comparison of YOLOv9 and YOLOv9 with channel attention.

### Displayed media

![Data preparation](screenshots/data-preparation.png)

![Detection sample 1](screenshots/detection-sample-1.png)

![Detection sample 2](screenshots/detection-sample-2.png)

![Detection sample 3](screenshots/detection-sample-3.png)

![Detection sample 4](screenshots/detection-sample-4.png)

![Confusion Matrix](screenshots/confusion-matrix.png)

![Precision-Recall Curve](screenshots/pr-curve.png)

> Place your screenshot files inside the `screenshots/` folder and use the video player in GitHub to view `YOLO v9.mp4`.

## Notes

- This repository is primarily a data preparation and YOLO-v9 setup proof of concept.
- If you want, I can also help update this README later with the actual screenshot files and final result descriptions.
