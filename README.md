- Setting up a virtual env and installing prereq to "vnev/Scripts"
    python -m venv venv

- activate venv:
    venv/Scripts/activate.bat
    venv/Scripts/deactivate.bat

- Installing Django library
    python -m pip install django=="3.2.9"

- creating requirements.txt 
    python -m pip freeze > requirements.txt

-convert directory into prject to manage the app and code
    python -m django startproject todo_project .