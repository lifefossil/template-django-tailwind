# template-django-tailwind
A template of Django styling with tailwindcss

## Download this template
```bash
$ codegen create your_project_name -t django-tailwind
```
`codegen` is a Scaffolding tool that published on PYPI. You can find it on PYPI by the name of `oliver-codegen`

## Install Dependencies
Now we're going to create a virtual environment and install dependencies with poetry tool.
```bash
$ cd your_project_name
$ poetry install
```

## Run Project
Start the node.js development server by running the following command in your terminal:
```bash
$ python manage.py tailwind start
```
Start the Django development server by opening a new terminal:
```bash
$ python manage.py runserver
```