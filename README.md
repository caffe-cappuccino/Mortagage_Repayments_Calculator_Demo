
# 🏡 Mortgage Repayments Calculator  

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)  
![License](https://img.shields.io/badge/License-MIT-pink.svg)  
![Status](https://img.shields.io/badge/Status-Demo%20Project-green.svg)  
![Made With Love](https://img.shields.io/badge/Made%20with-💖%20coffee%20%26%20code-ff69b4)  

A simple **Python demo app** that helps you figure out your mortgage repayments ✨  
Just enter your property + loan details, and it’ll instantly show you:  

- 💵 Monthly repayment amount  
- 📊 Total repayment over the loan term  
- 💸 Total interest you’ll pay  
- 📅 A neat payment schedule  

---

## 🌟 Features  

- 🔑 **Easy input**: Home value, deposit, interest rate, loan term — that’s it.  
- ⚡ **Instant results**: See repayment + interest breakdown in seconds.  
- 📉 **Payment schedule**: Watch your loan balance shrink over time.  
- 🧮 **Accurate maths**: Standard amortization formula under the hood.  

---

## 📂 Project Structure  

```

Mortgage\_Repayments\_Calculator\_Demo/
├── app.py               # Main app logic
├── requirements.txt     # Dependencies
└── README.md            # You are here

````

---

## 🚀 Getting Started  

### Prerequisites  
- Python 3.8+  
- Virtual environment tool (`venv` recommended)  

### Installation  

1. Clone the repo:  
   ```bash
   git clone https://github.com/jheelamH/Mortgage_Repayments_Calculator_Demo.git
   cd Mortgage_Repayments_Calculator_Demo
````

2. Set up environment + install deps:

   ```bash
   python -m venv venv
   source venv/bin/activate   # Windows: venv\Scripts\activate
   pip install -r requirements.txt
   ```

---

## 🖥️ Usage

Run:

```bash
python app.py
```

Enter details when asked:

* 🏠 **Home Value** — e.g., `500000`
* 💰 **Deposit** — e.g., `100000`
* 📈 **Interest Rate (%)** — e.g., `5.50`
* ⏳ **Loan Term (years)** — e.g., `30`

---

## 📋 Example

**Input:**

```
Home Value: 500000
Deposit: 100000
Interest Rate: 5.50
Loan Term: 30
```

**Output:**

```
Monthly Repayments: $2,271.16
Total Repayments: $817,616
Total Interest: $417,616
```

✨ Plus, you get a full **Payment Schedule** with principal vs. interest breakdown.

---

## 📐 Formula

The monthly repayment is calculated using the standard **loan amortization formula**:

$$
M = P \times \frac{r(1+r)^n}{(1+r)^n - 1}
$$

Where:

* `M` = monthly repayment
* `P` = principal (home value - deposit)
* `r` = monthly interest rate (annual ÷ 12 ÷ 100)
* `n` = total months (years × 12)

---

## 📜 License

MIT License — free to use, share, and tweak ✨

---

👩‍💻 *Girl-coded with coffee ☕, math 📐, and a lil’ pink aesthetic 🌸*

```

Chahe main ek **GitHub repo stats badge** (stars, forks, issues) bhi daal dun? 🌟
```
