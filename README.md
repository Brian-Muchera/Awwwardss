# Awwwwardss

> [Brian-Muchera](https://github.com/Brian-Muchera)

# Description

This project allows users to post their projects for other users to rate according to design, usability and content

# Api Endpoints

- https://awwardsbrian.herokuapp.com/api/users/
- https://awwardsbrian.herokuapp.com/api/posts/


## Live Link

Click [View Site]( https://awwardsbrian.herokuapp.com/) to visit the site

## Behavior Driven Development

| Input                                         | Behaviour                                              | Output                                                                                            |
| --------------------------------------------- | ------------------------------------------------------ | ------------------------------------------------------------------------------------------------- |
| User registers for an account by filling form | User is sent an email to activate the account          | User is redirected to login page                                                                  |
| User logs in                                  | User is taken to the home page                         | Redirect you to the homepage where the user is greeted with a feed of most recent projects posted |
| User clicks submit button and fills the form  | The page reloads                                       | User's new post is displayed on the feed                                                          |
| User clicks on a project                      | User redirected to rate projrct page                   | User rates a project on content usability                                                         |
| User clicks on the view button                | User is redirected to a the url of the site or project | A page the deployed project. .                                                                    |


## User Story

- A user can view posted projects and their details.
- Search for projects.
- View projects overall score.
- A user can view their profile page.

## Setup and Installation

To get the project .......

##### Cloning the repository:

```bash
https://github.com/Brian-Muchera/Awwwardss.git
```

##### Navigate into the folder and install requirements

```bash
cd awwwards pip install -r requirements.txt
```

##### Install and activate Virtual

```bash
- python3 -m venv virtual - source virtual/bin/activate
```

##### Install Dependencies

```bash
pip install -r requirements.txt
```

##### Setup Database

SetUp your database User,Password, Host then make migrate

```bash
python manage.py makemigrations awards
```

Now Migrate

```bash
python manage.py migrate
```

##### Run the application

```bash
python manage.py runserver
```

##### Testing the application

```bash
python manage.py test
```

Open the application on your browser `127.0.0.1:8000`.

## Technology used

- [Python3.8](https://www.python.org/)
- [Django 3.1.2](https://docs.djangoproject.com/en/2.2/)
- [Heroku](https://heroku.com)

## Known Bugs

- There is a bug for rating incase anyone comes through it pull requests are allowed

## Contact Information

If you have any question or contributions, please email me at [mucherabrian2@gmail.com]

## License

- [![License](https://img.shields.io/packagist/l/loopline-systems/closeio-api-wrapper.svg)](https://github.com/default-007/awwwards/blob/master/LICENSE)
- Copyright (c) 2020 **Muchera Brian**
