# AI Blog Article Genrator from youtube videos

This project genrates articles from the youtube videos provided via Open AI chatgpt plugin
It is build using django framework

## To run this project on your local machine
- open terminal/cmd in the project folder
- Run `python -m venv env` to create a virtual environment
- Run `env\scripts\activate.bat` to activate virtual environment
    - In case it didn't work try the command without `.bat`
- Run `pip install -r requirements.txt`
- Run `python manage.py makemigrations` and then `python manage.py migrate`
- Additionaly you have to acquire open ai and assembly ai api keys and paste them in the `blog_genrator/views.py` in line 82 and 74 respectively
- Now run `python manage.py runserver` and website should be up and running.

