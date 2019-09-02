# Halo Fullstack Coding Challenge 2019

## Create a virtual environment and activate

`virtualenv -m python3 .env`
`source .env/bin/activate`

## Install PostgreSql

`sudo apt install postgresql postgresql-contrib`

## Create databases

`createdb -U <user_name> test_db`

`createdb -U <user_name> blackCoffer`

## Install the required packages

`pip install -r requirements.txt`

## Export some environment variables

```bash
export FLASK_APP="run.py"
export SECRET="some-very-long-string-of-random-characters-CHANGE-TO-YOUR-LIKING"
export APP_SETTINGS="development"
export DATABASE_URL="postgresql://<username>:<password>@localhost/blackCoffer"
```

