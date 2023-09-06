# Brain-Tumour-Segmentation

## Overview

This Jupyter Notebook demonstrates the process of building, training, and evaluating tumor segmentation models using the BRATS Decathlon dataset and the MONAI (Medical Open Network for AI) framework. I utilize both custom-trained and pre-trained models from the MONAI model zoo and employ itkwidgets for insightful visualization of segmentation results.

## Dataset

The BRATS (Brain Tumor Segmentation) Decathlon dataset is a widely used benchmark dataset for brain tumor segmentation. You can download the dataset from the following link: [BRATS Decathlon Dataset](https://decathlon-10.grand-challenge.org/). We will also download the dataset whithin the notebook



## Requirements

To run this Jupyter Notebook, you'll need the following dependencies:

- Python 3.x
- Jupyter Notebook
- MONAI framework (Install via `pip install monai`)
- PyTorch (Install via `pip install torch`)
- itkwidgets (Install via `pip install itkwidgets`)
- Other dependencies specified in the Jupyter notebook

You can install the additional dependencies by running the corresponding cells in the notebook.

## Training

The Jupyter notebook provides a step-by-step guide to training your tumor segmentation model. Key steps include:

1. Data preprocessing and loading the BRATS dataset.
2. Defining and training your custom segmentation model.
3. Evaluating the model performance

## Loading Models from the MONAI Model Zoo

The MONAI model zoo provides a collection of pre-trained models specifically designed for medical image analysis. In the notebook, you will find examples of how to:

- Load a pre-trained model from the MONAI model zoo.
- Utilize the pre-trained model for tumor segmentation.

## Visualizing Results

To gain insights into your model's performance, the notebook includes sections for visualizing segmentation results. It demonstrates how to:

- Visualize segmented tumor regions using itkwidgets.


## Usage

Here's how to use this Jupyter Notebook:

1. Clone or download the repository to your local machine:

```bash
git clone https://github.com/your-username/tumor-segmentation.git
cd tumor-segmentation
