Project 01: Instacart Data Analysis

Project Overview

OilyGiant, a mining company, aims to identify the most profitable region to develop a new oil well. This project uses exploratory data analysis and a linear regression model to predict oil reserves based on data from three regions. Key steps include:
Analyzing regional oil sample data


Training a linear regression model to predict oil volume


Selecting the top 200 most promising well sites out of 500


Estimating potential profit under a $100M budget


Evaluating financial risk and excluding high-risk regions (>2.5% chance of loss)


The final goal is to recommend the region with the highest expected profit while maintaining acceptable risk levels.

Dataset Access

Due to file size limitations, the dataset required for this analysis is hosted externally on Google Drive.

Instructions to Download and Set Up the Dataset:

1. [Click here to download the dataset from Google Drive](https://drive.google.com/drive/folders/1mZ--ezkxjBE-0pGjKT-GLeorUL_QX6MI?usp=sharing)

2. Once downloaded, follow these simple steps to prepare your local environment:

Navigate to your local project-01-instacart directory.

Create a new folder named exactly datasets within this directory:

project-01-instacart/
├── notebook.ipynb
└── datasets/   (create this folder)

Place the downloaded dataset file clearly into this new datasets folder:

project-01-instacart/
├── notebook.ipynb
└── datasets/
    └── instacart_dataset.csv  (place dataset file here)

Running the Notebook

Open the notebook file (notebook.ipynb) in Jupyter Notebook, ensure your dataset is placed correctly as described above, and execute the cells sequentially.