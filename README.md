# Flashcards

## Author
* MERCY VUGUTSA
* BARNABAS KAMAU


* Link to live site: [Flashcards-App](https://flashy23.herokuapp.com/)

## Description
Flashcards is an app that enables users to write their thoughts and feelings through the use of notes.

As a user of the web application you will be able to:

1. Sign up and log in
2. Add a new note.
3. Update a note.
4. Delete a note.
5. Edit your profile



## Setup and installations
* Fork the data onto your own personal repository.
* Clone Project to your machine
* Activate a virtual environment on terminal: `. virtual/bin/activate`
* Install all the requirements found in requirements file.
* On your terminal run `python3.6 manage.py runserver`
* Access the live site using the local host provided



## Getting started

### Prerequisites
* python3.6
* virtual environment
* pip

#### Clone the Repo and rename it to suit your needs.
```bash
git clone https://github.com/vugutsa/Flashcards.git
```
#### Initialize git and add the remote repository
```bash
git init
```
```bash
git remote add origin <your-repository-url>
```

#### Create and activate the virtual environment
```bash
python3 -m venv virtual
```

```bash
source virtual/bin/activate
```

#### Install dependancies
Install dependancies that will create an environment for the app to run
`pip install -r requirements.txt`

#### Make and run migrations
```bash
python3.6 manage.py check
python manage.py makemigrations awward_app
python3.6 manage.py sqlmigrate awward_app 0001
python3.6 manage.py migrate
```

#### Run the app
```bash
python3.6 manage.py runserver
```
Open [localhost:8000](http://127.0.0.1:8000/)



## Testing the Application
`python manage.py test cards`
        
## Built With

* [Python3.6](https://docs.python.org/3/)
* Django 2.2.8
* Postgresql 
* Boostrap4
* HTML


## Support and contact details
 Incase you come across errors, have questions, ideas ,concerns, or want to contribute to the application you can feel free to reach : vugutsamercy84@gmail.com


### License

* [[License: MIT]](Licence.md) <vugutsamercy84@gmail.com>
