
### Installation:

* pip install uv

* Initialize project 

`uv init <project>`

Ex: `uv init uv_demo`

* create virtual environment:

`uv venv`

* Activate the virtual environment:

`source .venv/bin/activate`

* To install dependencies:

`uv add numpy`

* To install from requirements.txt file

`uv add -r requirements.txt`

* To run any python file

`uv run <.py file name>`

* To sync your packages

`uv sync`

* To lock your packages

`uv lock`