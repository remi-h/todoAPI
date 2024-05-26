# TODO LIST API

Simple Todo List API

To run:
``` zsh
python -m venv .venv
. .venv/bin/activate
pip install -r requirements.txt
```

to POST:
``` zsh
curl -X POST -H "Content-Type: application/json" -d '{"text":"apple"}' 'http://127.0.0.1:8000/items'
```