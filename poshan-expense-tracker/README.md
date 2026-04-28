# 🌐 Expense Tracker System (PM POSHAN)

A full-stack web application to digitize and streamline bill submission, approval, and expense tracking for organizations under the PM POSHAN scheme.

---

## 📌 Key Highlights

- 🔐 Role-based Authentication (Admin & User)
- 🧾 Digital Bill Submission & Approval Workflow
- 📊 Expense Tracking System
- 🏢 Organization Management
- 📑 Report Generation (PDF / CSV / Excel)
- 🔔 Real-time Notifications
- ⚡ Scalable and efficient system design

---

## 🧠 Problem Statement

Traditional bill and expense management systems are manual, time-consuming, and prone to errors.  
There is a lack of transparency and difficulty in tracking financial records.

This system provides a centralized digital solution to:
- Improve efficiency  
- Ensure accuracy  
- Enable real-time tracking  
- Reduce manual workload  

---

## 🏗️ System Architecture

Frontend (HTML/CSS/JS)  
⬇  
API Layer (JavaScript - Fetch/AJAX)  
⬇  
Backend (Django + Django REST Framework)  
⬇  
Database (SQLite / MySQL / PostgreSQL)

---

## 🛠️ Tech Stack

| Layer        | Technology                     |
|-------------|------------------------------|
| Frontend    | HTML, CSS, JavaScript        |
| Backend     | Django, Django REST Framework|
| Database    | SQLite / MySQL / PostgreSQL  |
| API Handling| JavaScript (Fetch / AJAX)    |
| Version Ctrl| Git & GitHub                 |

---

## ⚙️ Installation

```bash
# Clone repository
git clone https://github.com/Asmita-Rathod/pm-poshan-expense-tracker.git

# Navigate into project
cd pm-poshan-expense-tracker

# Create virtual environment
python -m venv venv

# Activate environment
venv\Scripts\activate   # Windows

# Install dependencies
pip install -r requirements.txt

# Apply migrations
python manage.py migrate

# Run server
python manage.py runserver

Now open your browser:
http://127.0.0.1:8000/
---
#📂 Project Structure
```bash
poshan-expense-tracker/
│── bills/              # Bill management module
│── users/              # Authentication & user roles
│── templates/          # HTML templates
│── static/             # CSS, JS, assets
│── api.js              # Frontend API integration
│── manage.py
```
👥 User Roles  
👤 User
Submit bills  
View bill status  
Track expenses  
Receive notifications    
🛠️ Admin
Approve / Reject bills  
Manage organizations  
Allocate grants  
Generate reports  

🔄 Workflow  
User submits bill
        ↓
Admin reviews bill
        ↓
Approved / Rejected
        ↓
User gets notified

📊 Features Breakdown
| Feature          | Description                     |
| ---------------- | ------------------------------- |
| Authentication   | Secure login/signup system      |
| Bill Management  | Submit, update, track bills     |
| Approval System  | Admin-controlled workflow       |
| Expense Tracking | Record & monitor expenses       |
| Reports          | Export data in multiple formats |
| Notifications    | Real-time updates               |


📸 Screenshots

Login Page : <br>
<img src="https://github.com/user-attachments/assets/ecff8a99-b3b8-41aa-bce7-1fd68e534bde" width="400" height="200"/><br>
<b>USER PANEL</b><br>
User Dashboard : <br>
<img src="https://github.com/user-attachments/assets/295f2802-63e2-450b-9022-36abda498860" width="500"/> <br>
Bill Submission Page :<br>
<img width="500" alt="image" src="https://github.com/user-attachments/assets/2e7f4aa3-6052-47ae-bab7-8537f5859957" /><br>
Expense Entry page :<br>
<img width="500" alt="image" src="https://github.com/user-attachments/assets/30dda710-832b-4ef7-a27d-b6e49d67b29d" /><br>


<br><b>ADMIN PANEL:</b><br>
Admin dashborard:<br>
<img src="https://github.com/user-attachments/assets/bc0b4712-5a77-49cb-81be-a749e7a266a3" width="500" /><br>
Bill Approval:<br>
<img width="500" alt="image" src="https://github.com/user-attachments/assets/86db3844-98fa-4080-b740-d690b1eaed9f" /><br>
Manage Organizations:<br>
<img width="500" alt="image" src="https://github.com/user-attachments/assets/f243be8c-9d40-4088-a8f0-7be523571079" /><br>
Generate Reports :<br>
<img width="500" alt="image" src="https://github.com/user-attachments/assets/b6dfccbd-a13d-4ecb-8eb1-36304723b73c" /><br>


🚀 Future Enhancements
📈 Analytics Dashboard (Charts & Graphs)  
📱 Mobile App Version  
📧 Email & SMS Notifications  
🔐 Advanced Role Permissions  
☁️ Cloud Deployment  

🧪 How to Test  
Register as a user  
Submit a bill  
Login as admin  
Approve/reject the bill  
Check updated status  

🤝 Contribution  

Contributions are welcome!  
Feel free to fork this repository and submit a pull request.  

👩‍💻 Author  

Asmita Rathod 
B.E. IT Student  

⭐ Support  

If you found this project useful:  

⭐ Star this repository  
🍴 Fork it  
