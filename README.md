**#Interest Calculation**
This Java console application calculates the Recurring Deposit (RD) maturity amount for a bank account.
It accepts user inputs—principal amount, tenure (5 or 10 years), age, and gender—and:
        Validates the inputs using a custom exception (BankValidationException).
        Determines the applicable interest rate based on the customer’s age and gender.
        Computes the total amount deposited, the interest earned, and the final maturity amount.
The project demonstrates Java concepts such as abstract classes, method overriding, custom exceptions, and user input handling.

**#Project Structure**
src/
├─ com/wipro/bank/exception/
│ └─ BankValidationException.java
├─ com/wipro/bank/acc/
│ ├─ Account.java
│ └─ RDAccount.java
├─ com/wipro/bank/service/
│ └─ BankService.java
└─ com/wipro/bank/main/
└─ Mainclass.java
