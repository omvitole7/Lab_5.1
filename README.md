# Lab_5.1

markdown
# 📈 LSTM Time Series Forecasting

This project implements an LSTM (Long Short-Term Memory) neural network for time series forecasting, inspired by the research paper **"ABBA: An Interpretable and Fast Symbolic Representation of Time Series" (arXiv:2003.05672v1)** and comparative reference to **"A Comprehensive Review on LSTM Architectures for Time Series Forecasting" (arXiv:1912.09363v3)**.

---

## 📚 Project Overview

This repository includes:
- ✅ Python implementation of an LSTM model for forecasting.
- 📊 Performance evaluation using MAE, MSE, and RMSE.
- 📄 Comparative analysis with literature results.
- 📝 A detailed project report.

---

## 🧠 Paper Summary

- **Paper Title**: *ABBA: An Interpretable and Fast Symbolic Representation of Time Series*
- **Key Idea**: Introduces ABBA, a symbolic representation technique to compress time series and accelerate forecasting.
- **Model**: Combines symbolic preprocessing with LSTM for efficient forecasting.
- **Claim**: Comparable performance to raw LSTM with easier training and better visual interpretability.

---

## 🔧 Implementation Details

- **Model**: 2-layer LSTM with dropout and dense output.
- **Sequence Length**: 50
- **Optimizer**: Adam
- **Loss Function**: Mean Squared Error (MSE)
- **Framework**: TensorFlow/Keras

---

## 🗂 Dataset

A sample time series dataset (`timesData.csv`) is used. You may replace it with your own or use a dataset similar to the one referenced in the paper.

---

## 📈 Results

| Metric | Reported in Paper | Your Model |
|--------|-------------------|------------|
| MAE    | Not Specified     | ✅ 5.701    |
| MSE    | Not Specified     | ✅ 49.289   |
| RMSE   | Not Specified     | ✅ 7.021    |

---

## 🔍 Discussion

- Results indicate low forecasting error, suggesting effective performance of the implemented LSTM model.
- Differences from the paper may arise due to:
  - Use of different datasets
  - Lack of ABBA symbolic transformation
  - Different hyperparameters and training conditions

---

## 📁 Repository Structure


├── LSTM_Time_Series_Report.docx   # Final report (summary, methodology, results, discussion)
├── timesData.csv                  # Dataset used for LSTM forecasting
├── lstm_forecasting.py            # Python implementation of LSTM
├── README.md                      # Project documentation


---

## ✅ How to Run

1. Clone the repo:
   bash
   git clone https://github.com/yourusername/LSTM-Time-Series-Forecasting.git
   cd LSTM-Time-Series-Forecasting
   

2. Install dependencies:
   bash
   pip install -r requirements.txt
   

3. Run the script:
   bash
   python lstm_forecasting.py
   

---

## 📬 Contact

Feel free to reach out for any questions or suggestions!

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).
