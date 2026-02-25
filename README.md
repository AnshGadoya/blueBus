<img width="602" height="338" alt="image" src="https://github.com/user-attachments/assets/2205b17d-583a-4d00-bff8-207458d46664" /># 🚌 BlueBus – Online Bus Ticket Booking System

## 📌 Overview

**BlueBus** is a modern web-based bus ticket booking system developed using **Python (Django)** and **MySQL**.
It provides a seamless booking experience with advanced features like **QR-based payments, smart seat selection, and automated email ticket generation**.

---

## 🚀 Features

### 👤 User Features

* 🔍 **Advanced Search System** (source, destination, date-based filtering)
* 🪑 **Interactive Seat Layout** for real-time seat selection
* 🎟️ Easy and fast ticket booking
* 💳 **QR Code Payment System (Scan & Pay)**
* 📧 **Automatic Email Ticket after Successful Payment**
* 📄 View booking history
* 🔐 Secure authentication (Login / Register)

### 🛠️ Admin Features

* ➕ Add / Update / Delete buses
* 🗺️ Manage routes and schedules
* 👥 Manage users
* 📊 View and manage all bookings
* 💰 Track transactions and payments

---

## 💡 Key Highlights

* ⚡ Smooth and modern UI/UX
* 🧾 Instant ticket generation system
* 🔄 Real-time seat availability updates
* 📱 Responsive design
* 🔐 Secure booking & payment flow

---

## 🧑‍💻 Tech Stack

* **Frontend:** HTML, CSS, JavaScript
* **Backend:** Python (Django Framework)
* **Database:** MySQL
* **Version Control:** Git & GitHub

---

## 📁 Project Structure

```
BlueBus/
│── manage.py
│── db.sqlite3 / MySQL DB
│── BlueBus/
│   ├── settings.py
│   ├── urls.py
│   └── ...
│
│── booking/
│── users/
│── buses/
│── templates/
│── static/
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/bluebus.git
cd bluebus
```

### 2️⃣ Create Virtual Environment

```bash
python -m venv venv
source venv/bin/activate   # for Linux/Mac
venv\Scripts\activate      # for Windows
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Configure Database (MySQL)

Update your `settings.py`:

```python
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': 'bluebus_db',
        'USER': 'root',
        'PASSWORD': 'your_password',
        'HOST': 'localhost',
        'PORT': '3306',
    }
}
```

### 5️⃣ Run Migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### 6️⃣ Create Superuser

```bash
python manage.py createsuperuser
```

### 7️⃣ Run the Server

```bash
python manage.py runserver
```

Open in browser:

```
http://127.0.0.1:8000/
```

---

## 📸 Screenshots

*(Comming Soon)*

---

## 🔮 Future Enhancements

* 📍 Live bus tracking
* 📱 Mobile app version (Flutter)
* 📧 SMS notifications
* ⭐ User reviews & ratings
* 🎯 AI-based seat recommendation

---
