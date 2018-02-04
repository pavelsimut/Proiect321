# WinYourHabit API

### Setup
```bash
clone winyourhabit repo
cd winyourhabit-api

# Create a virtualenv to isolate our package dependencies locally
virtualenv env
source env/bin/activate  # On Windows use `env\Scripts\activate`

# Install Django and Django REST framework into the virtualenv
pip install -r requirements.txt

# Create tables in database
python manage.py migrates