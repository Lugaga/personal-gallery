# Personal Gallery (Lugagaleria)

#### This is a personal gallery where I post photos of cities i fly to, users can view the photos, read details and copy a shareable link to share with friends and families.

#### By **Lugaga Maurice Ngulu**

## BDD
| Behavior| Input | Output |
| :-------------: | :-------------: | :-------------: |
| View Image Details | Click on Image  | Image Full size with details |

### Technologies Used

- HTML5
- CSS3
- django-Bootstrap4
- Python3.6
- Heroku
- Django
- postgresql
- whitenoise
- pillow

## Setup/Installation Requirements

### Prerequisites
- python
- django
- postgresql
- git
- heroku

### Clone the repo and checkout into the project folder.

- `git clone https://github.com/lugaga/personal-gallery.git`
- `cd gallery`

### Create and activate the virtual environment

- `python3.6 -m venv virtual`
- `source virtual/bin/activate`

### Install the dependencies

Install dependancies that will create an environment for the app to run.

- `pip install -r requirements.txt`

### Create an .env file and replace the following with your settings:

- SECRET_KEY='642726trtghgj'
- DEBUG=True #set to false in production
- DB_NAME='db-name'
- DB_USER='root'
- DB_PASSWORD='password'
- DB_HOST='127.0.0.1'
- MODE='dev' #set to 'prod' in production
- ALLOWED_HOSTS='.localhost', '.herokuapp.com', '.127.0.0.1'
- DISABLE_COLLECTSTATIC=1

### Make migrations to your database
- `python3.6 manage.py migrate`

### Run `manage.py` in the terminal

- `python3.6 manage.py runserver`

## Support
* Email: maureezgaga@outlook.com

### License and Copyright details
* The MIT License [MIT](LICENSE)
* Copyright (c) 2019 **Engineer Lugaga**
