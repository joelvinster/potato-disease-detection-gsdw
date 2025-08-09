# potato-disease-detection-gsdw
Potato Disease Detection using GDSW + DenseNet169
This repository contains my research notebook on potato leaf disease classification using a custom Grouped Depthwise Separable Convolution (GDSW) layer in conjunction with a DenseNet169 backbone.
The model is designed to detect and classify various diseases affecting potato leaves, leveraging the power of deep learning and computer vision.

Table of Contents
Project Overview

Notebook

Requirements

How to Run

Results

Dataset

Usage

Citation

License

Project Overview
Plant diseases, if left undetected, can cause significant crop loss. This project focuses on detecting diseases in potato leaves using a hybrid deep learning architecture that incorporates a GDSW layer and DenseNet169 for enhanced accuracy and efficiency.

Notebook
The core of this repository is a single, well-documented Jupyter Notebook:

text
PotatoDisease_GDSW_DenseNet169.ipynb
You may view the notebook directly in GitHub or launch it in Google Colab using the button below.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.google.com/github/<your-username>/<repo-name>/blob/main/PotatoDisease_GDSW_DenseNet-username>and<repo-name>` with your actual GitHub details.)*

Requirements
Python 3.8+

Jupyter Notebook

torch

torchvision

timm

scikit-learn

mmcv-full

thop

einops

seaborn

matplotlib

pandas

tqdm

To install dependencies:
pip install torch torchvision timm scikit-learn mmcv-full thop einops seaborn matplotlib pandas tqdm

How to Run
Clone the repository:

git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
Download and prepare the dataset.

See Dataset instructions below for details.

Place the dataset inside a directory named data/.

Open the notebook:

Locally: jupyter notebook PotatoDisease_GDSW_DenseNet169.ipynb

Or use the “Open in Colab” badge above.

Run all cells in the notebook to reproduce the experiments and results.




