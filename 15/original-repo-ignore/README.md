# README

**This project is just for Docker course use, which doesn't really do anything.**

## Dependencies

Of course you need Python3 environment. The example runs with Python3.8.

Python modules: Flask

So you may need to install flask `pip install Flask`

## Run the project

Execute the script app.py.

Then, the API http://127.0.0.1:5000/ should respond you with a string "Hello, World!".

### Run docker

```
docker build . -t flask-example
docker run -d -p 5000:5000 flask-example
```

