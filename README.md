# Animal Image Identification

This repository contains the code and outputs for my **Animal Image Identification** project. The project is implemented on **Kaggle** and utilizes **VGG16** for feature extraction, with various boosting techniques applied to the extracted features.

## Project Overview

The project aims to classify animal images using **VGG16** for feature extraction, followed by boosting techniques such as **AdaBoost**, **XGBoost**, **Gradient Boosting**, and **LightGBM** for improved accuracy. The dataset consists of three animal categories, with 1000 images per category. Due to the large size, the dataset is split into four `.rar` files.

## Files in this repository:

- `Animal Image Identification.ipynb` — Jupyter Notebook with code and outputs. (Can be imported directly into **Kaggle**)
- `Animals_datasets.part1.rar`, `Animals_datasets.part2.rar`, `Animals_datasets.part3.rar`, `Animals_datasets.part4.rar` — The dataset split into four parts.

## Getting Started

### Prerequisites

To run this project, you will need:

- A **Kaggle** account (preferred) or a local setup with **Python 3.7+**.
- Libraries: `TensorFlow`, `Keras`, `NumPy`, `Pandas`, `Matplotlib`, `OpenCV`, `LightGBM`, `XGBoost`, `Scikit-learn`

### Installation (Kaggle)

1. Download or clone this repository:

    ```bash
    git clone https://github.com/yourusername/animal-image-identification.git
    ```

2. Upload the `.ipynb` file and the four `.rar` dataset files to your **Kaggle** notebook.

3. Unzip the dataset:

    - Download **all four parts** of the dataset (`Animals_datasets.part1.rar`, `Animals_datasets.part2.rar`, `Animals_datasets.part3.rar`, `Animals_datasets.part4.rar`).
    - Select **all four `.rar` files at once** and extract them together. This will create a **single folder** containing the dataset.
    - The folder structure after extraction should be:

        ```
        ├── dataset
            ├── category1 (e.g., cats)
            ├── category2 (e.g., dogs)
            ├── category3 (e.g., birds)
        ```

    Each category contains 1000 images of the respective animal.

4. Run the Kaggle notebook, executing each cell in order to train the model.

### Running Locally (Optional)

If you prefer to run locally (optional):

1. Download the `.ipynb` file and the dataset `.rar` files from the repository.

2. Extract the dataset using your preferred extraction tool that supports `.rar` files.

3. Run the notebook locally in Jupyter by installing the necessary libraries with:

    ```bash
    pip install -r requirements.txt
    ```

4. Open the notebook:

    ```bash
    jupyter notebook Animal Image Identification.ipynb
    ```

## Model Summary

- Model: **VGG16** used for **feature extraction**.
- Boosting Techniques: Applied **AdaBoost**, **XGBoost**, **Gradient Boosting**, and **LightGBM** to the extracted features.
- Dataset: Three animal categories, each containing 1000 images.
- Accuracy: The **VGG16 CNN** achieved **98.6%** accuracy, with further analysis of boosting techniques.

## Conclusion

This project explores the use of CNN-based feature extraction with **VGG16** and the application of boosting algorithms to improve the classification accuracy of animal images. The implementation is done on **Kaggle** for ease of use with large datasets.
