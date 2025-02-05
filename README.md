# Simple Bank System in Bash

## Overview

This project is a **simple banking system** implemented using **Bash scripting**. It allows clients, employees, and moderators to interact with a simulated banking environment, handling transactions and account management efficiently.

## Features

- **Client Operations:** Withdraw, deposit, check balance.
- **Employee Operations:** Perform client actions + add/delete accounts.
- **Moderator Access:** Runs the system with root privileges.
- **Data Storage:** Client details are stored securely in a text file.

## Files and Their Roles

| File Name       | Description                                                 
| --------------- | ----------------------------------------------------------- 
| `mainfile`      | Controls program flow and user role selection.              
| `clientfile`    | Handles client transactions securely.                       
| `employeefile`  | Manages client transactions and account creation/deletion.  
| `moderatorfile` | Grants admin privileges to employees.                       
| `datafile.txt`  | Stores user data in a structured format (ID\|Name\|Balance) 

## How to Run the Project

### Prerequisites

Ensure you have a **Linux environment** with **Bash** installed.

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/simple-bank-system.git
   cd Simple-Bank-DataBase-Using-bash-script
   ```
2. Grant execution permissions:
   ```bash
   chmod +x *.
   ```
3. Run the main script:
   ```bash
   ./mainfile
   ```

## Usage Instructions

1. Choose your role: **Client, Employee, or Moderator**.
2. Follow the on-screen prompts to perform transactions or account operations.
3. The system loops back to the main menu after each operation.

## Example Data Format (data.txt)

```
1000|Hossam|5000
1001|Yasser|3000
```

## Contribution

Feel free to fork this repository and enhance it with new features!


## License

This project is licensed under the **MIT License**.

