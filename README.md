# 📝 Flask CRUD Task Manager

This is a simple CRUD (Create, Read, Update, Delete) web application built using Flask and SQLite. It allows users to manage tasks — including creating, viewing, editing, and deleting tasks.

---

## 💻 Technologies Used

- Python (Flask)
- SQLite (Database)
- HTML & CSS (Frontend)
- Jinja2 (Templating Engine)
- Git & GitHub (Version Control)

---

## ✅ Features

- Add new tasks  
- View all tasks in a table format  
- Edit task title or description  
- Delete tasks  
- Responsive and simple user interface  

## 👥 Contributors


| Name                                       | Contributions                                                                                                |
| -------------------------------------------- | -------------------------------------------------------------------------------------------------------------- |
| [Ife](https://github.com/olaife230)     | Built the interface using html and css and handled form submission to the flask endpoints|
| [Abigail](https://github.com/abibi123)     | created the read me file, including the setup guide and set up the environment variables|
| [Haruna](https://github.com/harunaMb) |  connected flask to mysql, tested all crud functionalities|
| [Hauwa](https://github.com/jeremiahauwa)        | set up mysql database and provided  database connection configuration                            |
| [David](https://github.com/David-dev24)  | Set-up the flask application software, implemented crud api endpoints                      |


---

## ▶️ How to Run It

1. **Clone this repo:**
```bash
git clone https://github.com/olaife230/Flask-Task-App.git
cd Flask-Task-App

python -m venv .venv
.venv\Scripts\activate
pip install flask flask_sqlalchemy
python app.py
http://127.0.0.1:5000/
