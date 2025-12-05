# EMI-Calculator
Java EMI Calculator App

# 📄 EMI Calculator – Java Console Application

This Java program calculates the **Equated Monthly Installment (EMI)** for a loan based on three user inputs:

* **Loan Amount (Principal)**
* **Annual Interest Rate (in %)**
* **Loan Tenure (in years)**

It uses the standard EMI calculation formula and prints the monthly installment amount.

---

## 🚀 Features

* Interactive console-based input
* Automatically converts annual interest rate to monthly rate
* Supports any loan amount, interest rate, or tenure
* Implements the standard EMI formula

---

## 🧮 How It Works

The EMI is calculated using the formula:

[
\text{EMI} = \frac{P \cdot r \cdot (1+r)^n}{(1+r)^n - 1}
]

Where:

* **P** = Principal loan amount
* **r** = Monthly interest rate (annual rate ÷ 12 ÷ 100)
* **n** = Loan tenure in months

---

## 📂 Project Structure

```
src/
└── day4/
    └── EMICalculator.java
```

---

## ▶️ Running the Program

1. Make sure you have **Java 8+** installed.

2. Compile the program:

   ```bash
   javac day4/EMICalculator.java
   ```

3. Run it:

   ```bash
   java day4.EMICalculator
   ```

4. Enter the required details when prompted:

   * Loan amount in USD
   * Annual interest rate
   * Loan tenure in years

The program will output your **monthly EMI**.

---

## 📘 Example

```
Enter loan amount in USD
50000
Enter annual interest rate (in %)
7.5
Enter loan tenure in years
10
Your monthly EMI is: 593.51
```

---

## 💡 Notes

* Interest rate must be provided in **percentage**, not decimal.
* Make sure all inputs are numeric to avoid input errors.

---


Just let me know!
