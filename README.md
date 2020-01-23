# Django + RestFramework + OAuth2

## Setup - 5 Steps

### Step 1 - Setting up Virtual Environment
  To install Virtual Environment
  
  pip install virtualenv
  
  Create a Virtual Environment
  
  python -m venv environment-name
  
  To Activate the Environment
  
  source environment-name/bin/activate
  
  Install Dependencies
  
  pip install django djangorestframework django-oauth-toolkit
  
### Step 2 - Setting up our Django project
  
  To start a django project first we need to be in the virtual environment.
  
  python -m django startproject api
