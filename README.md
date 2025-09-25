# Brain-Tumor-MRI-Analysis-Using-CNN-Accuracy-98-
# Brain Tumor MRI Classification Using CNN

This project uses **Convolutional Neural Networks (CNNs)** to classify brain tumor types from MRI scans. The model achieves **~95% accuracy** in detecting tumor classes.

## Dataset

* **Source:** [Brain Tumor MRI Dataset](https://www.kaggle.com/datasets/dilahbaheci/brain-tumor-mri-classification)
* **Description:** The dataset contains MRI images of brains, labeled according to tumor type.
* **Classes:**

  * Glioma Tumor
  * Meningioma Tumor
  * Pituitary Tumor
  * No Tumor

## Model

* **Architecture:** Convolutional Neural Network (CNN)
* **Input:** MRI images (preprocessed and resized)
* **Output:** Predicted tumor class

## Features

* Image preprocessing and normalization
* Data augmentation for better generalization
* Training with CNN and evaluation
* Accuracy achieved: ~95%

## Usage

1. Clone the repository:

```bash
git clone https://github.com/yourusername/brain-tumor-cnn.git
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the training script:

```bash
python train.py
```

4. Evaluate the model:

```bash
python evaluate.py
```

## Results

* Confusion matrix, classification report, and accuracy metrics
* Visualization of correctly and incorrectly classified images

## License

This project is licensed under the MIT License.
