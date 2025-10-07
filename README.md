# 💱 Currency Converter

A simple **Python-based Currency Converter** that uses the [Frankfurter API](https://www.frankfurter.app/) to convert amounts between different world currencies in real time.

---

## 🚀 Features

- 🌍 Converts between any two currencies (e.g., USD → EUR, GBP → NGN)
- ⚡ Real-time exchange rates using the **Frankfurter API**
- 💬 Simple command-line interface for user input
- 🧠 Automatically handles different currencies and amounts

---

## 🧩 How It Works

The program:
1. Prompts the user to enter:
   - The currency to convert **from** (e.g., `USD`)
   - The currency to convert **to** (e.g., `EUR`)
   - The **amount** to convert
2. Fetches the latest exchange rate data from the **Frankfurter API**
3. Displays the converted amount instantly in the terminal

---

## 🛠️ Technologies Used

- **Python 3**
- **Requests Library**
- **Frankfurter API**

---

## ⚙️ Installation & Usage

### 1️⃣ Clone the repository
```bash
git clone https://github.com/adelana107/currency-converter.git
cd currency-converter
2️⃣ Install dependencies
Make sure you have the requests library installed:

bash

pip install requests
3️⃣ Run the converter
bash

python converter.py
4️⃣ Example Output
sql

Enter in the currency you'd like to convert from: USD
Enter in the currency you'd like to convert to: EUR
Enter the amount of money: 100

https://api.frankfurter.app/latest?amount=100&from=USD&to=EUR
100 USD is 91.24 EUR
🧠 What I Learned
How to interact with REST APIs in Python using the requests library

How to handle user input and dynamic URLs

How to parse JSON responses from APIs

How to build quick, functional CLI-based utilities

🧑‍💻 Author
Adelana Oluwafunmibi
Backend Engineer | Python | Django | REST APIs
🛰️ Orbiting around good ideas
📧 adelana787898@gmail.com
🔗 GitHub Profile
