# Password Strength Checker

📌 Overview
This is a simple Python tool that checks the strength of a password based on multiple criteria such as:
- Length of the password
- Use of uppercase and lowercase letters
- Presence of numbers and special characters
- Avoiding common passwords and predictable sequences

It is meant for learning purposes and should not be used as a replacement for professional security tools.

🛠 Tech Stack
- Python 3
- Regular Expressions (`re` module)
  
🚀 How It Works
1. Input: User enters a password.
2. Checks performed:
   - Password length
   - Contains lowercase letters
   - Contains uppercase letters
   - Contains numbers
   - Contains special characters
   - Not a common password
   - No simple sequences or repeated characters
3. Scoring: The password gets a score from `0` to `10`.
4. Output:Displays the score, rating, passed checks, and improvement suggestio

▶️ How to Run
1. Install Python 3 if not already installed.
2. Save the script as `password_strength_checker.py`.
3. Open a terminal or PyCharm and run:
   ```bash
   python password_strength_checker.py
Enter a password when prompted.

💡 Example Output
markdown
Copy
Edit
Simple Password Strength Checker
--------------------------------
Enter a password to check: Hello123

=== Password Strength Report ===
Password: ********
Score   : 6 / 10
Rating  : Fair

✔ Passed:
  - Length ≥ 8
  - Has lowercase
  - Has uppercase
  - Has numbers
  - Not a common password

✘ Suggestions:
  - Add special characters (e.g., ! @ # $ % & *).
  - Make it longer (aim for 12+ characters).
    
📚 What I Learned
How to use regular expressions in Python for pattern matching.
How to check strings for different character types.
How to create scoring logic for security assessment.
How to give user-friendly feedback.

⚠️ Disclaimer
This project is for educational purposes only and is not suitable for real-world password security enforcement.
