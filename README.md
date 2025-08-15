# OIBSIP_Data_Analytics_Project1_Level2
Alright — here’s a clean **README.md** for your **House Price Prediction** project.

---

```markdown
#  House Price Prediction

This project predicts house prices based on various features such as area, number of bedrooms, bathrooms, parking, and other amenities.  
We use **Linear Regression** from `scikit-learn` to build the model.

---

##  Project Structure
```

HOUSE\_PRICE\_PREDICTION/
│
├── Housing.csv        # Dataset
├── main.ipynb         # Jupyter Notebook with analysis and model

````

---

##  Dataset

The dataset `Housing.csv` contains the following features:

| Feature | Description |
|---------|-------------|
| price   | Price of the house (target) |
| area    | Area of the house (sq. ft.) |
| bedrooms | Number of bedrooms |
| bathrooms | Number of bathrooms |
| stories | Number of floors |
| mainroad | Whether the house is on the main road (yes/no) |
| guestroom | Whether there is a guestroom (yes/no) |
| basement | Whether there is a basement (yes/no) |
| hotwaterheating | Availability of hot water heating (yes/no) |
| airconditioning | Availability of air conditioning (yes/no) |
| parking | Number of parking spaces |
| prefarea | Whether it is in a preferred area (yes/no) |
| furnishingstatus | Furnishing status (furnished, semi-furnished, unfurnished) |

---

##  Installation

Make sure you have Python **3.12+** installed, then install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
````

---

##  How to Run

1. Clone the repository or download the files.
2. Open `main.ipynb` in **Jupyter Notebook** or **VS Code**.
3. Run all cells in order (`Run All`).
4. The notebook will:

   * Load and explore the dataset
   * Encode categorical variables
   * Train a Linear Regression model
   * Evaluate model performance
   * Show feature importance

---

## 📈 Model Performance

Metrics calculated on the test set:

* **R² Score**: Measures the proportion of variance explained by the model.
* **Mean Squared Error (MSE)**: Measures average squared prediction error.
* **Root Mean Squared Error (RMSE)**: Measures error in same units as target.

---

##  Example Output

**Feature Importance Table:**

| Feature              | Coefficient |
| -------------------- | ----------- |
| bathrooms            | 1.09e+06    |
| airconditioning\_yes | 7.91e+05    |
| prefarea\_yes        | 6.29e+05    |
| ...                  | ...         |

---

##  License

This project is for educational purposes only.
You can modify and use it for your own learning.

```

---

If you want, I can also **add a short “Project Summary” section** at the top so it sounds more professional for your internship submission. That way it’s not just technical but also has a business explanation.
```
