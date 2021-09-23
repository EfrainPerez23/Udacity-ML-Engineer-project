# Machine Learning Engineer Nanodegree
# Model Evaluation and Validation
## Project: Using Machine Learning to classify if a patient has diabetes

### Install

This project requires **Python** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [tensorflow](https://www.tensorflow.org/install)
- [keras](https://keras.io/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://jupyter.org/install.html).

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](https://www.anaconda.com/download/) distribution of Python, which already has the above packages and more included. 

### Code

Template code is provided in the `Capstone_Final_Project.ipynb` notebook file. You will also be required to use the `diabetes.csv` dataset file to complete your work. 

### Run

In a terminal or command window, navigate to the top-level project directory `boston_housing/` (that contains this README) and run one of the following commands:

```bash
ipython notebook Capstone_Final_Project.ipynb
```  
or
```bash
jupyter notebook Capstone_Final_Project.ipynb
```
or open with Jupyter Lab
```bash
jupyter lab
```

This will open the Jupyter Notebook software and project file in your browser.

### Data

The modified Boston housing dataset consists of 768 data points, with each datapoint having 9 features. You can get this dataset from [kaggle](https://www.kaggle.com/uciml/pima-indians-diabetes-database).

**Features**
1. **`Pregnancies`**: Number of times pregnant
2. **`Glucose`**: Plasma glucose concentration 2 hours in anoral glucose tolerance test.
3. **`BloodPressure`**: Diastolic blood pressure (mm Hg)
4. **`SkinThickness`**: Triceps skin fold thickness (mm)
5. **`Insulin`**: 2-Hour serum insulin (mu U/ml)
6. **`BMI`**: Body mass index (weight in kg/(height in m)^2)
7. **`DiabetesPedigreeFunction`**: Diabetes pedigree function
8. **`Age`**: years old


**Target Variable**

9. **`Outcome`**: Is diabetic person or not