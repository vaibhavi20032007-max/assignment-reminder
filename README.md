# assignment-reminder
# Smart Reminder for Assignments

The *Smart Reminder for Assignments* is a simple Python-based project designed to help students manage their academic workload by tracking assignment deadlines and notifying them when a deadline is approaching.

## 🔥 Features
- Add assignments with a title, description, and deadline
- View all upcoming assignments
- Automatic reminder for assignments due within 24 hours
- Persistent data storage using JSON
- User-friendly menu-based interface

## 📂 Project Structure

📁 SmartReminder
│── main.py
│── assignments.json
│── README.md


## 🛠 Technologies Used
- *Python 3*
- *JSON* for data storage
- *datetime module* for time calculations

## ▶️ How to Run
1. Install Python 3
2. Download or clone the repository:

git clone <repository_link>

3. Navigate into the project folder:

cd SmartReminder

4. Run the program:

python main.py


## 📘 How It Works
- The user enters assignment details including a *deadline*.
- The data is stored in assignments.json.
- When the user checks reminders, the program compares deadlines with the current time.
- If a deadline is within 24 hours or overdue, the user receives an alert.

## 🧩 Future Enhancements
- Add a GUI using Tkinter or PyQt
- Email/WhatsApp/SMS notifications
- Priority-based sorting
- Repeat reminders feature

## 📜 License
This project is free for educational and academic use.
