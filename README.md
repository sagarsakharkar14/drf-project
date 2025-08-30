# 🛒 DRF E-Commerce API

A backend e-commerce application built using Django REST Framework. This project demonstrates modular API development, clean architecture, and integration of essential e-commerce features.

## 🚀 Features

- User registration and authentication
- Product listing and categorization
- Cart management
- Order placement and tracking
- Admin panel for product and order management
- RESTful API endpoints with pagination and filtering

## 🧰 Tech Stack

- **Backend**: Django, Django REST Framework
- **Database**: SQLite (default, can be swapped with PostgreSQL)
- **Testing**: Pytest
- **Environment Management**: `requirements.txt`
- **Version Control**: Git & GitHub

## 📁 Project Structure
drfecommerce/ ├── drfecommerce/        
# Core Django project files ├── manage.py            
# Entry point for Django project ├── pytest.ini           
# Pytest configuration ├── requirements.txt     
# Python dependencies ├── .gitignore           
# Git ignored files └── commands.md          


## 🧪 Setup & Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/sagarsakharkar14/drf-project.git
   cd drf-project/drfecommerce
   
2. Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

3. Install dependencies
   pip install -r requirements.txt
   
5. Run migrations
   python manage.py migrate
   
7. Start the development server
   python manage.py runserver

📌 Notes
- This project is structured for scalability and modularity.
- Future enhancements may include payment gateway integration, product reviews, and JWT-based authentication, many more can be done.












