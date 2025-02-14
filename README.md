# Django Recipe Project  

The **Django Recipe Project** is a web application that allows users to manage recipes with full CRUD (Create, Read, Update, Delete) functionality. Built with Django, it provides an intuitive interface to add, view, edit, and delete recipes.  

## Features  
- Add new recipes with title, ingredients, and instructions  
- View a list of all recipes  
- Edit existing recipes  
- Delete recipes when no longer needed  

## Installation  
1. Clone the repository:  
   ```bash
   git clone <repository_url>
   cd django-recipe-project
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
4. Run migrations:  
   ```bash
   python manage.py migrate
   ```  
5. Start the development server:  
   ```bash
   python manage.py runserver
   ```  

## Usage  
- Open `http://127.0.0.1:8000/` in your browser  
- Manage your recipes with a simple UI  

## License  
This project is open-source and available under the [MIT License](LICENSE).  
