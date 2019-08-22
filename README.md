# Django Webpack Starter

Hello fellow human. The repo uses
```
Python 3.7.*
Django 2.2.*
Webpack 4.39.*
Bootstrap 4.3.*
Pipenv
```

## Installing

Run the following commands.

```
git clone git@github.com:khadegd/django-webpack-starter.git demo
python3 -m venv .venv
source .venv/bin/activate
pip install pipenv
pipenv install
yarn
```


### Hot reload:
```
yarn start
python manage.py runserver_plus 0.0.0.0:8000
```


### Development mode:
```
yarn run dev
python manage.py runserver_plus 0.0.0.0:8000
```


### Production mode:

```
yarn run prod
python manage.py runserver_plus 0.0.0.0:8000 --insecure
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Authors

* **Ganesh Khade** - [khadegd](https://twitter.com/khadegd)


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc

