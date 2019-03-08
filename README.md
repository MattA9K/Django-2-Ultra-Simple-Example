# Django 2.1 Ultra Simple Example
##### Matt Andrzejczuk

Use this minimalist project as a cheatsheet for any new Django 2.1 project you'd like to 
create. All code is kept to a bare minimum to implement a movie list application.

### Getting Started

#### I. For a fresh Ubuntu installation, get Python3 all setup and ready to go: 
```bash
sudo apt-get update && sudo apt-get install -y \
		build-essential git \
		python3 python3-dev python3-setuptools \
		nginx supervisor \
		postgresql-client libpq-dev \
		sqlite3 libjpeg62-turbo-dev \
		python3-pip \
		software-properties-common python3-software-properties
		
sudo apt install -y virtualenv python3-venv
```

#### II. Get your project ready:
```bash
git clone https://github.com/MattAndrzejczuk/Django-2-Ultra-Simple-Example.git
cd Django-2-Ultra-Simple-Example
python3 -m venv env
```

#### III. Download Dependencies
```bash
source ./env/bin/activate
pip install -r requirements.txt
```

#### IV. Run Server
```bash
./manage.py createsuperuser
./manage.py runserver
```
##### App Main Page:
http://127.0.0.1/

##### Edit Content For Main Page:
http://127.0.0.1/admin
