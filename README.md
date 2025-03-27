# Feed This Much
II1305 Project 

# Windows
If you are using Windows, you can install WSL and follow the rest of instructions. 

## How to set up local env
Project has some dependencies that need to be installed. We use `uv` package manager to handle the dependencies. 

**uv**: Use the link (https://github.com/astral-sh/uv) to install

Create the virtual environment by running `uv venv`
Activate the virtual environment by running `source .venv/bin/activate` and run `uv sync` to install the dependencies

Run the local development server by `python manage.py runserver`
