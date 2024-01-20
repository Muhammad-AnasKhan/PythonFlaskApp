# To create python flask app

- setup create virtual venv
- activate venv
- pip install flask

## create app.py file

```python
from flask import Flask
app = Flask(__name__)

@app.route("/")
def home():
    return "Salam o Alaikum 🫡"

```

## To run flask app

```bash
flask --app  .\app.py run
or
python -m flask --app  .\app.py run
```
