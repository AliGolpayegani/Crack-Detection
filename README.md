📌 Overview
This project implements a Convolutional Neural Network (CNN) for binary classification to detect cracks in surface images.
The model classifies images into:

Positive: Contains a crack

Negative: No crack detected

The workflow covers data preparation, model training, evaluation, and inference.

📂 Dataset
The dataset is the Surface Crack Detection dataset, containing:

Positive — images with visible cracks.

Negative — images without cracks.

Source: Downloaded from Google Drive (public link).
After download, images are split into:
dataset\_split/
├── train/
│   ├── Positive/
│   └── Negative/
└── test/
├── Positive/
└── Negative/

# Clone this repository
git clone https://github.com/yourusername/crack-detection.git
cd crack-detection

# Install dependencies
pip install -r requirements.txt

📜 How to Run
Download Dataset

The notebook uses gdown to download the dataset from Google Drive.

This step is automated in Crack_detection.ipynb.

Preprocess Data

Images are split into training and testing sets.

Data augmentation (optional) can be applied.

Train the Model

Run the training cells in the notebook.

The CNN learns to classify images as cracked or non-cracked.

Evaluate

Accuracy, loss curves, and confusion matrix are displayed.

Model performance is tested on the test set.

Inference

You can upload a custom image to see predictions.

📧 Contact
Author: Ali Golpayegani
📩 Email: aligolpa9877@gmail.com