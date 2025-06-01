# 📈 Stock Price Prediction Using RNNs

## 🧠 Project Overview

This project explores time series forecasting using Recurrent Neural Networks (RNNs) to predict the stock prices of four major technology companies: Amazon (AMZN), Google (GOOGL), IBM, and Microsoft (MSFT). Two neural network architectures were evaluated:

- **Simple RNN**
- **Advanced RNN (LSTM)**

The models were trained on historical stock data from 2006 to 2018 and assessed on their ability to predict future stock prices.

---

## 📂 Dataset

Each company’s historical stock data includes the following columns:

- `Date`: Date of observation (2006–2018)
- `Open`: Stock price at market opening
- `High`: Highest price of the day
- `Low`: Lowest price of the day
- `Close`: Stock price at market close
- `Volume`: Number of shares traded

---

## ⚙️ Technologies Used

- Python
- NumPy, Pandas
- Matplotlib, Seaborn
- Scikit-learn
- TensorFlow / Keras

---

## 🏁 Final Results

| Metric                            | Simple RNN        | LSTM (Advanced RNN) |
|----------------------------------|-------------------|---------------------|
| **RMSE**                         | **$27.42**         | $52.59              |
| **MAE**                          | **$21.15**         | $41.06              |
| **MAPE**                         | **3.08%**          | 5.85%               |
| **Max Absolute Error**           | $107.46            | $169.58             |
| **Correlation Coefficient**      | **0.9944**         | 0.9813              |

---

## ✅ Key Takeaways

- **Simple RNN outperformed the LSTM model** in all evaluation metrics.
- The results show that **simpler models can outperform more complex ones** when the data and problem structure are well-suited.
- The Simple RNN model is more stable and accurate for this specific stock prediction task.

---

## 📘 Conclusion

The Simple RNN model was the optimal architecture for predicting stock prices in this dataset. It achieved:
- Higher accuracy
- Lower error
- Better correlation with actual prices

These findings emphasize the importance of **empirical model evaluation** over assumptions about architectural superiority.

---

## 📁 Repository Structure

```bash
📦RNN_Stocks_Data/
 ┃ ┣ AMZN.csv
 ┃ ┣ GOOGL.csv
 ┃ ┣ IBM.csv
 ┃ ┗ MSFT.csv
 ┣ 📓 RNN_Assg_Stock_Price_Prediction_RaghavMishra_MuthuvadivelB.ipynb
 ┗ 📄 README.md


✍️ Authors

Raghav Mishra
Muthuvadivel B
