# CARLA Autonomous Driving Dataset Pipeline

Python-based data collection pipeline for generating autonomous driving datasets using the CARLA Simulator.

## Overview

This project collects synchronized multi-sensor data from CARLA, including RGB camera, depth camera, semantic segmentation, and LiDAR. The pipeline is designed to support autonomous driving research and model development using dashcam and Bird's Eye View perspectives.

## Features

- Collects RGB, depth, semantic segmentation, and LiDAR data
- Supports synchronized multi-sensor data collection
- Captures dashcam and Bird's Eye View perspectives
- Structures raw simulation outputs into reusable autonomous driving datasets

## Tech Stack

- Python
- CARLA Simulator
- NumPy
- OpenCV
- Jupyter Notebook

## Repository Structure

carla-autonomous-driving-dataset-pipeline/
├── notebooks/
│   └── carla_dataset_collection_pipeline.ipynb
├── README.md
├── requirements.txt
└── .gitignore

## How to Run

1. Clone this repository.

git clone https://github.com/aikathalita/carla-autonomous-driving-dataset-pipeline.git

2. Move into the project directory.

cd carla-autonomous-driving-dataset-pipeline

3. Install dependencies.

pip install -r requirements.txt

4. Run the notebook.

jupyter notebook notebooks/carla_dataset_collection_pipeline.ipynb

5. Make sure the CARLA Simulator server is running before executing the notebook.

## Notes

Large generated datasets, images, videos, and sensor outputs are excluded from this repository using .gitignore.

This repository focuses on the data collection pipeline and implementation notebook.

## Author

Thalita Aika Rahmani