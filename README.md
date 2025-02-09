# Titanic Survival Prediction 🚢💥

## Project Description 📊
This project involves analyzing the Titanic dataset to predict whether a passenger survived or not based on various features like age, gender, passenger class, fare, and others. The project steps include:
1. **Data Cleaning 🧹** – Cleaning the dataset by handling missing values, encoding categorical features, and preparing the data for machine learning.
2. **Exploratory Data Analysis (EDA) 🔍** – Visual exploration and analysis of data to discover trends, relationships, and patterns.
3. **Machine Learning Model 🤖** – Implementing a **Random Forest Classifier** to predict survival based on the data features. The model is trained and evaluated, and predictions are made on new data.
4. **Insights and Conclusion 💡** – The final output includes performance metrics, insights from the data, and conclusions.

## Insights and Conclusions 📝
After analyzing the Titanic dataset and training the Random Forest model, several key insights emerged:

1. **Survival Rates by Gender** 🧑‍🤝‍🧑: 
   - A significant pattern was observed where **women** had a much higher survival rate compared to men. 
   - **Female passengers** survived at a rate of **74%**, while **male passengers** survived at only **18%**. This aligns with historical accounts of women and children being prioritized during evacuation.

2. **Passenger Class Impact (Pclass)** 🚂:
   - Passengers in **1st class** had a higher survival rate than those in **2nd** and **3rd class**. 
   - The survival rate for **1st class passengers** was around **63%**, while **2nd class** was **47%** and **3rd class** was **24%**. This suggests that higher-class passengers had better access to lifeboats.

3. **Age Distribution and Survival** 👶👵:
   - Younger passengers had a higher chance of survival. 
   - The survival rate for **children (0-10 years)** was around **60%**, while the survival rate for **elderly passengers (65+ years)** was quite low, around **20%**.

4. **Fare and Survival Correlation** 💵:
   - There is a positive correlation between the **fare** paid and the likelihood of survival. 
   - Passengers who paid higher fares were more likely to survive, indicating that higher-class cabins and better accommodations were associated with higher survival chances.

5. **Embarked Location** 🌍:
   - Passengers who embarked from **Cherbourg (C)** had a higher survival rate compared to those who embarked from **Southampton (S)** or **Queenstown (Q)**. This could be attributed to the differences in passenger demographics and class distribution at the embarkation points.

6. **Model Performance 🏆**:
   - The **Random Forest Classifier** achieved an accuracy of **79%** on the test dataset.
   - **Feature importance** showed that **Sex**, **Pclass**, and **Fare** were the most influential features in predicting survival.

## Technologies Used 💻
The following tools and technologies were used to complete this project:

- **Python 🐍**: Programming language for the data pipeline, machine learning model, and analysis.
- **Pandas 📦**: Data manipulation and preprocessing.
- **Matplotlib & Seaborn 📊**: Data visualization.
- **Scikit-learn 🔧**: Machine learning model (Random Forest Classifier).
- **Jupyter Notebook 📓**: Interactive environment to run code, analyze data, and document the process.
- **NumPy 🔢**: Numerical operations.
- **Kaggle Titanic Dataset 🛳️**: The dataset used for analysis and model training.

## Dataset 📋
The dataset used is from Kaggle and contains information about Titanic passengers, including:
- **PassengerId**: Unique identifier for each passenger.
- **Pclass**: The class of the passenger (1, 2, or 3).
- **Name**: The passenger’s name.
- **Sex**: The passenger’s gender.
- **Age**: The passenger’s age.
- **SibSp**: Number of siblings/spouses aboard.
- **Parch**: Number of parents/children aboard.
- **Ticket**: Ticket number.
- **Fare**: Fare paid by the passenger.
- **Cabin**: Cabin number.
- **Embarked**: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).
- **Survived**: Whether the passenger survived (1 = survived, 0 = did not survive).

## Visualizations 📊✨
In this project, several types of visualizations were created:
![Image](https://github.com/user-attachments/assets/3ba19fe5-c05c-49b4-b4df-4849eb39423a)
- **Bar plots 📊** for categorical data (e.g., sex, passenger class).
- **Histograms 📈** for continuous data (e.g., age, fare).
- **Heatmaps 🔥** to observe correlations between features.
- **Pair plots 🔗** to examine relationships between pairs of features.
- **Box plots 📦** to detect outliers in continuous variables.
- **Violin plots 🎻** to visualize distributions grouped by categorical variables.

## Usage 🏁
After running the Jupyter notebook, follow the instructions inside the notebook to understand how the data is cleaned, visualized, and used for training the machine learning model. You can also change the dataset or parameters to explore different results.

## Contributing 🤝
If you want to contribute to this project, feel free to fork the repository, create a branch, make your changes, and submit a pull request. Contributions are always welcome!

## License 📜
This project is licensed under the MIT License - see the LICENSE file for details. ✨
