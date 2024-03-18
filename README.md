# Steel-Plate-Defect-Prediction

Steel Plate Defect Prediction project on GitHub, authored by Chand Rayee:

---

# Steel Plate Defect Prediction

## Overview
This project focuses on predicting defects in steel plates using machine learning techniques. The dataset used in this project is derived from the Steel Plates Faults dataset from the UCI Machine Learning Repository. The goal is to develop a predictive model capable of classifying the presence or absence of various types of defects in steel plates.

## Dataset
The dataset consists of two main files:

- `train.csv`: The training dataset containing features and labels for model training.
- `test.csv`: The test dataset for which predictions need to be made.

The training dataset includes features extracted from images of steel plates, along with binary labels indicating the presence or absence of each defect category. The test dataset requires predictions to be made for each defect category.

## Evaluation
Submissions are evaluated based on the area under the ROC curve (AUC) using the predicted probabilities and ground truth targets. The final score is calculated as the average AUC across all defect categories.

## Project Structure
The project is structured as follows:

- `train.csv`: The training dataset.
- `test.csv`: The test dataset.
- `submission.csv`: A sample submission file in the correct format.
- `model_training.ipynb`: Jupyter Notebook containing code for data preprocessing, model training, and evaluation.
- `submission_generation.ipynb`: Jupyter Notebook containing code for generating predictions on the test dataset and creating the submission file.
- `README.md`: This file providing an overview of the project.

## Usage
To reproduce the results or make predictions on new data, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/mrchandrayee/Steel-Plate-Defect-Prediction.git
   ```






## Contributors
- Chand Rayee ([GitHub](https://github.com/mrchandrayee))
- chandrayee ([About Me]([https://github.com/mrchandrayee](https://github.com/mrchandrayee/Chand-Rayee/blob/1b85fc39223f955bf4b5e08df4747e78e243626e/chandrayee.md)))
## License
This project is licensed under the [MIT License](LICENSE).

---
