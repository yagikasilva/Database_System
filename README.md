📚 Database System GUI with CustomTkinter
This project is a simple Database Management System built using Python, CustomTkinter, Tkinter, and Openpyxl for managing basic student and personal details.

It features a modern, scrollable GUI where users can input and store data into an Excel file (password.xlsx) and view the entered records.

✨ Features
📋 Two Tabs: Students and Personal Details

🧾 Save student names and grades to an Excel sheet

🧑‍💼 Save personal details like gender, age, and telephone number

📈 Display all records inside a scrollable frame

✅ Automatically update Excel file with new entries

❌ Close button to safely exit

📂 Project Structure
bash
Copy
Edit
├── databaseimage.ico   # App icon
├── password.xlsx       # Excel file where data is stored
├── main.py             # Main Python script (your code)
└── README.md           # This file
🚀 Installation
Clone the Repository

bash
Copy
Edit
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
Install Required Packages

bash
Copy
Edit
pip install customtkinter openpyxl
Make sure you have:

A password.xlsx Excel file with at least a sheet named Sheet4

An icon file databaseimage.ico for the app (or you can comment out the icon line if not needed)

Run the application

bash
Copy
Edit
python main.py
🛠 Requirements
Python 3.8+

CustomTkinter

openpyxl

tkinter (comes pre-installed with Python)

📸 Screenshots

Student Details Tab	Personal Details Tab
(Optional: Add screenshots to show the UI in action)

⚡ How It Works
Enter Student Name and Grade → Click Upload → Data is saved and displayed.

Enter Personal Details → Click Upload → Data is saved and displayed with additional fields.

All data is appended into the Excel file password.xlsx.

📢 Notes
Make sure the Excel file password.xlsx exists and contains a sheet called Sheet4 before running the app.

When switching between tabs, the form fields reset.


🙌 Acknowledgements
CustomTkinter

openpyxl Documentation

