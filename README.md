# CS471 Django Project

## Course :
CS471 - Web Technologies

## Project Name :
SuraWebsite

## Project Description :
This project was created as part of the CS471 (Web Technologies) course.  
It is a Django web application that demonstrates the use of:
- Models, views, and templates
- Database migrations
- URL routing
- Static files and templates

## Project Structure :
```
SuraWebsite/
├─ manage.py
├─ SuraWebsite/       # settings, urls, wsgi, asgi
├─ templates/
└─ static/
```

## Requirements :
- Python 3.x
- Django (latest stable version)
- Virtual environment (recommended)

## How to Run ?
1. Clone the repository:
```bash
git clone https://github.com/Sura3-s/CS471_Django_Project.git
cd SuraWebsite
```

2. Create and activate a virtual environment:
```bash
python3 -m venv venv
source venv/bin/activate   # macOS/Linux
venv\Scripts\activate      # Windows
```

3. Install Django:
```bash
pip install django
```

4. Apply migrations:
```bash
python manage.py migrate
```

5. Run the development server:
```bash
python manage.py runserver
```

6. Run the development server and open the website in your browser to see it working locally.

## Git & GitHub Setup :

To initialize the Git repository and push the project to GitHub, follow these steps:

1. Initialize a new Git repository in your project folder:
```bash
git init
```
2. Add all project files to the staging area:
```bash
git add .
```
3. Commit the files with a meaningful message:
```bash
git commit -m "Initial commit"
```
4. Link your local repository to the remote GitHub repository:
```bash
git remote add origin https://github.com/username/CS471_Django_Project.git
```
5. Rename your branch to main (optional but recommended):
```bash
git branch -M main
```
6. Push your local repository to GitHub:
```bash
git push -u origin main
```

Note: Using git add . is sufficient to include all files unless you have files ignored by .gitignore. The -f option is only needed to force-add ignored files, so it is not necessary in most cases.

## Conclusion
Through this project, I learned how to build a web application using Django.  
I created the main project folder (`SuraWebsite`) and set up the project structure.  
I practiced working with models, views, templates, and static files, and applied database migrations.  
I also learned how to run the development server and view the project in a web browser.  
This project helped me understand the basics of Django and how to organize a web project.

