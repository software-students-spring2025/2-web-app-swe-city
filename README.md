# Web Application Exercise

A little exercise to build a web application following an agile development process. See the [instructions](instructions.md) for more detail.

## Product vision statement

Restaurant Roulette helps people more easily keep track of their favorite food spots while discovering new cuisines and connecting with other foodies, all to make the saving, exploring, and sharing of food lovers an effortless experience.

## User stories

1.  As a user, I want to create an account so I can start tracking my favorite restaurants.
2.  As a user, I want to log into my account so I can access the record of my favorite restaurants.
3.  As a user, I want to log out of my account so I can prevent other users who use the same device from modifying my restaurant record.
4.  As a user, I want to set a username for my account so I have a more anonymous and personalized experience in the app.
5.  As a user, I want to access my own restaurant list so I can view the restaurants I keep track of.
6.  As a user, I want to add a restaurant to my own list so I can save and keep track of that food spot.
7.  As a user, I want to delete a restaurant from my own list so I can decide to no longer track that food spot.
8.  As a user, I want to add a rating to a restaurant so I can easily indicate the quality of the restaurant.
9.  As a user, I want to input the address of a restaurant so that I keep track of where the restaurant is located.
10. As a user, I want to add the type of cuisine a restaurant is known for so I can provide a quick summary of the style of food the restaurant specializes in.
11. As a user, I want to add a price range of a restaurant so I can have a better idea of how much I spent or am going to spend in that food spot.
12. As a user, I want to edit my restaurants' information so I can add or correct previous reviews.
13. As a user, I want to access the homepage of all restaurants so I can explore a list of all restaurants tracked in the app.
14. As a user, I want to add other users as friends so I can access their personalized restaurant list.
15. As a user, I want to view my friends’ personalized restaurant list so I can discover new food spots based on their preferences.
16. As a user, I want to randomly select a restaurant from my restaurant list so I can decide on a spot to visit when indecisive.

[LINK to User Stories](https://github.com/software-students-spring2025/2-web-app-swe-city/issues)

## Steps necessary to run the software

### Python

This software application has been written in Python.
To be able to run the application, a Python interpreter is required in the machine.

Python can be downloaded [here](https://www.python.org/downloads/).

### pip

pip is a package manager for Python and Python modules. pip is usually included in the Python installation, but if for some reason it is not in the machine, make sure to install it.

This is going to be used to install dependencies for this application.

pip can be installed [here](https://pip.pypa.io/en/stable/installation/)

### Virtual environment (venv) - Optional

A virtual environment is a self-contained isolated space where project dependencies are installed.
Dependencies are automatically installed globally, meaning that other projects will also be accessing/using those dependencies. Therefore, for this project, a virtual environment is recommended so that the dependencies installed for it will not interact with/be used by other projects in your machine.
After cloning the GitHub repository, at the root directory of the project, run the following command in the command line:

`python -m venv .venv`

or

`python3 -m venv .venv`

Then, to active the environment, run the following command:

`source .venv/bin/activate` (MacOS)

`.venv\Scripts\activate.bat` (Windows)

The dependencies below should now be installed in this virtual environment.

<br/>

### Dependencies

### Automatic Installation

To automatically install all of the required dependencies, run the following command in the command line:

`pip install -r requirements.txt`

### Manual Installation

If the requirements file is missing or some error occurred, manually install the dependencies of the project.

The following commands should be run in the command line.

#### Flask

`pip install Flask`

#### Flask-Login

`pip install Flask-Login`

#### dotenv

`pip install python-dotenv`

#### pymongo

`python3 -m pip install pymongo`

Finally, verify that all of the dependencies mentioned in the requirements file have been successfully installed:

`pip list`

<br/>

### Running the Application

To run the application, run either of the commands in the command line:

`python app.py` or `python3 app.py`

or

`flask run`

A URL will be given once the command is successfully run.

Click or copy/paste the URL into your browser to access the running software application.

## Task boards

[LINK to Task Board](https://github.com/orgs/software-students-spring2025/projects/20/views/2)
