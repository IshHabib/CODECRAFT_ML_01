# CODECRAFT_ML_01
## House Price Prediction

This project predicts the **sale prices of houses** using a simple **Linear Regression** model which is trained on a dataset that includes features like **square footage**, **number of bedrooms**, and **total number of bathrooms**.

---

##  Dataset

* **train.csv** — Used to train the model (includes actual SalePrice)
* **test.csv** — Used for prediction (SalePrice not provided)

---

##  Features Extracted

The model uses the following features:

* `GrLivArea` — Ground living area (square footage)
* `BedroomAbvGr` — Number of bedrooms above ground
* `TotalBathrooms` — Custom feature combining:

  * FullBath + 0.5 × HalfBath
  * BsmtFullBath + 0.5 × BsmtHalfBath

---


##  Model

* Model: **Linear Regression** (from scikit-learn)
* Libraries used: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`

---

##  How to Run

1. Clone the repo or open the notebook in Google Colab.
2. Ensure `train.csv` and `test.csv` are in your working directory.
3. Run the notebook to:

   * Train the model on `train.csv`
   * Predict `SalePrice` for `test.csv`
   * Save predictions to `submission.csv`

---

##  Model Evaluation

Model performance on training data:

| Metric   | Value       |
| -------- | ----------- |
| MSE      | *123456.78* |
| RMSE     | *351.37*    |
| R² Score | *0.87*      |

*(Values are examples — update with your actual results)*

---

##  Output

The final output is:

* A **plot of Actual vs Predicted Prices**

<img width="335" height="158" alt="image" src="https://github.com/user-attachments/assets/2c195703-bc5c-44e4-a1ef-01575cff0594" />


  
* It's **Graph**

<img width="521" height="347" alt="image" src="https://github.com/user-attachments/assets/473e7648-e25e-4119-859f-acdf00c9ee89" />


---


## Performer

* Name: Ishpreet Singh
* Internship Project: July 2025
* Linedin: (www.linkedin.com/in/ishpreet-bhatia-ai-ml)

---

## 📄 License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---
