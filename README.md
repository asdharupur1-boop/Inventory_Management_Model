# Inventory_Management_Model
 (Benefit-focused): A sales forecasting tool to prevent stockouts and optimize inventory. This project uses machine learning to generate lead-time-aware reorder suggestions.
# 📈 [Inventory_Management_Model]

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
 **An intelligent inventory management and sales forecasting system using Python, Pandas, and Scikit-learn.**



This application analyzes historical sales data to forecast future demand, helping businesses optimize stock levels and prevent stockouts. It uses a machine learning model to provide daily sales predictions and generates dynamic, lead-time-aware reorder recommendations.

---
## ✨ Key Features

* **Sales Forecasting:** Predicts future sales quantities on a per-product basis using a Random Forest model.
* **Dynamic Recommendations:** Intelligently suggests when and how much to reorder based on supplier lead times and safety stock.
* **Data Visualization:** Generates plots to compare historical sales against forecasted trends.
* **Interactive Data Management:** Allows users to add or update product details, including stock levels and lead times.

---
## 🔧 Tech Stack

* **Backend:** Python
* **Data Analysis:** Pandas, NumPy
* **Machine Learning:** Scikit-learn
* **Database:** SQLite
* **Plotting:** Matplotlib

---
## ⚙️ Getting Started

### Prerequisites

Make sure you have Python 3.x installed on your system.

### Installation

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/](https://github.com/asdharupur1-boop/Inventory_Management_Model.md
    ```
2.  **Navigate to the project directory:**
    ```sh
    cd [Inventory_Management_Model]
    ```
3.  **Install the required packages:**
    ```sh
    pip install -r requirements.txt
    ```
    *(Note: You'll need to create a `requirements.txt` file by running `pip freeze > requirements.txt` in your terminal.)*

---
## ▶️ Usage

To run the main application and see the forecast and recommendations, execute the main script:

```sh
python main.py
