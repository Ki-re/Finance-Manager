<div align="center">
  <img src="logo.png" alt="logo" width="200" height="auto" />
  <h1>Personal Finance Manager</h1>
  
  <p>
    A Django-based web application to efficiently manage personal finances.
  </p>
  
<h4>
    <a href="https://github.com/Ki-re/Finance-Manager/issues/">Report a Bug</a>
  <span> · </span>
    <a href="https://github.com/Ki-re/Finance-Manager/issues/">Request a Feature</a>
  <span> · </span>
    <a href="https://github.com/Ki-re/Finance-Manager/pulls">Contribute</a>
  </h4>
</div>

<br />

## 🚀 About the Project

Personal Finance Manager is a web application that helps users keep track of their income and expenses easily. With an intuitive interface and financial insights, it assists users in improving their financial management.

### ✨ Features
- User authentication and account management.
- Add income and expenses with custom categories.
- Filter transactions by date, type, and category.
- Generate financial charts and reports.
- Export data to CSV or PDF.

---

## 🛠️ Requirements

To run this project, you will need:

```bash
pip install django
pip install django-crispy-forms
pip install matplotlib
```

Optionally, to generate PDF reports:
```bash
pip install reportlab
```

---

## 🚀 Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/finance-manager.git
   cd finance-manager
   ```

2. **Set up a virtual environment (optional but recommended):**
   ```bash
   python -m venv env
   source env/bin/activate  # On Linux/macOS
   env\Scripts\activate     # On Windows
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Apply database migrations:**
   ```bash
   python manage.py migrate
   ```

5. **Create a superuser (optional, for the Django admin panel):**
   ```bash
   python manage.py createsuperuser
   ```

6. **Run the development server:**
   ```bash
   python manage.py runserver
   ```

Now, you can access the application at `http://127.0.0.1:8000/`.

---

## 📚 Project Structure

```
finance-manager/
│── manage.py
│── db.sqlite3
│── finance_manager/
│   │── settings.py
│   │── urls.py
│   │── wsgi.py
│── transactions/
│   │── models.py
│   │── views.py
│   │── templates/
│   │── static/
│── users/
│   │── models.py
│   │── views.py
│── templates/
│── static/
│── requirements.txt
```

---

## 🐟 License

Distributed under the MIT License. See `LICENSE.txt` for more details.

