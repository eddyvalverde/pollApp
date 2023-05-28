# pollsApp

## How to start

1. Open Project in Visual studio code
2. Create new python environment

```console
foo@bar:~/source/repos/NutriTrack$ python3 -m venv <venv_name>
```
For example:
```console
foo@bar:~/source/repos/NutriTrack$ python3 -m venv dev
```
3.  Activate python environment
```console
foo@bar:~/source/repos/NutriTrack$ source <venv_name>/bin/activate
```
For example:
```console
foo@bar:~/source/repos/NutriTrack$ source dev/bin/activate
```
4. Install all the dependencies
Install all dependencies defined in requirements.txt file by running:
```console
foo@bar:~/source/repos/NutriTrack$ pip install -r requirements.txt
```

5. Copy env file
Install all dependencies defined in requirements.txt file by running:
```console
foo@bar:~/source/repos/NutriTrack$ cp .env.example .env
```

5. Run database with docker
Make sure you have opened Docker Desktop:
```console
foo@bar:~/source/repos/NutriTrack$ docker compose up -d
```

5. Run Django App
```console
foo@bar:~/source/repos/NutriTrack$ ./manage.py runserver
```