# car-price-prediction
A machine learning project that predicts used car prices using Multiple Linear Regression with data preprocessing, visualization, and model evaluation.
🚗 Used Car Price Prediction using Machine Learning

📌 Project Overview

The used car market is growing rapidly as many people prefer buying second-hand cars instead of new ones due to cost advantages. However, pricing a used car correctly can be difficult and sometimes misleading.

This project builds a Machine Learning model using Multiple Linear Regression to predict the selling price of used cars based on various features such as car age, price, kilometers driven, fuel type, and more.



🎯 Objective

- Predict the selling price of a used car
- Help buyers and sellers make better decisions
- Reduce chances of price manipulation or fraud



📊 Dataset Details

The dataset contains 301 records with the following features:

- "Car_Name" – Name of the car (removed during preprocessing)
- "Year" – Year of purchase
- "Selling_Price" – Price the car is sold for (Target Variable)
- "Present_Price" – Current ex-showroom price
- "Kms_Driven" – Distance driven
- "Fuel_Type" – Petrol / Diesel / CNG
- "Seller_Type" – Dealer / Individual
- "Transmission" – Manual / Automatic
- "Owner" – Number of previous owners



⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn



🔄 Workflow

1. Data Collection

- Loaded dataset using "pandas.read_csv()"

2. Data Exploration

- Viewed dataset using ".head()" and ".tail()"
- Checked data types and missing values
- Used ".describe()" for statistical summary

3. Data Preprocessing

- Converted "Year" into car age
- Dropped unnecessary column "Car_Name"
- Converted categorical variables using One Hot Encoding

4. Data Visualization

- Used pairplot to visualize relationships
- Used heatmap to check feature correlations

5. Feature Selection

- Defined:
  - X (Independent variables)
  - y (Target variable)

6. Feature Scaling

- Applied StandardScaler to normalize data

7. Train-Test Split

- Split dataset into:
  - 70% Training
  - 30% Testing

8. Model Building

- Used Linear Regression
- Trained model using ".fit()"

9. Model Evaluation

- Mean Squared Error (MSE): ~4.39
- R² Score: ~0.83

10. Visualization of Results

- Scatter plot: Actual vs Predicted values
- Line plot comparison


📈 Results & Insights

- Model achieved around 83% accuracy
- Important factors affecting price:
  - Present Price (strong positive impact)
  - Car Age
- Negative impact factors:
  - Kilometers Driven
  - Manual Transmission



🧠 Key Learnings

- Importance of data preprocessing
- Handling categorical data
- Feature scaling improves performance
- Visualization helps understand data patterns
- Regression models for prediction tasks



📂 Project Structure

Used-Car-Price-Prediction/
│
├── car_data.csv
├── main.ipynb
├── README.md



🚀 How to Run the Project

Step 1: Clone Repository

git clone https://github.com/your-username/used-car-price-prediction.git

Step 2: Install Dependencies

pip install pandas numpy matplotlib seaborn scikit-learn

Step 3: Run Notebook

jupyter notebook


🔮 Future Improvements

- Implement advanced models:
  - Random Forest
  - XGBoost
- Hyperparameter tuning
- Build a web app using Streamlit or Flask
- Deploy model online


🤝 Contribution

Feel free to fork this repository and improve the project.


📜 License

This project is open-source and free to use.


👩‍💻 Author
shifa fathima 
