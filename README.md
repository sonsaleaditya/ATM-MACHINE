
# ATM Project

This is a simple ATM simulation project implemented in Java. It allows users to create and use ATM cards, check their balance, change their ATM PIN, withdraw or deposit money, and more. The project uses basic Java concepts such as classes, objects, and collections (like `HashMap`).

## Features

- **Generate New ATM Card:** Each user can generate a new ATM card with a unique 12-digit ATM number and a default PIN.
- **Check Balance:** Users can check the balance of their account.
- **Change ATM PIN:** Users can change their ATM PIN with a simple verification process.
- **Withdraw Amount:** Users can withdraw money from their account, subject to available balance and ATM cash limit.
- **Deposit Amount:** Users can deposit money into their account.
- **ATM Cash Management:** The ATM has a total cash limit that is updated with every withdrawal and deposit.

## How to Use

1. **Generate New ATM Card:** Start by generating a new ATM card. You will be provided with a 12-digit ATM number and a default PIN (`1234`). You must change this PIN before you can access any other services.
  
2. **Use Your ATM Card:** To use your ATM card, enter the 12-digit ATM number and your PIN. If you have not yet changed the default PIN, you will be prompted to do so.

3. **Select an Option:**
    - **Check Balance:** View the current balance in your account.
    - **Change ATM PIN:** Update your PIN to a new secure number.
    - **Withdraw Amount:** Enter the amount you wish to withdraw. The system will check if the ATM has sufficient cash and if you have enough balance.
    - **Deposit Amount:** Enter the amount you wish to deposit into your account.
    - **Exit:** Exit the ATM session.

4. **Exit:** Always remember to exit after completing your transactions.

## Example

```java
1. Generate New ATM Card
   Your ATM pin is 1234
   Your ATM NO. IS 1234 5678 9012

2. Use Your ATM Card
   Enter Your ATM No.: 123456789012
   Now enter Your ATM PIN: 1234
   Please generate a new ATM PIN. You cannot access your account with this PIN.
   Enter Your new PIN: 6789
   Confirm Your new PIN: 6789
   PIN changed successfully!

   1. Check Balance
   2. Change ATM Pin
   3. Withdraw Amount
   4. Deposit Amount
   5. Exit
```

## Requirements

- **Java 8** or higher

## Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/YourUsername/ATM-Project.git
   ```

2. **Compile the Java Files:**
   ```bash
   javac ATM.java Main.java
   ```

3. **Run the Project:**
   ```bash
   java Main
   ```

## License

This project is licensed under the MIT License.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue.

## Contact

For any inquiries or feedback, please reach out to me at sonsaleaditya@gmail.com
