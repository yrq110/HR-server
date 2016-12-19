# house-server

api server for [HouseRadar](https://github.com/yrq110/HouseRadar).

## Requirements
* python 2.7
* flask
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
