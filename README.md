Core-Calamus Training-POC Demo Application

1. Download the repository as a whole, or use command `git clone git@gitlab.otxlab.net:saikrisk/calamus-demo.git` with Git Bash.

2. Prerequisites for running the application are Python, and Django. 

    - **Python** can be downloaded from https://www.python.org/downloads/
    - **Django** can be downloaded from https://www.djangoproject.com/download/, by simply running command in the terminal.

        `pip install Django`

    - Install the **requests** module using `pip install requests`

3. Provide your mail credentials in settings.py file and change the SMTP settings according to your host. After that Update the mail address "youremail@domain.com"in views.py file to the one used in settings.py .


4. The application can be locally hosted by the command in the terminal:

    `python manage.py runserver`



5. It can then be accessed using the localhost url provided in the terminal.

    `http://127.0.0.1:8000/`

