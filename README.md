# Assignement 4: 

## Description
Debugging utility built into your IDE (integrated development environment) to fix logic errors in a program. Will also perform exception handling to anticipate and process potential errors.

## Author
Zander Santos

## Assignment
Assignment 4: Troubleshooting and Exception Handling: Programming Beyond Expected Results

## pixell_transaction_report.py
Ensure all programs are correct, accurate and use exception handling apporopriately.

## Code Modification:
Exception Modification made were:

FileNotFound - Raised when the file is not found 

Exception - Catches any additional unhandled exceptions

## Code Modification:
Data Validation Modifications made were:

Transaction Type Validation - If the value stored in transaction_type 
did not match one of the values in valid_transaction_type

Transaction Amount Validation - If the value representing the transaction amount could not be parsed to a float

## Code Modification:
Troubleshooting Modifications made were:

After reading the file, added a "next" statement to skip the first line of code so that the customerID, TransactionType and TransactionAmount would not equal the headers

In Validation 1, added an additional if statement for when the transaction type was the same to the valid data types. I also changed the "==" in both statements which was previously "if transaction_type == valid_transaction_types:" to "in" 

On line 57 under "if valid_record:", changed the elif to an if so that the program would also loop through it as well instead of skipping over it

On line 67, changed the elif, so that "withdrawal" was "withdraw" and instead of adding the transaction, it would subtract it to align with a withdraw

## Code Modification:
Troubleshooting Modifications made were:

On line 92, changed the variable from transaction_counter to transaction_count because transaction_count was the variable being used to count transactions

