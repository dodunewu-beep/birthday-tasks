🎂 Birthday Wisher
Overview

Birthday Wisher is a Python automation project designed to ensure birthdays are never missed. It checks a list of birthdays, creates a personalised message, and automatically sends it by email.

Key Features
📅 Checks birthdays against today's date
🎲 Randomly selects a birthday message template
✏️ Personalises the message with the recipient's name
📧 Automatically sends the message by email
⚡ Reduces manual effort and improves consistency
How It Works
Birthday information is stored in birthdays.csv.
The system checks whether anyone has a birthday today.
A random message template is selected.
The recipient's name is added to the message.
The personalised birthday message is sent by email.
Project Structure
birthday-wisher/
├── main.py
├── birthdays.csv
├── letter_1.txt
├── letter_2.txt
├── letter_3.txt
└── README.md

Technology
Python
Pandas – Birthday data processing
datetime – Date checking
random – Message selection
smtplib – Email delivery
Setup

Install the required dependency:

pip install pandas


Add birthday details to birthdays.csv:

name,email,year,month,day
John Doe,john@example.com,1995,9,8


Message templates should include the [NAME] placeholder:

Happy Birthday [NAME]!

Wishing you a wonderful birthday! 🎉


Run the application with:

python main.py

Security

Email credentials should not be stored directly in the source code or committed to GitHub. Environment variables or a Gmail App Password should be used for secure authentication.

Future Development
🔐 Secure credential management
📆 Automated daily scheduling
💌 Additional message templates
🖼️ HTML emails and images
⚠️ Improved error handling
📧 Support for multiple recipients
Outcome

The project demonstrates how simple automation can reduce repetitive tasks, improve reliability, and provide a personalised experience with minimal manual intervention.

⭐ A practical Python automation project for personalised birthday communication.

Contributions and suggestions are welcome!

Fork the repository.
Create a new branch.
Make your changes.
Commit your changes.
Push the branch.
Open a Pull Request.
📜 License

This project is available for educational and personal use. Add your preferred open-source license here, such as the MIT License.

⭐ If you found this project useful, consider giving the repository a star!
