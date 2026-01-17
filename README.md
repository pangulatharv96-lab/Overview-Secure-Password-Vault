#Secure-Password-Vault
- 📌 Project Objective
  - The goal of this project is to build a command-line based secure password vault that allows users to safely store, view, search, and validate passwords for different websites.
  - It focuses on basic security principles, Python fundamentals, and user interaction via CLI.
 
  -------------------------------

- 🛠️ Technologies Used
  - Python
  - Core Python concepts:
  - Lists & dictionaries
  - Functions
  - Loops & conditionals
  - String handling
  - Input validation
 
  ------------------------------

- ⚙️ Core Features
- 1️⃣ Add New Credentials
  - User can store:
  - Website name
  - Username
  - Password
  - Before saving, the password is validated for strength.
 
  -------------------------------------------

- 2️⃣ Password Strength Validation
  - Passwords are checked against security rules:
  - Minimum 8 characters
- At least:
  - 1 uppercase letter
  - 1 lowercase letter
  - 1 digit
  - 1 special character
- Output:
  - "Strong" → password accepted
  - "Weak" → user warned
  - This demonstrates basic security awareness.
 
  -------------------------------------

- 3️⃣ View All Stored Credentials
  - Displays all saved credentials in a readable format
  - Helps users review stored data easily
 
  -----------------------------------

- 4️⃣ Search Credentials by Website
  - User can search credentials using a website name
  - Returns matching username and password
  - Improves usability and real-world relevance
 
  -----------------------

- 5️⃣ Menu-Driven CLI Interface
  - Clean, loop-based menu:
  - 1. Add Credential
  - 2. View Credentials
  - 3. Search Credential
  - 4. Exit
  - Runs continuously until the user exits
  - Beginner-friendly and interactive
 
  -----------------------------------

- 🧠 Project Flow (How It Works)
  - Program starts → displays menu
  - User selects an option
  - Based on choice:
  - Add / View / Search credentials
  - Password is validated before storing
  - Credentials are stored in memory
  - Program exits safely on user command
 
-------------------

- ✅ Strengths of the Project
  - Practical real-world use case
  - Demonstrates security fundamentals
  - Clean separation of logic using functions
  - Beginner-friendly yet interview-relevant
  - Shows understanding of data validation
 
  -------------------------------------------------

- ⚠️ Current Limitations
  - Data is stored in-memory only (lost after program ends)
  - Passwords are stored in plain text
  - No encryption or authentication
  - Single-user support
