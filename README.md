🏡 Housing Price Prediction using Linear Regression

This project performs **simple and multiple linear regression** on housing data to predict house prices based on features like area, bedrooms, and more.

---

📁 Dataset

The dataset used is `Housing.csv` and includes the following features:

- `price` (Target variable)
- `area`
- `bedrooms`
- `bathrooms`
- `stories`
- `mainroad`, `guestroom`, `basement`, `hotwaterheating`, `airconditioning`
- `parking`
- `prefarea`
- `furnishingstatus`

---

📌 Objective

- Build a Linear Regression model
- Predict house prices using features such as area and other attributes
- Evaluate the model using metrics like MAE, MSE, and R² Score
- Visualize the regression line (for simple regression)

---

🛠️ Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn (LinearRegression, train_test_split, metrics)

---

 📊 Model Implementation Steps

1. Import required libraries
2. Load and clean the dataset (`Housing.csv`)
3. Select input features (`X`) and target variable (`y`)
4. Split the dataset into training and testing sets
5. Train a Linear Regression model
6. Make predictions on the test set
7. Evaluate performance using MAE, MSE, and R² Score
8. Plot regression line (for simple regression with one feature)

---

📈 Example Results
       MAE: 83279.47
       MSE: 123456789.00
       R² Score: 0.76

🖼️ Plot
       A scatter plot with a regression line will be generated for visual evaluation when using one feature like area.

✅ How to Run
   1. Clone this repo or copy the files
   2.Make sure Housing.csv is in the same directory
   3.Run the notebook:
                 jupyter notebook Housing_Linear_Regression.ipynb

📌 Author
       Shobin Salva K.G
       AI & ML Internship — Elevate Labs under MSME
       Task 3: Linear Regression

📜 License
       This project is for educational purposes.



