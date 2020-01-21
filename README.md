# hello_flask
Simplest hello word for Python Flask web frame work


The installation of Flask is very simple if we use pip. We just need to type the following:

`pip install Flask`

```python
from flask import Flask
app = Flask(__name__)

@app.route("/")
def hello():
    return "Hello World!"

if __name__ == "__main__":
    app.run()
```
### How it works?
First step is importing Flask into your code:
```python
from flask import Flask
```
This you have to create an instance of Flask class inorder to start your application:
```python
`app = Flask(__name__)`
```
To create your first routeyou need these 3 lines of code:
```python
@app.route("/")
def hello():
    return "Hello World!"
```
First line tells that we want to have a URL called "/", after that we define our handler and inside that a "Hello World!" has been returned. like a piece of cake :)
You can run this project like this:
```
python booy.py
```
Or
```
python3 booy.py
```
The default port for Flask is 5000, so you can see your Hello World! this way:
```
http://localhost:5000
```

Have fun and welcome to the world of Flask framework
