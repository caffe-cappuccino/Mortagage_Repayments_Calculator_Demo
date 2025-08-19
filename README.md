
# Mortgage Repayments Calculator

A simple Python-based demo application for calculating mortgage repayments.  
It allows you to input property and loan details and instantly calculates:

- Monthly repayment amount
- Total repayment over the loan term
- Total interest paid
- A payment schedule

---

## Features

- **Easy input**: Enter home value, deposit, interest rate, and loan term.
- **Instant calculation**: Shows repayment amounts and interest details.
- **Payment schedule**: See how your loan balance reduces over time.
- **Accurate formula**: Uses the standard amortization method for repayment calculation.

---

## Project Structure

```

Mortagage\_Repayments\_Calculator\_Demo/
├── app.py               # Main application logic
├── requirements.txt     # Python dependencies
└── README.md            # Project documentation

````

---

## Getting Started

### Prerequisites

- Python 3.8 or higher
- Virtual environment tool (`venv` recommended)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/jheelamH/Mortagage_Repayments_Calculator_Demo.git
   cd Mortagage_Repayments_Calculator_Demo


2. Install dependencies:

   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   pip install -r requirements.txt
   ```

---

## Usage

Run:

```bash
python app.py
```

You will be prompted to enter:

* **Home Value** — e.g., `500000`
* **Deposit** — e.g., `100000`
* **Interest Rate (in %)** — e.g., `5.50`
* **Loan Term (in years)** — e.g., `30`

---

## Example Output

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

Additionally, the **Payment Schedule** is displayed, showing principal and interest components over time.

---

## Formula Used

Monthly repayment is calculated using the standard loan amortization formula:

$$
M = P \times \frac{r(1+r)^n}{(1+r)^n - 1}
$$

Where:

* $M$ = monthly repayment
* $P$ = loan principal (home value - deposit)
* $r$ = monthly interest rate (annual rate ÷ 12 ÷ 100)
* $n$ = total number of monthly payments (years × 12)

---

## License

This project is licensed under the MIT License.

---

## Author

**Jheelam Hossain**
