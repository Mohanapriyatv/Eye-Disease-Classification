
# Eye Disease Classification

## Table of Contents
- [Project Overview](#project-overview)
- [About the Diseases](#about-the-diseases)
- [Use Case](#use-case)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Modeling](#modeling)
- [Results](#results)

## Project Overview
Eye disease classification is a research area that focuses on developing algorithms and models to accurately classify different types of eye diseases based on medical imaging data. This project aims to leverage machine learning and computer vision techniques to analyze medical images and detect four types of eye diseases: cataract, diabetic retinopathy, glaucoma, and normal.

## About the Diseases
1. **Cataract:** A common age-related eye condition characterized by the clouding of the lens, leading to blurry vision and visual impairment. It can be treated surgically by replacing the cloudy lens with an artificial one.

2. **Diabetic Retinopathy:** A complication of diabetes that affects the blood vessels in the retina. It can cause vision loss and, in severe cases, lead to blindness. Early detection and proper management of diabetes are crucial.

3. **Glaucoma:** A group of eye diseases that damage the optic nerve, often due to increased fluid pressure in the eye. It gradually leads to vision loss, starting with peripheral vision and potentially progressing to complete blindness. Timely diagnosis and treatment are vital.

## Use Case
Eye disease classification has several important use cases and applications:
1. **Screening and Early Detection:** Algorithms can serve as screening tools to identify individuals at risk of developing eye diseases, enabling prompt intervention and treatment.

2. **Diagnosis Support:** Models can assist healthcare professionals in making accurate diagnoses by providing additional insights and suggestions based on image analysis.

3. **Treatment Planning and Monitoring:** Classification algorithms can aid in treatment planning and monitoring by analyzing sequential imaging data, tracking disease progression, and assessing treatment effectiveness.

## Dataset
The dataset consists of approximately 1000 retinal images for each class: Normal, Diabetic Retinopathy, Cataract, and Glaucoma. These images are collected from various sources like IDRiD, Oculur recognition, and HRF.

## Installation
To run this project, you need to have Python installed along with the following libraries:
- pandas
- numpy
- scikit-learn
- tensorflow/keras (or PyTorch)
- matplotlib
- seaborn

You can install these dependencies using the following command:
```bash
pip install pandas numpy scikit-learn tensorflow matplotlib seaborn
```

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Eye-Disease-Classification.git
   cd Eye-Disease-Classification
   ```

2. Place the dataset in the `data` directory.

3. Run the Jupyter notebook to preprocess the data, train the model, and evaluate its performance:
   ```bash
   jupyter notebook Eye_Disease_Classification.ipynb
   ```

## Modeling
The project involves the following steps:
1. **Data Preprocessing:** Handling missing values, normalizing images, and augmenting the dataset.
2. **Exploratory Data Analysis (EDA):** Visualizing data distributions and relationships between features.
3. **Model Training:** Training different classification models using CNN architectures such as VGG16, ResNet50, etc.
4. **Model Evaluation:** Evaluating model performance using metrics such as accuracy, precision, recall, F1-score, and confusion matrix.

## Results
The results of the trained models, including the confusion matrix and performance metrics, are documented in the Jupyter notebook. The best-performing model is selected based on these evaluations.

