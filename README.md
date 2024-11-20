# MyCash

A C++-based digital wallet system for managing financial transactions securely and efficiently. Users can register, update profiles, send money, and check balances with advanced features like OTP security.

---

## Key Features of the Program

### Registration and Login:
- **Registration**: Users can register with their mobile number, name, and PIN.
- **Login**: Access is secured by a PIN-based system.

---

### File Management:
- User data is stored in `file.txt`, ensuring persistence across sessions.
- File operations are handled through methods like:
  - `FileIn`: Save new user data.
  - `FileOut`: Retrieve existing user data.
  - `UpdateFile`: Modify and update data.

---

### Account Management:
- **Update Details**: Modify personal information, including name and PIN.
- **Account Removal**: Users can delete their accounts after verifying with an OTP.

---

### Transactions:
- **Send Money**: Transfer funds to another registered user securely.
- **Cash-In and Cash-Out**: Add or withdraw funds from the user's account.

---

### OTP Security:
- A one-time password (OTP) is generated for sensitive operations, including:
  - PIN changes.
  - Sending money.
  - Cash withdrawals.
- OTPs are time-limited, providing enhanced security for users.

---

### Transaction History:
- Comprehensive records of all transactions are maintained, including:
  - **Transaction ID**: Unique identifier for each transaction.
  - **Description**: Details of the operation.
  - **Updated Balances**: Reflects changes post-transaction.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/srshadiq/Assignment/
