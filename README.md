# PServe

Make your interactive command work as an HTTP server! :)

Currently Supports line-by-line commands, like Kytea and python interpreters.

## install

```
$ python setup.py install
``` 

## how to use

making Python interpreter work as HTTP server

```
$ pserve --port 8080 --command 'python -i -q'
...

$ curl localhost:8080?stdin="5-2"
>>> 3
```
