# FlaskApp_Test
A test website made using Flask framework

Database - SQLite

File_Structure:

├───app.py 
├───requirements.txt 
├───migrations # folder created for migrations by calling
├───myproject # main project folder
│   │   data.sqlite
│   │   models.py
│   │   __init__.py
│   │
│   ├───owners
│   │   │   forms.py
│   │   │   views.py
│   │   │
│   │   ├───templates
│   │      └───owners
│   │             add_owner.html
│   │   
│   │
│   ├───puppies
│   │   │   forms.py
│   │   │   views.py
│   │   │
│   │   ├───templates
│   │   │   └───puppies
│   │   │           add.html
│   │   │           delete.html
│   │   │           list.html
│   │
│   ├───static # Where you store your CSS, JS, Images, Fonts, etc...
│   ├───templates
│          base.html
│          home.html


