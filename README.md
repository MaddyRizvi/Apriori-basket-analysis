# Apriori Algorithm – Market Basket Optimization 🛒

This project implements the **Apriori algorithm** for **Association Rule Learning** on a retail dataset to identify patterns in customer purchases. The output is a list of frequent itemsets and strong association rules that can help in optimizing product placements and recommendations. **This project can be easily adapted to work with other datasets** containing different or additional independent variables.

---

## 📌 Project Overview

- **Algorithm Used**: Apriori (via the `apyori` package)
- **Goal**: Discover relationships between products frequently bought together
- **Tech Stack**: Python, Pandas, Apyori, Matplotlib

---

## Displaying the results sorted by descending lifts

![Image](https://github.com/user-attachments/assets/48217e8d-083c-4b34-b196-0dfe079c3109)

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/MaddyRizvi/Apriori-basket-analysis.git
cd Apriori-basket-analysis
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

Or install individually:

```bash
pip install apyori pandas matplotlib numpy
```

### 3. Run the Script

Make sure your dataset is in the correct format, then run:

```bash
python apriori.py
```

---

## 📁 Repository Structure

- `apriori.py` – Main script to execute Apriori on transaction data
- `Market_Basket_Optimisation.csv` – Input dataset (if provided)
- `README.md` – Project overview and setup instructions
- `CONTRIBUTING.md` – Guidelines for contributors

---

## 📜 License

This project is licensed under the MIT License.

---

## 🤝 Contributions

Contributions are welcome! Please refer to the [CONTRIBUTING.md](./CONTRIBUTING.md) file for more details.
