# Development Steps

## Fri 21Sept2018
1. Create new project file
2. Initialise Git
3. Create this file - DEVELOPMENT.md 
    ~~~~
    touch DEVELOPMENT.md
    ~~~~
4. Create a virtual environment
    ~~~~
    virtualenv venv -p python3
    ~~~~
5. Create gitignore
6. Place virtual environment in gitignore
    ~~~~
    touch .gitignore
    ~~~~
7. Create README.md 
    ~~~~
    touch README.md
    ~~~~
8. Add initial notes to README.md


9. Create a new gihub repository and connect it to this git.  
    Git first commit and push up to github
    ~~~~
    git add .  
    git commit -m "first commit"  
    git remote add origin https://github.com/abonello/flask_SQLAlchemy.git  
    git push -u origin master  
    ~~~~
10. Start the virtual environment
    ~~~~
    source venv/bin/activate
    ~~~~
11. Install Flask
    ~~~~
    pip install Flask
    ~~~~
12. Install Flask-SQLAlchemy
    ~~~~
    pip install Flask-SQLAlchemy
    ~~~~
13. Create requirements.txt
    ~~~~
    pip freeze --local > requirements.txt
    ~~~~


