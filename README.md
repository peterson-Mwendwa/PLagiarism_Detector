
This project has been forked from [https://github.com/SE-19/autograding-of-cs-courses](https://github.com/SE-19/autograding-of-cs-courses) for educational and collaborative purposes. The fork allows for further development, experimentation, and improvements while retaining the core functionalities of the original project.


# autograding-of-cs-courses

![First screen](./screenshots/screen1.png)
**Home page**
![First screen](./screenshots/screen2.png)
**Assignment about**
![First screen](./screenshots/screen3.png)
**Assignment about**
![First screen](./screenshots/screen4.png)
**Create assignment**
![First screen](./screenshots/screen5.png)
**create assignment file**

5th Semester project for SE subject offered by UET, Lahore.

To run:

Activate the virtual environment (it might install some packages)

    pipenv shell

Install Flask, Flask-SQLAlchemy.

    pipenv install flask, flask-sqlalchemy

Before running, you must initiate the database by first activating the virtual environment and then execute python shell by the following command:

    drive:/path> python

Then, enter the following commands:

    > from app import db
    > db.create_all()

After this, you can exit the terminal using `exit()`
and then run the following command to run the localhost.

    python app.py

Make sure the virtual environment is activated