# Todo list

Task manager project.


## Features

* Todo list consists of tasks. Each task have fields for:
  * content - describes what you should do
  * datetime, when a task was created
  * optional deadline datetime if a task should be done until some datetime
  * the boolean field that marks if the task is done or not
  * tags that are relevant for this task
* Tag - a tag symbolizes the theme of the task
* Tasks are ordered from not done to done and from newest to oldest
* User can create new task, update and delete existing one.
* Also, there is a button Complete if a task is not done and Undo if a task is done, this button changes the status of the task to the opposite

## Installation

Python3 must be already installed

```shell
git clone https://github.com/Tania-Kharchuk/todo-list
cd todo-list
python -m venv venv
venv/Scripts/activate
pip install -r requirements.txt
python manage.py runserver
```
