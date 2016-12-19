# house-server

## Requirements
* Python 2.7
* Flask
* pymongo
* requests
* gunicorn

## Tip

set your own database path.

`app.py`:
```
...

mongoClient = pymongo.MongoClient("mongodb://[YOUR_DB_PATH]")

...
```
