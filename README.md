## **Bank Account App** ##

This is a small project that creates checking or savings accounts based on data from a spreadhseet(NewBankAccounts.cvs). Both checking and savings are subclasses of accounting class. IBaseRate contains a method for getting base rate, that method is implemented to Account class and overriden in the subclasses. 

#### **Classes** #####
* BankAccountApp - contains main method, reads data from file and puts into string array list.
* Account - contains methods and fields for accounts(checking and savings).
* Checking - contains fields related only to checking accounts, overrides/adds to inherited methods.
* Savings - contains fields related only to checking accounts, overrides/adds to inherited methods.
* IBaseRate - provides Base Interest Rate
* CSV - defines method for reading CSV file and returning list
