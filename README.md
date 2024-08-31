# High School Students' Grade Prediction

This repository contains a project focused on the exploration of data and prediction of academic grades for a sample of high school students. The data sources are extracted from Kaggle, and the project includes exploratory data analysis (EDA) and predictive modeling using Python.

## Project Structure

- **`dataset/`**: This folder contains the data sources used in the project. The datasets have been extracted from Kaggle and are utilized for both data exploration and modeling.

- **`grade_EDA_PDA.ipynb`**: This Jupyter Notebook is the core of the project. It includes:
  - **Exploratory Data Analysis (EDA)**: Investigation of the dataset to understand the distributions, relationships, and key patterns.
  - **Predictive Data Analysis (PDA)**: The application of machine learning models to predict students' grades based on the explored features.

- **`grade_documentation.pdf`**: This PDF document provides detailed documentation of the project, including the methodology, data processing steps, model selection, and evaluation.

## Requirements

To run this project, you will need to have the following Python packages installed:

- matplotlib
- numpy
- pandas
- pillow
- plotly
- scikit-learn
- scipy
- seaborn

You can install all the required packages using the following command:

```bash
pip install -r requirements.txt
```
## How to Run the Project

1. Clone the repository:
```bash
git clone https://github.com/lalessia/grades-prediction.git
```
2. Navigate to the project directory:
    ```bash
    cd grades-prediction
    ```
3. Open the Jupyter Notebook: You can open the notebook using Jupyter Notebook or Jupyter Lab.
    ```bash
    jupyter notebook grade_EDA_PDA.ipynb
    ```
4. Run the notebook: Execute the cells in the notebook to perform the data exploration and run the predictive models.


# Old Alcohol and Young

This project aims to analyze the academic performance of a sample of high school students, with the aim of identifying the factors that most influence the final results and carrying out predictive assessments.


# Repository

Repository structure:

- **dataset/**: The directory containing the datasets that were used https://www.kaggle.com/datasets/uciml/student-alcohol-consumption/data
- **Alchol_Youth_EDA_PDA.ipynb**: heart of the project, this file containing the export analysis and the predictive analysis performed with python

# Execution Alchol_Youth_EDA_PDA.ipynb

This project includes a Jupyter Notebook (.ipynb) file that can be executed and modified by following these steps:

Make sure you have <i>installed Python 3.9 or higher</i>. You can download and install it from the official [Python website](https://www.python.org/downloads/).

<b><i>Installing Jupyter Notebook</i></b>

You can <i>install Jupyter Notebook</i> using pip or Anaconda.

<b>Using pip</b>

1. Install `pip` if you haven't already.
2. Create a virtual environment:

    ```bash
    python -m venv myenv
    ```

3. Activate the virtual environment:

    - On Windows:

      ```bash
      myenv\Scripts\activate
      ```

    - On macOS/Linux:

      ```bash
      source myenv/bin/activate
      ```

4. Install Jupyter Notebook:

    ```bash
    pip install jupyter
    ```

<b>Using Anaconda</b>

1. Download and install [Anaconda](https://www.anaconda.com/products/individual).
2. Create a new environment:

    ```bash
    conda create --name myenv
    ```

3. Activate the environment:

    ```bash
    conda activate myenv
    ```

4. Install Jupyter Notebook:

    ```bash
    conda install jupyter
    ```

### Running the Notebook

1. Start Jupyter Notebook:

    ```bash
    jupyter notebook
    ```

2. This will open a browser window. Navigate to the `project.ipynb` file and open it.
