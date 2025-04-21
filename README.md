
# 📊 Financial and Industry Analysis Script

This repository contains a Python script designed to analyze financial and industry-related data using four interrelated CSV datasets. It leverages the power of the `pandas` library to perform in-depth data processing and compute key metrics.

---

## 📘 Overview

The script processes the following datasets:

- **`financial_information.csv`**: Contains macroeconomic data like inflation rate and GDP growth over various time periods.
- **`payment_information.csv`**: Records details of client payments, including payment date, amount, client ID, and method of payment.
- **`subscription_information.csv`**: Tracks subscription data such as type, start/end dates, and renewal status.
- **`industry_client_details.csv`**: Provides metadata about clients, including industry type, company size, and location.

---

## 🔍 Key Questions Answered

The script answers four core business intelligence questions:

1. **Client Distribution**:  
   How many clients are associated with the **"Finance Lending"** and **"Block Chain"** industries?

2. **Renewal Performance**:  
   Which **industry** has the **highest subscription renewal rate**?

3. **Macroeconomic Insights**:  
   What is the **average inflation rate** during periods when subscriptions were renewed?

4. **Revenue Analysis**:  
   What is the **median amount paid each year** across all payment methods?

---

## 🚀 Features

- 📂 Merges multiple CSV files for integrated analysis  
- 📅 Converts and aligns date formats for time-based analysis  
- 📈 Computes unique client counts, renewal rates, inflation averages, and annual payment medians  
- 🛠️ Includes error handling for missing files with clear console messages  

---

## 🧰 Prerequisites

- Python 3.7+
- `pandas` library (Install via `pip install pandas`)

---

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/YashAgnihotri/Skygeni_Client-subscription-analysis

# Navigate to the project directory
cd path/to/Skygeni_financial-industry-analysis

# Install required packages
pip install pandas
```

Ensure all CSV files are placed in the root project directory:
- `financial_information.csv`
- `payment_information.csv`
- `subscription_information.csv`
- `industry_client_details.csv`

---

## 🛠️ Usage

1. Open the script file (e.g., `financial_analysis.py`)
2. Update the `file_paths` dictionary if your files are located elsewhere
3. Run the script:

```bash
python financial_analysis.py
```

---

## 📤 Example Output

```
Number of Finance Lending and Block Chain clients: 25
Industry with highest renewal rate: Block Chain with rate 75.00%
Average inflation rate during renewed subscriptions: 4.50%
Median amount paid each year:
Year 2018: $250.00
Year 2019: $300.00
Year 2020: $275.00
Year 2021: $290.00
Year 2022: $280.00
```

---

## 📝 Notes

- The script assumes the following date formats:
  - `'YYYY-MM-DD'` for financial and subscription data
  - `'M/D/YYYY'` for payment data
- If any CSV file is missing or misnamed, the script will display an informative error message.
- You may need to modify file paths based on your directory structure.

---

## 🤝 Contributing

Contributions are welcome!  
Feel free to fork the repo and submit a pull request with improvements, new features, or bug fixes.
