# Apple Disease Classification

![Apple Disease Header](path/to/header_image.jpg)

A deep learning project for classifying apple diseases using the Plant Pathology 2021 FGVC8 dataset from Kaggle, implemented in a Jupyter notebook.

## Features

- CNN and EfficientNetB0 models for apple disease classification
- Data augmentation and preprocessing
- Training visualization
- Single image classification tool

## Sample Output

![Sample Classification](path/to/sample_output.png)

## Setup

1. Clone the repo:
   ```
   git clone https://github.com/ishaan-n19/Apple-Disease-.git
   cd Apple-Disease-
   ```

2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Set up Kaggle API:
   - Download `kaggle.json` from your Kaggle account
   - Place it in the `~/.kaggle/` directory
   - Ensure proper permissions: `chmod 600 ~/.kaggle/kaggle.json`

4. Start Jupyter Notebook:
   ```
   jupyter notebook
   ```

5. Open `code.ipynb` in the Jupyter interface

## Usage

1. Run the cells in `code.ipynb` sequentially to:
   - Download and preprocess the apple disease dataset
   - Train the models on apple leaf images
   - Evaluate model performance
   - Generate predictions for apple disease classification

2. To classify a new apple leaf image, use the `upload_and_classify_image()` function provided in the notebook.

## Model Architecture

![Model Architecture](path/to/model_architecture.png)

- Custom CNN tailored for apple disease identification
- Transfer learning with EfficientNetB0, fine-tuned for apple leaf diseases

## Dataset

The project uses the Plant Pathology 2021 FGVC8 dataset from Kaggle, focusing on apple leaf diseases. Here are some sample images from the dataset:

![Dataset Samples](path/to/dataset_samples.jpg)

## Results

Here's a visualization of our model's performance:

![Results Visualization](path/to/results_visualization.png)

## Note

This project is implemented as a Jupyter notebook. Ensure you have Jupyter installed and are familiar with running notebook cells. The focus is on classifying diseases in apple trees using leaf images.
