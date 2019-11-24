
https://deparkes.co.uk/2018/03/02/simple-docker-flask-sqlite-api/


An example of a flask api running in a docker container.

Extends example of a Flask API from [programminghistorian.org](http://programminghistorian.github.io/ph-submissions/lessons/creating-apis-with-python-and-flask)

# Requirements
[docker](https://www.docker.com/get-docker)

# Usage
Clone this repository
```
git clone https://github.com/deparkes/docker_flask_example.git
```

Run docker-compose
```
docker-compose up --build
```

Test localhost api in your browser by navigating to
```
http://localhost:5000/api/v1/resources/books/all
```

## Heroku

- docker build -f Dockerfile.myflask -t myflask .
docker-compose up --build

- heroku container:login
- heroku container:push web --app testa-api-ufma
- heroku container:release web --app testa-api-ufma


- docker build -f Dockerfile.myflask -t myflask .