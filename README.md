# Payment-application
A sales payment application that takes the user data, process them and executes the transaction if valid.All forms of error checks are there to ensure credibility.
# Table of contents
-Development environment preparation
-The card module
-The terminal module
-The server module
-The application
# How to run
You can run this project on visual studio 2022
# How to use
-You input the card data in the application and they are all verified in the card module. If any data was wrongly entered, you have to reenter
-In the terminal module,the expiry date of your card is checked along with whether the amount you want to withdraw is beyond the ATM limit or not.
-If nothing went wrong in the card and terminal module, you can proceed to the server which checks if your account is blocked or not and if you have sufficient funds,otherwise your transaction will be recorded as a failed one with the reason behind the rejection.
-If all is good, the server will save the transaction in an output file and depict the amount you withdrew from the account.
-Finally, The application will print a message showing whether the transaction failed or not.
# License
No license.

