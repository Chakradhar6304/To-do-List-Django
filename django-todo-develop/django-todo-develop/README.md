Django To-Do List

A simple yet efficient to-do list application built with Django, designed to help users manage tasks effectively.

🚀 Features

✅ User authentication (signup, login, logout)

📝 Task creation, updating, and deletion

📌 Task prioritization and categorization

📱 Responsive web design for seamless use on multiple devices

⚙️ Admin dashboard for managing tasks and users

🔍 Built-in search functionality to quickly find tasks

🔒 Secure and efficient database operations with PostgreSQL

🛠️ Installation

Follow the steps below to set up and run the application on your local machine.

Prerequisites

Ensure you have the following installed on your system:

🐍 Python (>=3.8)

🦄 Django (>=4.0)

🐘 PostgreSQL (or SQLite for development)

🔗 Git

Setup Instructions

Clone the repository:

git clone https://github.com/Chakradhar6304/To-do-List-Django.git
cd To-do-List-Django

Create and activate a virtual environment:

python -m venv venv
source venv/bin/activate   # For Linux/macOS
venv\Scripts\activate      # For Windows

Install the required dependencies:

pip install -r requirements.txt

Set up the database:

python manage.py makemigrations
python manage.py migrate

Create a superuser to access the admin panel:

python manage.py createsuperuser

Run the development server:

python manage.py runserver

Access the application at:

http://127.0.0.1:8000/todos

📋 Usage

Register a new user or log in with existing credentials.

Create, update, and manage your tasks.

Prioritize tasks by category and due dates.

Access the admin panel at http://127.0.0.1:8000/admin to oversee operations.

🏗️ Contributions

I have worked extensively on:

⚡ Enhancing backend performance and database optimization.

🔐 Implementing a robust authentication system.

🎨 Improving UI/UX for better user interaction.

📂 Adding features such as task categorization and prioritization.

🚧 Future Enhancements

🌍 Integration with third-party services like Google Calendar.

📱 Mobile-friendly UI improvements.

📧 Automated email reminders for pending tasks.

📜 License

This project is licensed under the MIT License.

📞 Contact

For any inquiries or suggestions, feel free to reach out:

GitHub: Chakradhar6304

Email: chakradharnemali@gmail.com