# 🌐 Personal Portfolio Website – Django

## 📌 Project Overview

A personal portfolio website developed using **Python and Django** to showcase my technical skills, professional experience, projects, education, and contact information.

The website provides a platform for presenting my development journey and demonstrating my practical experience in Python development and Data Science.

## 🎯 Features

- **Home Page:** Introduction and personal profile.
- **About Me:** Educational background and professional information.
- **Skills:** Technical skills and technologies.
- **Projects:** Showcase of completed projects with descriptions.
- **Experience:** Professional experience and training details.
- **Contact:** Contact information for professional opportunities.
- **Responsive Design:** User-friendly interface across different screen sizes.

## 🛠️ Technologies Used

| Category | Technologies |
|---|---|
| Backend | Python, Django |
| Frontend | HTML, CSS, JavaScript |
| Database | SQLite |
| Styling | Bootstrap / CSS |
| Version Control | Git, GitHub |

## 📂 Project Structure

```text
Portfolio/
│
├── Aakash/
│   ├── migrations/
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── urls.py
│   └── views.py
│
├── Portfolio/
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
│
├── templates/
│   └── base.html
│
├── static/
│   ├── css/
│   ├── js/
│   └── images/
│
├── manage.py
├── requirements.txt
├── .gitignore
└── README.md
```

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Aakashv34/Django-Portfolio-Website.git
```

### 2. Navigate to the Project Directory

```bash
cd Django-Portfolio-Website
```

### 3. Create a Virtual Environment

```bash
python -m venv venv
```

Activate the environment:

**Windows:**

```bash
venv\Scripts\activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

### 5. Configure Environment Variables

Create a `.env` file in the project root directory.

```env
DJANGO_SECRET_KEY=your_django_secret_key
DEBUG=True
```

Use your own Django secret key. Never upload the `.env` file to GitHub.

### 6. Apply Database Migrations

```bash
python manage.py migrate
```

### 7. Run the Development Server

```bash
python manage.py runserver
```

Open your browser:

```text
http://127.0.0.1:8000/
```

## 🔐 Security

- Django secret key is managed using environment variables.
- Environment configuration files are excluded from Git.
- Debug mode is configurable through environment variables.


## 🚀 Future Improvements

- Add a downloadable resume feature.
- Improve SEO and website performance.
- Add a blog section.
- Enhance deployment and production configuration.
- Integrate additional interactive features.

## 👨‍💻 Developer

**Aakash V Devan**

- GitHub: [Aakashv34](https://github.com/Aakashv34)
- Portfolio Repository: [Django Portfolio Website](https://github.com/Aakashv34/Django-Portfolio-Website)

---

⭐ Thank you for visiting my portfolio project!
