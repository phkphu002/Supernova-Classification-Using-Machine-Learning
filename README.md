# Supernova Classification Using Machine Learning

## Project Overview

This project explores the application of machine learning techniques to astronomical data, focusing on the classification of supernovae based on their photometric light curves.

The objective is to distinguish between three supernova types:

- **Type Ia**
- **Type II**
- **Type Ibc**

The project uses Python-based scientific computing and machine learning libraries to extract meaningful features from supernova light curves and develop supervised classification models.

## Objectives

The main objectives of this project are to:

- Process and analyse photometric supernova light-curve data.
- Extract relevant features using the SALT2 model through the `sncosmo` package.
- Prepare astronomical data for machine learning applications.
- Implement and compare supervised machine learning classification algorithms.
- Evaluate classification performance using Receiver Operating Characteristic (ROC) curves and Area Under the Curve (AUC).
- Generate class probabilities for previously unlabelled supernova observations.

## Methodology

The project follows a machine learning workflow consisting of the following stages:

**1. Data Preparation and Feature Extraction**

Photometric light-curve observations are processed using `sncosmo` to fit the SALT2 model. The resulting model parameters are used as input features for machine learning.

**2. Data Preprocessing**

The extracted features are prepared for classification, including feature scaling where required by the selected algorithms.

**3. Machine Learning Classification**

Supervised machine learning classifiers are implemented using Scikit-learn to distinguish between the three supernova classes.

**4. Model Evaluation**

Classification performance is assessed using validation data, ROC curves and AUC scores to compare the predictive performance of the models.

**5. Prediction**

The selected classifier is applied to unlabelled supernova observations to estimate the probability of each object belonging to the three supernova classes.

## Technologies and Libraries

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Astropy
- sncosmo
- Scikit-learn

## Repository Structure

```text
supernova-classification-ml/
│
├── README.md
├── supernova_classification.ipynb
│
└── dataset/
    ├── training_data/
    ├── test_data/
    └── training_labels.txt
```

*Note: The dataset folder structure above is illustrative. Adjust it to match the actual files uploaded to the repository.*

## How to Run the Project

1. Clone this repository:

```bash
git clone https://github.com/YOUR-USERNAME/supernova-classification-ml.git
```

2. Navigate to the project directory:

```bash
cd supernova-classification-ml
```

3. Install the required Python libraries:

```bash
pip install numpy pandas matplotlib astropy sncosmo scikit-learn jupyter
```

4. Launch Jupyter Notebook:

```bash
jupyter notebook
```

5. Open `supernova_classification.ipynb` and execute the notebook cells.

## Project Context

This project was undertaken as part of the NASSP Observational Cosmology Course (2017), exploring the application of machine learning in observational astrophysics.

The tutorial was developed by Dr Michelle Lochner and introduced the use of machine learning for automated supernova classification.

## Author

**Phumlani**

Aspiring Data Analyst | Astrophysics Researcher | Python & Machine Learning

## Acknowledgements

- NASSP Observational Cosmology Course (2017).
- Dr Michelle Lochner – Machine Learning Tutorial.
- [Original Machine Learning Tutorial Repository](https://github.com/MichelleLochner/ml_tutorial).
- [Scikit-learn Documentation](https://scikit-learn.org/).

