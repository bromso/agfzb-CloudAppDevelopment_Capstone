# Final Project Template

[![Lint Code](https://github.com/bromso/agfzb-CloudAppDevelopment_Capstone/actions/workflows/linter.yml/badge.svg)](https://github.com/bromso/agfzb-CloudAppDevelopment_Capstone/actions/workflows/linter.yml)

The final project for this course has several steps that you must complete. 
To give you an overview of the whole project, all the high-level steps are listed below. 
The project is then divided into several smaller labs that give the detailed instructions for each step. 
You must complete all the labs to successfully complete the project.

## Table of Content
- [Project Breakdown](#project-breakdown)
    - [Prework](#prework)
    - [Fork](#fork)
    - [User management](#user-management)
    - [Backend services](#backend-services)
    - [Templates](#templates)
    - [Containerize](#containerize)
- [Quickstart](#quickstart)
    - [Clone](#clone)
    - [Install](#install)
    - [Secret Key](#secret-Key)
    - [Server](#server)
    - [Users](#users)
    - [Cloud Foundry](#cloud-foundry)
    - [Git](#git)

---

## Project Breakdown

### Prework
#### Sign up for IBM Cloud account and create a Watson Natural language Understanding service**
1. Create an IBM cloud account if you don't have one already.
2. Create an instance of the Natural Language Understanding (NLU) service.

### Fork
#### Fork the Github repository with a project then build and deploy the template project**
1. Fork the repository in your account
2. Clone the repository in the theia lab environment
3. Create static pages to finish the user stories
4. Deploy the application on IBM Cloud

### User management
Add user management to the application
1. Implement user management using the Django user authentication system.
2. Set up continuous integration and delivery

### Backend services
Implement backend services
1. Create cloud functions to manage dealers and reviews
2. Create Django models and views to manage car model and car make
3. Create Django proxy services and views to integrate dealers, reviews, and cars together
 
### Templates
Add dynamic pages with Django templates
1. Create a page that shows all the dealers
2. Create a page that show reviews for a selected dealer
3. Create a page that let's the end user add a review for a selected dealer

## Containerize
Containerize your application
1. Add deployment artifacts to your application
2. Deploy your application

---

## Quickstart

### Clone
Clone the project
```sh
git clone https://github.com/bromso/agfzb-CloudAppDevelopment_Capstone.git
```

Go to the project directory
```sh
cd agfzb-CloudAppDevelopment_Capstone
```

### Install
Install the required Python packages
```sh
python3 -m pip install -r requirements.txt
```


### Secret Key
Create a [new Django Secret Key](https://humberto.io/blog/tldr-generate-django-secret-key/) 

### Server
Make migrations:
```sh
python3 manage.py makemigrations
```
Migrate the database:
```sh
python3 manage.py migrate
```
Run the development server:
```sh
python3 manage.py runserver
```

### User
Create a new superuser:
```sh
python3 manage.py createsuperuser
```

Log in via the admin site (just add `/admin` at the end of the url, eg. [localhost:8000/admin](localhost:8000/admin))

### Cloud Foundry
Push to IBM Cloud Foundry:
- Install the IBM Cloud CLI and the cloud foundry plugin
- Configure the `manifest.yml` file
-   ```sh
    ìbmcloud cf push
    ```
### Git
Clone the repository:
```sh
git clone https://github.com/bromso/agfzb-CloudAppDevelopment_Capstone.git
```
Connect your email:
```sh
git config --global user.email “your@email.com”
```
Connect your username:
```sh
git config --global user.name “username”
```
Add the files you want to commit:
```sh
git add .
```
Add a commit message:
```sh
git commit -m "your message"
```
Push your changes:
```sh
git push
```
