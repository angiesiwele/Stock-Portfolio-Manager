# Stock-Portfolio-Manager
Creating a python application to help manage multiple stock portfolios. Your application should allow the user to add multiple portfolios to a collection structure, as well as multiple stocks in each portfolio. The stock options should store the number of shares owned for that specific stock.

Your application should include a class with methods to do the following:
1. Add new portfolio: adds a new portfolio to the catalogue
2. Add stock to portfolio: adds a new stock to the specified portfolio, and an initial amount of shares.
3. Buy shares: add shares to an existing stock in a portfolio. Ensure there are sufficient funds available before completing the purchase.
4. Sell shares: sell shares from an existing stock in a portfolio. Ensure that there are enough shares owned to complete the transaction.
5. Deposit money: add funds to the available balance
6. Withdraw money: deduct funds from the available balance. Ensure that the user does not overdraw.
7. Display available balance: Displays the current balance
8. Display all portfolios: List all existing portfolios
9. Display specific portfolio: Show the details of a specified portfolio.
10. The constructor method should initialize the collection of portfolios (using an appropriate data structure such as a dictionary) and set the available balance to $10,000.

Your application must also ensure that there is enough money available before buying any stock or withdrawing any funds and ensure that the balance is adjusted accordingly after each transaction. You must use error-handling techniques to handle cases of insufficient funds and insufficient number of shares.
Create a user-friendly menu for interacting with the application. The menu should be displayed repeatedly until the user chooses (exit) to exit the program.
