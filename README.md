# ☕ Python Coffee Machine OOP Project

Welcome to the **Python Coffee Machine** — a command-line simulation of a real-world coffee vending machine, built with the power of **Object-Oriented Programming (OOP)** in Python!

---

## 📌 Overview

This project models a coffee machine that can:

* Serve different types of coffee (Espresso, Latte, Cappuccino)
* Manage ingredient resources (water, milk, coffee)
* Handle monetary transactions
* Report current resource status

It’s a great beginner-to-intermediate level Python project to practice **classes**, **encapsulation**, **inheritance**, and **clean code design**.

---

## 🧠 Concepts Covered

* Object-Oriented Design
* Class Abstraction and Responsibilities
* Instance Attributes and Methods
* Real-world Simulation
* Python Dictionaries & Input Handling

---

## 🎮 How to Play

1. Run the program from your terminal.
2. You'll be prompted to choose a drink: `espresso`, `latte`, or `cappuccino`.
3. The machine will:

   * Check if enough resources are available.
   * Process coin input and handle the transaction.
   * Make the coffee and deduct ingredients.
4. You can also enter:

   * `report` — to see remaining resources.
   * `off` — to shut down the machine.

---

## 💻 Example Output

```
What would you like? (espresso/latte/cappuccino): latte
Please insert coins.
How many quarters?: 4
How many dimes?: 0
How many nickels?: 0
How many pennies?: 0
Here is $1.00 in change.
Here is your latte ☕. Enjoy!
```

---

## 🏗️ Project Structure

```
coffee_machine/
├── coffee_maker.py       # Manages the machine's resource and coffee making
├── menu.py               # Contains MenuItem and Menu classes
├── money_machine.py      # Handles coin processing and transactions
└── main.py               # Runs the program loop
```

---

## 🧩 Classes Breakdown

### `MenuItem`

Represents a single coffee item (e.g., Latte) with ingredients and cost.

### `Menu`

Manages the coffee menu and returns available options.

### `CoffeeMaker`

Handles checking resources and making coffee.

### `MoneyMachine`

Deals with inserting coins, calculating totals, and managing profits.

---

## 🧪 Example Menu

| Drink      | Water (ml) | Milk (ml) | Coffee (g) | Cost (\$) |
| ---------- | ---------- | --------- | ---------- | --------- |
| Espresso   | 50         | 0         | 18         | 1.50      |
| Latte      | 200        | 150       | 24         | 2.50      |
| Cappuccino | 250        | 100       | 24         | 3.00      |

---

## ✅ Features

* Interactive CLI interface
* Clean OOP design
* Resource tracking and updates
* Realistic coin handling
* Clear user prompts and feedback

---

## 🚀 Getting Started

### Requirements:

* Python 3.x

### Run the Program:

```bash
python main.py
```

---

## 📚 Learning Resource

This project is inspired by **Angela Yu's 100 Days of Code** course on Udemy. A perfect practice if you're learning Python OOP!

---

## 📌 Author

Made with ☕ by [Arnab Mandal]

---

## ⭐️ Star the Repo

If you found this project helpful, consider giving it a ⭐️ on GitHub!

---

Would you like me to generate the code files (`coffee_maker.py`, `menu.py`, `money_machine.py`, `main.py`) as well?
