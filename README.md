# Table of Contents

-   detect_video.ipynb: detect videos from your own source
-   evaluate_result.ipynb: evaluate performance of various detection models
-   faster_rcnn.ipynb: use the Faster R-CNN model for detection
-   ssd.ipynb: use the SSH model for detection
-   training.ipynb: train the YOLOv3 model using custom dataset, annotation file and anchor file

# Environment Setup

## Install Anaconda with Python 3.7

<https://www.anaconda.com/distribution/#download-section>

## Setup Conda Environment

```sh
conda env create -f environment.yml
```

## Activate Conda Environment

```sh
conda activate tensorflow
```

## Start Jupyter Notebook

```sh
jupyter notebook
```

# Detect Pedestrians in Videos from own Source

1. Open `detect_video.ipynb` in your browser
2. Change the `video_path` argument in the second cell to the path of your own input video
3. Change the `output_path` argument in the second cell to the desired output path
4. Run all cells

# See report.pdf for result analysis
