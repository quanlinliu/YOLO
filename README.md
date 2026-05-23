# YOLO Object Detection Notebook

This repository contains a Google Colab notebook for training a YOLO-based object detection model. The notebook focuses on small-object detection and dataset preparation for traffic and transportation-related classes.

## Project Overview

The notebook includes a complete experimental workflow:

- Mounting Google Drive in Colab
- Loading COCO-format annotation files
- Exploring object category distributions
- Merging multiple detection datasets
- Mapping categories into the target label set
- Converting COCO annotations into YOLO label format
- Creating a YOLO `data.yml` configuration file
- Training an Ultralytics YOLO model

## Target Classes

The training configuration uses four classes:

| Class | Description |
| --- | --- |
| `car` | Cars and related vehicle objects |
| `people` | Pedestrians and people |
| `motor` | Motorcycles, bicycles, tricycles, and similar objects |
| `ship` | Ship objects |

## Tech Stack

- Python
- Google Colab
- Jupyter Notebook
- Ultralytics YOLO
- COCO annotation format
- Pandas, NumPy, Matplotlib, Seaborn

## Files

| File | Description |
| --- | --- |
| `main.ipynb` | Main Colab notebook for dataset analysis, conversion, and YOLO training |
| `README.md` | Project documentation |

## How to Use

1. Open `main.ipynb` in Google Colab.
2. Mount Google Drive.
3. Place the dataset and COCO annotation files in the paths expected by the notebook.
4. Install the required packages in Colab.
5. Run the data analysis, conversion, and training cells in order.

## Notes

- Dataset files and trained model weights are not included in this repository.
- API keys should be stored privately and should not be committed to GitHub.
- The notebook uses a placeholder for Roboflow access: `YOUR_ROBOFLOW_API_KEY`.
