# Banking Fraud Detection System (ShieldAI Radar)

A real-time banking and payment fraud detection web application built using **Python**, **Streamlit**, and **SQLite**. This project simulates payment API requests and analyzes transaction risk scores, device fingerprints, and location anomalies to detect fraudulent activity.

## Key Features
* **Real-Time Payment Simulation:** Test transactions across UPI, IMPS, NetBanking, and Credit Cards.
* **Risk Scoring & Signals:** Evaluates transaction amount, time, unrecognized device fingerprints, and KYC vs. GPS origin city mismatches.
* **Database Integration:** Stores and tracks transaction records using SQLite (`.db`).

## Technologies Used
* **Frontend & App Framework:** Streamlit
* **Backend:** Python
* **Database:** SQLite3

## How to Run Locally
1. Clone this repository:
   ```bash
   git clone https://github.com
   ```
2. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```
