# 🧑‍🎓 CGPA Calculator
This project is a Django-based web application designed to calculate and manage CGPA (Cumulative Grade Point Average) for students.

## 🚀 Features

- User authentication and profile management.
- Add, edit, and delete semester grades.
- Automatic CGPA calculation.
- Responsive and user-friendly interface.

## 🛠️ Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/CGPA.git
    cd CGPA
    ```

2. Create and activate a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Apply migrations:
    ```bash
    python manage.py migrate
    ```

5. Run the development server:
    ```bash
    python manage.py runserver
    ```

6. Open the application in your browser at `http://127.0.0.1:8000`.

## Usage

1. Register or log in to your account.
2. Add your semester grades.
3. View your CGPA and manage your grades.

## 🧩 Tech Stack

- **Backend**: Django
- **Frontend**: HTML, CSS, JavaScript
- **Database**: SQLite (default, can be changed)
