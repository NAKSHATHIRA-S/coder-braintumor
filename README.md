# coder-braintumor
## Brain Tumor Classification
This repository contains code for classifying whether a patient has a brain tumor based on the provided dataset from Kaggle. The dataset consists of images of brain scans categorized into two classes: tumor and healthy.

## Dataset Description
The dataset contains two folders:
- `Brain Tumor`: Contains images of brain scans with tumors.
- `Healthy`: Contains images of healthy brain scans

Additionally, there are two CSV files containing metadata:
- `metadata.csv`: Contains metadata for all images, including the image filename, class (tumor or healthy), format, mode, and shape.
- `metadata_rgb_only.csv`: Contains metadata for images with the RGB mode only.

## Code Overview

- `data_preprocessing.ipynb`: Jupyter Notebook for preprocessing the data, including loading images, resizing, and flattening them for model training.
- `model_training.ipynb`: Jupyter Notebook for training machine learning models (Gradient Boosting, Random Forest, SVM) for tumor classification.
- `README.md`: This file providing an overview of the project and instructions.

## Usage

1. Download the dataset from Kaggle: [Brain Tumor Data](https://www.kaggle.com/debarghamitraroy/brain-tumor-data).
2. Extract the contents of the downloaded zip file and place them in the appropriate folders (`Brain Tumor` and `Healthy`).
3. Run the `data_preprocessing.ipynb` notebook to preprocess the data.
4. Run the `model_training.ipynb` notebook to train the classification models.
5. Evaluate the models and analyze the results.


## Dependencies
- Python 3.x
- Jupyter Notebook
- NumPy
- pandas
- scikit-learn
- PIL (Python Imaging Library)

  
## Results and Analysis
The trained models can be evaluated using metrics such as accuracy and classification report. Additionally, feature importance can be analyzed to identify the strongest parameters influencing tumor classification.

## License
The dataset is provided by [Kaggle](https://www.kaggle.com/), and the code in this repository is available under the [MIT License](LICENSE).


