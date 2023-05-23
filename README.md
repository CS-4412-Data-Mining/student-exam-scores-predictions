# Student Exam Score Predictions

This is a Multiple Linear Regression (MLR) model that predicts exam scores of fictitious high school students based on
several external factors (like parental level of education). The dataset used for this model can be found
[HERE](http://roycekimmons.com/tools/generated_data/exams).

## Setup

To obtain the latest version of **pip**, input the following command in your terminal:

```bash
$ pip3 install --upgrade pip
```

Using pip, install **Jupyter**, **pandas**, **Matplotlib**, and **scikit-learn** one after another.

```bash
$ pip3 install jupyter
$ pip3 install pandas
$ pip3 install matplotlib
$ pip3 install scikit-learn
```

To ensure that each of the aforementioned packages is installed properly, input the following command:

```bash
$ pip3 list
```

## Installation

Now, `git clone` this repository, and navigate to the `student-exam-scores-predictions` directory.

```bash
$ git clone https://github.com/CS-4412-Data-Mining/student-exam-scores-predictions.git
$ cd student-exam-scores-predictions
```

## Usage

First, open `basic_visualizations.ipynb` to view different visualizations of the `StudentsPerformance.csv` dataset.

```bash
$ jupyter notebook basic_visualizations.ipynb
```

Next, navigate to http://localhost:8888/notebooks/basic_visualizations.ipynb in the browser, and press the ⏩ button to
restart the kernel and rerun the whole notebook.

Second, open `test_score_regression.ipynb` to observe the MLR model.

```bash
$ jupyter notebook test_score_regression.ipynb
```

Next, navigate to http://localhost:8888/notebooks/test_score_regression.ipynb in the browser, and press the ⏩ button to
restart the kernel and rerun the whole notebook.
