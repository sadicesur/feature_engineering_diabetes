# Data Alchemy: Transforming Diabetes Data with Feature Engineering Wizardry

<div style="text-align: justify">Welcome to this Jupyter notebook project, where we delve into the realm of feature engineering to develop a machine learning model for predicting whether individuals have diabetes. Our primary goal is to emphasize the significance of data analysis and feature engineering in building reliable predictive models. Before we proceed to model development, we will conduct essential data analysis steps and explore feature engineering techniques to extract meaningful information from the dataset. By focusing on these foundational aspects, we aim to lay a solid foundation for a robust and interpretable model, highlighting the essential role of feature engineering in diabetes prediction. Let's embark on this enriching journey of transforming raw data into valuable insights for accurate predictions.</div>

## Dataset Information

<div style="text-align: justify">The dataset is a part of a large dataset maintained by the National Institute of Diabetes and Digestive and Kidney Diseases in the United States. It is specifically related to a diabetes research study conducted on Pima Indian women, aged 21 and above, residing in Phoenix, the largest city in the state of Arizona. The dataset contains valuable information used for investigating diabetes prevalence among the study participants.</div>

<div style="text-align: justify">The target variable, labeled as "outcome," is the focal point of the analysis. It is binary, with a value of 1 indicating a positive diabetes test result and 0 indicating a negative result. The dataset's attributes encompass diverse features, such as pregnancies, glucose levels, blood pressure, skin thickness, insulin levels, diabetes pedigree function, body mass index (BMI), and age, which are expected to contribute to the prediction of diabetes presence in the participants. The dataset offers an opportunity to delve into the world of feature engineering and machine learning to create a reliable model that can predict the likelihood of individuals having diabetes based on the provided features.</div>

- Pregnancies: Number of pregnancies
- Glucose: 2-hour plasma glucose concentration in an oral glucose tolerance test
- Blood Pressure: Diastolic blood pressure (mm Hg)
- SkinThickness: Triceps skinfold thickness (mm)
- Insulin: 2-hour serum insulin (mu U/ml)
- DiabetesPedigreeFunction: Diabetes pedigree function, providing a measure of the genetic influence of diabetes
- BMI: Body mass index (weight in kg / (height in m)^2)
- Age: Age in years
- Outcome: Whether the individual has diabetes (1) or does not have diabetes (0)

## Notebooks

The `notebooks/` directory contains Jupyter Notebooks used in the project:

- `01_data_analysis.ipynb`: Data exploration and visualization.
- `02_feature_engineering.ipynb`: Feature engineering and handling missing values.
- `03_model_development.ipynb`: Model development and evaluation.

## How to Run

To run the notebooks in this project, you'll need to have Python and Jupyter Notebook installed. You can install the required dependencies using the following command:

```
pip install -r requirements.txt
```

After installing the dependencies, navigate to the `notebooks/` directory and start Jupyter Notebook:

```
jupyter notebook
```

This will open a new browser window showing the Jupyter Notebook interface. You can then click on the notebooks to open and run them interactively.

## Results

The best performing machine learning model for diabetes prediction is stored in the `models/` directory. The model achieved an accuracy of X% on the test set.

## License

This project is licensed under the [MIT License](LICENSE).

Feel free to reach out if you have any questions or suggestions!
