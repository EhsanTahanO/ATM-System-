# ATM System (C++)

A simple ATM console application built with C++ that simulates basic banking operations for clients.

## Features
- Login using account credentials
- Check balance
- Deposit money
- Withdraw money
- Basic input validation
- Console-based menu system

## Project Structure
```text
 .gitignore
    Clients.txt
    ConsoleApplication1.cpp
    ConsoleApplication1.vcxproj
    ConsoleApplication1.vcxproj.filters
    README.md
```

> If your current project is still in one `.cpp` file, that’s okay. You can refactor gradually.

## How to Run
1. Open the solution file in Visual Studio:
   - `ConsoleApplication1.sln`
2. Build the project (Build → Build Solution)
3. Run the program (Ctrl + F5)

## Example Use Cases
- Client logs in and checks available balance.
- Client deposits a valid amount.
- Client attempts invalid withdrawal and gets a clear error message.

## Future Improvements
- Save/load client data from file or database
- PIN retry limits and account lock
- Transaction history
- Admin panel
- Unit tests

