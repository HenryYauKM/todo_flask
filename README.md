# todo_flask
todo_flask youtube

Commands:

cd %USERPROFILE%

mkdir flask_project
cd flask_project
mkdir todo_flask
cd todo_flask
python -m venv venv
venv\Scripts\activate
python -m pip install --upgrade pip
pip install flask
pip install Flask-SQLAlchemy
code .

flask shell   
from app import db
db.create_all()
exit()
flask run
