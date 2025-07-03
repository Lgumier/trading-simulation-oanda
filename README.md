# FX Trading Simulation – RMIT Trading Competition 2025

BAFI1065 – Fixed Income Securities & Credit Analysis / Trading Simulation Project  
📍 RMIT University, Semester 1 – 2025  

---

## 📘 Project Overview  
This project was developed as part of the **RMIT Finance Trading Competition 2025**, where participants acted as FX traders in a simulated real-time environment using the RMIT Trader platform and live pricing data.

The notebook implements a basic automated trading system capable of quoting FX rates, executing buy/sell orders, and detecting **triangular arbitrage opportunities** across AUD/USD, AUD/EUR, USD/JPY and related pairs via the **OANDA Practice API**.

The system simulates realistic price-making and order-matching logic in line with official competition rules.

---

## 📁 Repository Structure

| Folder / File                    | Contents                                                        |
|----------------------------------|-----------------------------------------------------------------|
| `Trading_simulation.ipynb`       | Jupyter Notebook with FX quoting and execution logic            |
| `requirements.txt`               | Python dependencies (requests, pandas)                         |
| `.gitignore`                     | Standard exclusions (checkpoints, cache, credentials)          |
| `README.md`                      | This project overview                                           |

---

## 📊 Tools and Models Used

- **Python 3.10+**
- `requests`, `pandas`
- FX quoting logic, triangular arbitrage detection
- OANDA v3 REST API (practice environment)

> **Note:** This notebook uses placeholders for sensitive values:  
> `ACCESS_TOKEN = "INSERT_OANDA_ACCESS_TOKEN"`  
> `ACCOUNT_ID   = "INSERT_OANDA_ACCOUNT_ID"`  

---

## ▶️ Open in Google Colab

Want to test it online?  
Click below to launch the notebook in **Google Colab** (insert your own API keys to run it):

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/trading-simulation-oanda/blob/main/Trading_simulation_MM_Arbitrage_RMIT.ipynb)

> 🛠 Make sure to replace the API placeholders before executing!

---

## 🤝 License  
[MIT License](https://opensource.org/licenses/MIT) – Free to use, modify, and share with attribution.

---

## 📩 Contact  
For any questions about the notebook or the competition framework, feel free to reach out via GitHub or connect on [LinkedIn](https://www.linkedin.com/in/lorenzo-gumiero-952452200/).
