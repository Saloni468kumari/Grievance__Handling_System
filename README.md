
# 📢 Grievance Handling System

A **full-stack Django-based web application** designed to streamline the submission, tracking, escalation, and resolution of grievances within any organization. This system features role-based access, real-time grievance updates, feedback collection, analytics visualization, and report generation.

---

## 🚀 Features

- 📝 **Grievance Submission** – Easy submission process for users.
- 👥 **Role-Based Dashboards** – Separate interfaces for Admin, Employee, and Customer.
- ⚙️ **Admin Control Panel** – Assign grievances to departments and employees.
- ⏱️ **Automatic Escalation** – Unresolved grievances are escalated after 2 days.
- ⭐ **Feedback Mechanism** – Customers can submit ratings and comments post-resolution.
- 📊 **Data Visualization** – Insightful charts using Chart.js for tracking performance.
- 📄 **Filtered Reports & CSV Export** – Efficient report generation for Admin users.

---

## 🔧 Tech Stack

- **Backend:** Django, Python  
- **Frontend:** HTML5, CSS3, Bootstrap 5, JavaScript  
- **Database:** SQLite3 (can be upgraded to MySQL/PostgreSQL)  
- **Charts & Analytics:** Chart.js  
- **Version Control:** Git, GitHub  
- **Development Environment:** Visual Studio Code  

---

## ⚙️ Setup Instructions

> ✅ Make sure you have **Python (3.10+)**, **Django 5.1+**, and optionally **MySQL** installed.

### 1. Clone the Repository

```bash
git clone https://github.com/singh-gaurav04/Grievance__Handling_System.git
cd Grievance__Handling_System/grievance_system
```

### 2. Create & Activate Virtual Environment (Optional but recommended)

```bash
python -m venv venv
venv\Scripts\activate   # For Windows
# source venv/bin/activate  # For macOS/Linux
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

```bash
pip install django djangorestframework django-cors-headers
```

### 4. Run Development Server

```bash
python manage.py runserver
```

---

## 🔐 Default Credentials & Roles

- ✅ **Admin Login**
  - **Username:** `Admin`
  - **Password:** `1234pass`
- ✅ **Create Users**
  - Customers and Employees can be created from the app.
  - Admins can register new Admins via:  
    [http://127.0.0.1:8000/register-admin](http://127.0.0.1:8000/register-admin) *(when logged in as an admin)*

---

## 📸 Demo Screenshots

> Replace the following links with updated ones from your GitHub repository.

- **Login Page**  
  ![Login](https://github.com/user-attachments/assets/093e7f9b-17f4-4216-9ae8-a71ecedc1e9a)

- **Customer - Grievance Submission**  
  ![Customer Submission](https://github.com/user-attachments/assets/9b300803-369c-4f2b-9773-0241230d5a79)

- **Admin - Dashboard View**  
  ![Admin Dashboard](https://github.com/user-attachments/assets/f7149b53-069e-4e85-958e-abdf4a0a8757)

- **Admin - Grievance Table**  
  ![Grievance Table](https://github.com/user-attachments/assets/090a2ee2-0cf9-4a39-af71-3c0134a5ab00)

---

## 🙌 Acknowledgements

- [Django Documentation](https://docs.djangoproject.com/)
- [Bootstrap](https://getbootstrap.com/)
- [Chart.js](https://www.chartjs.org/)
