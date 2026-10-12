Neural Network Exercises (1--10)

This repository contains ten interactive Python notebook exercises
exploring neural-network models, associative memory, unsupervised
learning, and pattern classification on standard machine-learning
datasets.

Exercises

Exercise                Topic                   Dataset

1                       Perceptron-based        Banknote Authentication
decision boundaries and
linear separability

2                       Backpropagation neural  Breast Cancer Wisconsin
network prediction and  (Diagnostic)
feature analysis

3                       Feedforward             Fashion-MNIST
neural-network
diagnostics for
learning rate,
gradients, and
overfitting

4                       ADALINE adaptive        Iris
pattern classification
and prediction

5                       MADALINE heart-disease  Heart Disease
classification and
adaptive decision
analysis

6                       Bidirectional           Optical Recognition of
Associative Memory      Handwritten Digits
(BAM) for digit/code
association

7                       Boltzmann and Cauchy    Wine Quality
machines for stochastic
feature selection and
energy optimization

8                       Self-Organizing Map     Mall Customers
(SOM) customer
segmentation and
cluster exploration

9                       Hopfield neural-network Optical Recognition of
associative memory and  Handwritten Digits
pattern reconstruction

Project Structure

The main files are Jupyter notebooks:

Exercise_1.ipynb
Exercise_2.ipynb
Exercise_3.ipynb
Exercise_4.ipynb
Exercise_5.ipynb
Exercise_6.ipynb
Exercise_7.ipynb
Exercise_8.ipynb
Exercise_9.ipynb
Exercise_10.ipynb

Related DOCX reports may also be included. Each report separates the
program INPUT from a descriptive OUTPUT section.

Requirements

Use Python 3 with Jupyter Notebook or Google Colab. Depending on the
notebook, common libraries may include:

numpy

pandas

matplotlib

scikit-learn

tensorflow / keras (where used)

openpyxl (for Excel datasets)

ucimlrepo (where used to retrieve a UCI dataset)

Install common dependencies in a notebook cell if needed:

%pip install numpy pandas matplotlib scikit-learn tensorflow openpyxl ucimlrepo

Not every exercise needs every package. If a notebook reports a
missing-module error, install the package named in that error and rerun
the relevant cell.

How to Run

Open Google Colab or Jupyter
Notebook.

Upload or open the required Exercise_N.ipynb notebook.

Run the notebook cells from top to bottom. If the notebook provides
a menu, run the cell containing the menu and enter the option
number.

Follow any dataset download or upload prompts.

Choose an experiment from the menu, review the printed metrics
and/or visualizations, and return to the menu to try another option.

Select the menu's Exit option when you are finished, if one is
provided.

Dataset Notes

The exercises use different datasets. Some notebooks may retrieve data
automatically; others may require a local CSV, Excel, or ZIP file to be
uploaded. If automatic retrieval fails:

Download the dataset from the source specified in that notebook.

Upload the file when prompted, or place it at the path expected by
the notebook.

Check that the file name and column names match what the notebook
expects.

For example, the Dry Bean exercise may use a CSV or Excel version of the
Dry Bean Dataset, while the Mall Customers exercise may require a
Mall_Customers.csv file. Use the exact file format and column names
expected by the corresponding notebook.

What the Exercises Explore

Supervised classification: Perceptron, backpropagation, ADALINE,
and MADALINE.

Training diagnostics: learning-rate behaviour, gradient-related
issues, and overfitting.

Associative memory and reconstruction: BAM and Hopfield
networks.

Stochastic optimization: Boltzmann and Cauchy machine
approaches.

Unsupervised learning and clustering: SOM and ART.

Evaluation and analysis: model predictions, accuracy or other
metrics, feature behaviour, category formation, recall, and cluster
exploration, where implemented.

The exact outputs and metric values depend on the notebook code,
dataset, model settings, and runtime. Run each notebook to obtain its
actual results.

Troubleshooting

Dataset download error: Use the upload option provided by the
notebook, if available, and upload the correct dataset file.

Missing Python package: Install the missing package in a new
notebook cell and rerun the notebook.

File not found: Confirm the file was uploaded and the path/name
matches the code.

Slow execution: Reduce the number of samples or training
iterations if the notebook provides such controls.

Unexpected results: Check the selected menu option, dataset
columns, preprocessing, and model parameters.

Notes

These notebooks are educational implementations intended for
experimentation and learning. Results should be interpreted in the
context of each exercise and its dataset. In particular, heart-disease
classification is a learning exercise and is not a substitute for
professional medical assessment.
