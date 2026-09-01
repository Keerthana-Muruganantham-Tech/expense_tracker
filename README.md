Expense Tracker

A simple Python Expense Tracker that allows users to enter their expenses and calculates the total amount spent.

Features

- Enter multiple expenses
- Accepts decimal values
- Type "done" to finish entering expenses
- Automatically calculates the total amount spent
- Simple command-line interface

Technologies Used

- Python

How It Works

1. The program starts with the total expense as "0".
2. The user enters an expense amount.
3. The entered amount is converted into a floating-point number.
4. Each expense is added to the total.
5. The user can type "done" to stop entering expenses.
6. The program displays the total amount spent.

Code

total = 0

while True:
    expense = input("Enter an expense (or type 'done' to finish): ")

    if expense.lower() == "done":
        break

    total = total + float(expense)

print("Total Spent:", total)

Example

Enter an expense (or type 'done' to finish): 100
Enter an expense (or type 'done' to finish): 250.50
Enter an expense (or type 'done' to finish): 75
Enter an expense (or type 'done' to finish): done

Total Spent: 425.5

Future Improvements

- Add expense categories
- Store expenses in a file or database
- Display daily and monthly expenses
- Add a graphical user interface (GUI)
- Generate expense reports# expense_tracker
Expense tracker
