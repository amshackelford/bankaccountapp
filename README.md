## **Bank Account App** ##

This is a small project that handles the creation of new customer bank account requests based on data from a spreadhseet (NewBankAccounts.cvs). Savings or Checking accounts are created, and both accounts have the ability deposit, withdraw, transfer, print balance and show basic info along with class specific funtionality.

#### **Classes** #####
* BankAccountApp - contains main method, reads data from file and puts into string array list.
* Account - contains methods and fields for accounts(checking and savings).
* Checking - contains fields related only to checking accounts, overrides/adds to inherited methods.
* Savings - contains fields related only to checking accounts, overrides/adds to inherited methods.
* IBaseRate - provides Base Interest Rate
* CSV - defines method for reading CSV file and returning list
