# GALLERY

#### AUTHOR
SHEILA EGEIDZA



## Description
This is an online platform where I display my photos for others to see.A user can click on an image to view the image details. A user can also copy an image link. 

#### Github link
https://github.com/mmbukane-shy6/GALLERY.git

#### Link to live site
https://sheilagallery.herokuapp.com/

## BDD
<img src="/images/home.png"/>
<img src="/images/gallery.png"/>
<img src="/images/link.png"/>



## Setup and installations
* Fork the data onto your own personal repository.
* Clone Project to your machine
* Activate a virtual environment on terminal: `source virtual/bin/activate`
* Install all the requirements found in requirements file.
* On your terminal run `python3.7 manage.py runserver`
* Access the live site using the local host provided


#### Prerequisites
1. [Python3.7](https://www.python.org/downloads/)

2. [virtualenv](https://virtualenv.pypa.io/en/stable/installation/)
3. [pip](https://pip.pypa.io/en/stable/installing/)

#### Technologies used
    - Python3.7
    - HTML
    - Bootstrap 4
    - Heroku
    - Postgresql
    - Django 1.11

#### Clone the Repo and rename it to suit your needs.
```bash
```https://github.com/mmbukane-shy6/GALLERY.git
#### Initialize git and add the remote repository
```bash
git init
```
```bash
git remote add origin <your-repository-url>
```

#### Create and activate the virtual environment
```bash
python3.7 -m virtualenv virtual
```

```bash
source virtual/bin/activate
```

#### Setting up environment variables
Create a `.env` file and paste paste the following filling where appropriate:
```
SECRET_KEY='rdtfyguihjohucbdsjnc'
DEBUG=True
DB_NAME='tribune'
DB_USER='<your database name>'
DB_PASSWORD='<password to your database>'
DB_HOST='127.0.0.1'
MODE='dev'
ALLOWED_HOSTS='.localhost', '.herokuapp.com', '.127.0.0.1'
DISABLE_COLLECTSTATIC=1
```

#### Install dependancies
Install dependancies that will create an environment for the app to run
`pip install -r requirements.txt`

#### Make and run migrations
```bash
python3.7 manage.py check
python manage.py makemigrations news
python3.7 manage.py sqlmigrate news 0001
python3.7 manage.py migrate
```

#### Run the app
```bash
python3.7 manage.py runserver
```
Open [localhost:8000](http://127.0.0.1:8000/)


## Bugs
#### Known bugs
There are no known bugs at the moment 



## Support and contact details
Email address: sheilaegeidza@gmail.com
### License
[MIT LICENSE](LICENCE)

Copyright (c)2020 **sheilaegeidza**
