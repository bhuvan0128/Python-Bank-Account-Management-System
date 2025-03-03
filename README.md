# Python Bank Account Management System

## **Key Features**  

### **1. Account Management**  
- Create new accounts with the following details:  
  - **PAN Number**: Unique identifier for each account.  
  - **Account Type**: Current or Savings.  
  - **Auto-Generated Credentials**:  
    - Username and password.  
    - Unique account number.  

### **2. View Account Details**  
- Retrieve and display account information securely using:  
  - Username.  
  - Password.  
  - PAN Number.  

### **3. Transactions**  
- Perform the following operations:  
  - **Deposit**: Add funds to the account.  
  - **Withdraw**: Deduct funds (balance checks applied).  
  - **Transfer**: Move funds between two accounts within the same bank.  

### **4. Transaction History**  
- View detailed transaction logs:  
  - **Timestamp**: Exact time of the transaction.  
  - **Type**: Deposit, Withdraw, or Transfer.  
  - **Amount**: Transaction amount.  
  - **Updated Balance**: Account balance after the transaction.  

### **5. Exit Functionality**  
- Safely terminate the session after completing operations.

---

## **Technologies Used**  
- **Python**: Core programming language.  
- **Modules**:  
  - `random`: For generating credentials and account numbers.  
  - `datetime`: For transaction timestamping.
