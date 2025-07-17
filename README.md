
# 📈 Stock Trading Simulation in Java

This is a simple console-based **stock trading simulation** program written in Java. It allows a user to:

* Buy and sell predefined stocks (e.g., COAL INDIA, ITC)
* View their portfolio and transaction history
* Simulate basic trading activity with a virtual balance

---

## 🧠 Features

* Basic stock trading for two companies.
* Real-time balance updates.
* Transaction history stored in memory.
* Portfolio tracking for each stock.
* Simple menu-driven CLI (Command Line Interface).

---

## 📂 File Structure

```
StockPlatform.java
```

Contains all classes:

* `Stock`: Represents a stock with symbol and price.
* `Transaction`: Represents a buy or sell action.
* `User`: Manages the user's portfolio, balance, and transaction history.
* `StockPlatform`: Main class that provides a menu for user interaction.

---

## 🛠️ How to Run

### Prerequisites

* Java Development Kit (JDK) installed
* A terminal or IDE like IntelliJ IDEA / Eclipse / VS Code

### Steps

1. **Save the file** as `StockPlatform.java`.

2. **Open terminal/command prompt**.

3. **Compile the code**:

   ```bash
   javac StockPlatform.java
   ```

4. **Run the program**:

   ```bash
   java StockPlatform
   ```

---

## 📌 Sample Usage

```
Welcome to Stock Exchange
1. Market Details 
2. Buy
3. Sell
4. Portfolio
5. Exit
```

* Buy or sell stocks by selecting options.
* View your updated balance and holdings.
* Exit anytime using option 5.

---

## 💡 Example Stocks

| Symbol     | Company    | Price (INR) |
| ---------- | ---------- | ----------- |
| COAL INDIA | Coal India | ₹383.83     |
| ITC        | ITC Ltd.   | ₹416.65     |

---

## 🔒 Disclaimer

This is a **simulation** for educational/demo purposes only. Prices are static and no real-world transactions occur.

---

## 👨‍💻 Author

**Gourab Tikadar**
Feel free to modify and extend the functionality to include real-time APIs, dynamic prices, or GUI interface.

