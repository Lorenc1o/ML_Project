# Machine Learning (ML-MDS, BDMA) Project 2023

This is the repository for the project of the course Machine Learning (ML-MDS, BDMA) at the Universitat Politècnica de Catalunya (UPC), Barcelona, Spain, for the 2023 Spring Semester.

## Team

- Jose Antonio Lorencio Abril [@Lorenc1o](https://www.github.com/Lorenc1o)
- Mariana Mayorga Llano [@marianamllano](https://www.github.com/marianamllano)

## Project Description

We had to choose a dataset and a task to perform on it. We chose the [adult dataset](https://archive.ics.uci.edu/ml/datasets/adult) and the task of predicting whether a person earns more than 50k a year or not. We also addressed the problem of fairness in machine learning, and tried to mitigate the bias in our model by applying the approach exemplified in [Attacking discrimination with smarter machine learning](https://research.google.com/bigpicture/attacking-discrimination-in-ml/).

## Project Structure

The project is structured as follows:
- `data/`: contains the dataset and the preprocessed data
- `source/`: contains the notebooks used for the project
- `report/`: contains the report of the project, with explanations, results and conclusions

## How to run the code

You will need the libraries specified in `requirements.txt`. To install them, run `pip install -r requirements.txt`. Then, you can run the notebooks in `source/` in order to reproduce the results.