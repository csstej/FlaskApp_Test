# FlaskApp_Test
A test website made using Flask framework

Database - SQLite

File_Structure:

├───app.py <br/>
├───requirements.txt <br/>
├───migrations # folder created for migrations by calling<br/>
├───myproject # main project folder<br/>
│   │   data.sqlite<br/>
│   │   models.py<br/>
│   │   __init__.py<br/>
│   │<br/>
│   ├───owners<br/>
│   │   │   forms.py<br/>
│   │   │   views.py<br/>
│   │   │<br/>
│   │   ├───templates<br/>
│   │      └───owners<br/>
│   │             add_owner.html<br/>
│   │   <br/>
│   │
│   ├───puppies<br/>
│   │   │   forms.py<br/>
│   │   │   views.py<br/>
│   │   │<br/>
│   │   ├───templates<br/>
│   │   │   └───puppies<br/>
│   │   │           add.html<br/>
│   │   │           delete.html<br/>
│   │   │           list.html<br/>
│   │<br/>
│   ├───static # Where you store your CSS, JS, Images, Fonts, etc...<br/>
│   ├───templates<br/>
│          base.html<br/>
│          home.html<br/>


