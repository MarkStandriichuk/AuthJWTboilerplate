# AuthJWTboilerplate

### JWT authentication boilerplate for DRF projects

## Installation
Use [pipenv](https://pypi.org/project/pipenv/) package manager.

1. Run this command to install all requirements from Pipfile
```bash
pipenv update
```
2. Apply migrations:
```bash
pipenv makemigrations
pipenv migrate
```
3. Start development server:
```bash
pipenv runserver
```
4. Go to [http://127.0.0.1:8000/auth/](http://127.0.0.1:8000/auth/) for API Root of the project

#### All needed endpoints you can find at the [Djoser official docs](https://djoser.readthedocs.io/en/latest/getting_started.html#available-endpoints)