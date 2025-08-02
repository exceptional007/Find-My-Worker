
<p align="center">
  <img src="static/photos/worker_logo.png" alt="Find My Worker Logo" width="120"/>
</p>

<h1 align="center">Find My Worker</h1>

<p align="center">
  <b>A platform to connect customers with skilled workers in your locality.</b><br>
  <i>Built with Django</i>
</p>

---

## � Introduction

**Find My Worker** is a full-stack web application designed to connect customers with skilled workers in their area. The platform streamlines the process of finding, contacting, and hiring workers for various services, making it easier for both customers and workers to interact and manage their needs.

---

## 💡 Motivation

Finding reliable workers for household or professional tasks can be challenging. This project was created to simplify that process, empower local workers, and provide customers with a trustworthy platform to find help quickly and efficiently.

---

## 🚀 Project Overview

Customers can search for workers based on their requirements, while workers can register, manage their profiles, and respond to job requests. The admin panel allows for easy management of users and requests.

---

## ✨ Features

- 🔍 **Search Workers:** Find workers by skill, location, and availability.
- 👷 **Worker Dashboard:** Workers can manage their profiles and job requests.
- 📝 **Customer Requests:** Customers can post requests and view worker profiles.
- 📸 **Profile Photos:** Workers can upload and manage their photos.
- 📊 **Admin Panel:** Manage users, workers, and requests via Django admin.
- 📱 **Responsive Design:** Works seamlessly on desktop and mobile devices.
- 🗂️ **Role-based Access:** Separate dashboards for customers, workers, and admins.
- 📨 **Contact System:** Customers can contact workers directly through the platform.

---

## 🌐 Live Demo

> [Live Demo](https://find-my-worker-fmy.vercel.app/) <!-- Replace # with your deployed URL -->

---

## 🛠️ Tech Stack

- **Backend:** Django, SQLite
- **Frontend:** HTML, CSS (custom styles), Django Templates
- **Deployment:** Vercel (see `vercel.json`)

---

## 👤 User Roles

- **Customer:** Search for workers, post requests, view worker profiles.
- **Worker:** Register, manage profile, respond to job requests.
- **Admin:** Manage users, workers, and requests via Django admin panel.

---

## 📂 Folder Structure

```text
Find_My_Worker/
│   db.sqlite3
│   manage.py
│   requirements.txt
│   vercel.json
│
├── customer/
│   ├── models.py
│   ├── views.py
│   ├── forms.py
│   ├── urls.py
│   └── templates/
│       ├── search_workers.html
│       └── worker_dashboard.html
│
├── worker/
│   ├── models.py
│   ├── views.py
│   ├── forms.py
│   ├── urls.py
│   └── templates/
│
├── Find_My_Worker/
│   ├── settings.py
│   ├── urls.py
│   └── views.py
│
├── static/
│   ├── css/
│   └── photos/
│
├── media/
│   └── photos/
│
└── templates/
    ├── about_us.html
    ├── contact_us.html
    ├── layout.html
    └── layout_2.html
```

---

## ⚙️ Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/exceptional007/Find-My-Worker.git
cd Find-My-Worker/Find_My_Worker
```

### 2. Create a Virtual Environment
```bash
python -m venv venv
venv\Scripts\activate  # On Windows
# source venv/bin/activate  # On Linux/Mac
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Apply Migrations
```bash
python manage.py migrate
```

### 5. Run the Development Server
```bash
python manage.py runserver
```

### 6. Access the App
Open your browser and go to [http://127.0.0.1:8000/](http://127.0.0.1:8000/)

---

## 🖼️ Screenshots

<p align="center">
  <img src="static/photos/FIND MY WORKER.png" alt="Home Page" width="400"/>
  <img src="static/photos/worker_logo.png" alt="Worker Logo" width="200"/>
</p>

---

## 📚 API Endpoints (Sample)


| Endpoint                | Method | Description                       |
|-------------------------|--------|-----------------------------------|
| `/`                     | GET    | Home page                         |
| `/customer/search/`     | GET    | Search for workers                |
| `/worker/dashboard/`    | GET    | Worker dashboard                  |
| `/admin/`               | GET    | Django admin panel                |

---

## ❓ FAQ

**Q: How do I register as a worker?**

A: Go to the registration page and select the worker option. Fill in your details and submit the form.

**Q: How can I contact a worker?**

A: Use the search feature to find a worker and use the provided contact options on their profile.

**Q: How do I contribute to this project?**

A: Fork the repository, make your changes, and submit a pull request.

---

## 🤝 Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙏 Acknowledgements

- [Django Documentation](https://docs.djangoproject.com/)
- [Vercel](https://vercel.com/)
- [Font Awesome](https://fontawesome.com/)
- All contributors and open-source libraries used

---

## 📬 Contact

- **Author:** Akshhat Srivastava
- **GitHub:** [exceptional007](https://github.com/exceptional007)
- **Email:** akshhatsri7843@gmail.com

---

<p align="center">
  <b>Made with ❤️ using Django</b>
</p>

---


