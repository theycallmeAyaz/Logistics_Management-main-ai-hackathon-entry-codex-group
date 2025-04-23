# 🚛 SmartLog – AI Logistics Dashboard

**SmartLog** is a logistics management system developed for the  
**DAFZ AI WEEK – AI Innovation Forum 2025**  
👥 Team Members: Ali, Hasan, Murtaza, Ayaz

---

## 🔹 What It Does
- Role-based dashboard for **Managers**, **Customers**, and **Delivery Agents**
- Real-time shipment tracking and assignment
- Delay reporting and delivery confirmation with photo proof
- Email notifications for key events

---

## 🔹 Tech Stack
- **Backend:** Flask (Python)
- **Database:** SQLAlchemy + SQLite
- **Auth:** Flask-Login
- **Frontend:** REST API-ready for integration

---

## 🔹 Key Features
- 📦 Assign & manage shipments  
- 📍 Track deliveries in real-time  
- 🧾 Upload proof of delivery (photo + timestamp)  
- 📬 Notify users via email  
- 🔒 Secure role-based login

---

## 🔹 Installation Guide
```bash
git clone https://github.com/your-team/smartlog.git
cd smartlog
python -m venv venv
source venv/bin/activate         # Windows: venv\Scripts\activate
pip install -r requirements.txt
```

---

## 🔹 Setup
```bash
# Environment variables
export EMAIL='your-email@gmail.com'
export PASSWORD='your-email-password'

# Initialize database
flask shell
from app import db
db.create_all()
exit()

# Run app
flask run
```

---

## 🔹 Access Roles
- **Manager:** Assign shipments, view status, manage agents
- **Customer:** Track packages, report issues, view proof of delivery
- **Delivery Agent:** Mark completed deliveries, upload photos
