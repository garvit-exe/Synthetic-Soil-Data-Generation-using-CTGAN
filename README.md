# Synthetic Soil Data Generation using CTGAN

This project demonstrates the generation of synthetic soil data using the CTGAN (Conditional Tabular Generative Adversarial Networks) model. The goal is to create realistic and privacy-preserving synthetic data that can be used for various purposes, such as data analysis, machine learning model training, and software testing.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Methodology](#methodology)
  - [Data Preprocessing](#data-preprocessing)
  - [Model Training](#model-training)
  - [Data Generation](#data-generation)
  - [Evaluation](#evaluation)
- [Dependencies](#dependencies)
- [Usage](#usage)
- [Results](#results)
- [Conclusion](#conclusion)

## Introduction

Synthetic data generation is a crucial technique for addressing privacy concerns and data scarcity issues. This project focuses on generating synthetic soil data, which can be valuable for agricultural research, environmental modeling, and other applications. The CTGAN model, a state-of-the-art generative model for tabular data, is employed for this purpose.

![image](https://github.com/user-attachments/assets/b18dd022-a7f5-430a-a814-b35cfd23a6f5)


## Dataset

The [dataset](https://www.kaggle.com/datasets/ashishkumarak/soil-dataset) used in this project is the "soil.csv" file, which contains information about various soil properties. The dataset includes features such as district, pH, EC, OC, N, P, K, S, Zn, Fe, Cu, Mn, and B. The dataset is preprocessed before being used for model training.

## Methodology

### Data Preprocessing

The data preprocessing steps involve handling missing values, converting categorical variables to numerical representations, and scaling numerical features. These steps ensure that the data is in a suitable format for the CTGAN model.

### Model Training

The CTGAN model is trained on the preprocessed soil data. The model learns the underlying patterns and relationships within the data to generate realistic synthetic data. The training process involves optimizing the model's parameters to minimize the difference between the real and synthetic data distributions.

### Data Generation

Once the CTGAN model is trained, it can be used to generate synthetic soil data. The model generates new data points that resemble the original data in terms of statistical properties and relationships between features. The number of synthetic data points to be generated can be specified.

### Evaluation

The quality of the synthetic data is evaluated using various metrics, such as statistical similarity, distribution comparisons, and correlation analysis. The goal is to ensure that the synthetic data accurately reflects the characteristics of the original data while preserving privacy.

## Dependencies

The project requires the following dependencies:

- Python 3.7 or higher
- pandas
- scikit-learn
- sdv (Synthetic Data Vault)
- plotly

These dependencies can be installed using pip:

```bash
pip install pandas scikit-learn sdv plotly
```

## Usage

1. Clone the repository:
    ```bash
    git clone https://github.com/garvit-exe/Synthetic-Soil-Data-Generation-using-CTGAN.git
    ```

2. Install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the Jupyter Notebook:
    ```bash
    jupyter-notebook synthetic_soil_data.ipynb
    ```

4. Execute the code cell by cell in the notebook and generate synthetic data.

## Results

The generated synthetic soil data exhibits high quality and closely resembles the original data in terms of statistical properties and relationships between features. The evaluation metrics indicate that the synthetic data is realistic and privacy-preserving.

## Conclusion

This project demonstrates the successful generation of synthetic soil data using the CTGAN model. The synthetic data can be used for various purposes, such as data analysis, machine learning model training, and software testing, without compromising privacy. The project highlights the potential of synthetic data generation in addressing data scarcity and privacy concerns in various domains.
