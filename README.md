# Bipolar Cell Simulation
An edge detection model based off of biological bipolar cells

## Installation
To run the code, create a virtual environment in which to store the packages using the following command:
python -m venv .venv

To install the packages, run the following command:
pip install -r requirements.txt

The dataset will download automatically to the project directory upon running all the cells.

## Current Results
Currently, the project displays an example image from the test dataset. The same image is then shown as it is run through a Laplacian filter and as the data is normalized. The final result is how different bipolar cells would respond according to the given image. In both the on-center and off-center cell, a brighter pixel represents a stronger response for the given cell.