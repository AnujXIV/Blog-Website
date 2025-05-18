# 📰 MiniBlog – A Django-Powered Blog Website

**MiniBlog** is a simple yet powerful blog web application built using the Django framework. It allows users to create, edit, and publish blog posts with ease. This project is great for learning Django fundamentals, handling forms, working with models, and implementing admin features.

---

## 🚀 Features

- 🖊️ **Create, Edit, and Delete Posts**
- 📅 **Timestamped Blog Entries**
- 🔐 **Django Admin Panel for Post Management**
- 📂 **Structured Django App Architecture**
- 🧪 **Basic Unit Testing Setup**

---

## 🛠️ Tech Stack

- **Framework**: Django (Python)
- **Database**: SQLite (default)
- **Frontend**: HTML, CSS (via Django templates)
- **Admin Panel**: Django’s built-in admin interface

---

## 🗂️ Project Structure

```
miniblog/
├── blog/                 # Core app containing models, views, forms
│   ├── admin.py
│   ├── apps.py
│   ├── forms.py
│   ├── models.py
│   ├── views.py
│   └── migrations/
├── miniblog/             # Project settings and URLs
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── db.sqlite3            # SQLite database file
├── manage.py             # Django management script
```

---

## ⚙️ Setup Instructions

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/miniblog.git
   cd miniblog
   ```

2. **Create and Activate a Virtual Environment**

   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Run Migrations**

   ```bash
   python manage.py migrate
   ```

5. **Create Superuser (for Admin Access)**

   ```bash
   python manage.py createsuperuser
   ```

6. **Start Development Server**

   ```bash
   python manage.py runserver
   ```

7. **Access the App**

   - Visit: `http://127.0.0.1:8000/`
   - Admin Panel: `http://127.0.0.1:8000/admin/`

---

## 📌 Notes

- Blog entries are managed via Django's admin interface.
- Easily extendable with user authentication, comments, categories, and tags.

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a branch: `git checkout -b feature/YourFeature`
3. Make your changes and commit: `git commit -m 'Add new feature'`
4. Push to your fork: `git push origin feature/YourFeature`
5. Create a Pull Request

---

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

---

## 👨‍💻 Author

**Anujkumar Patel**  
🔗 [LinkedIn](https://www.linkedin.com/in/akp003)

---

> *A clean and simple blog engine built with Django – ideal for learning and launching.* 🚀