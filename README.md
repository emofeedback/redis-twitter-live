# redis-twitter-live
redis -twitter
    0. Change config.py to set redislabs and twitter Authentication.
    1. run pip install -r requirements.txt
    2. Run with python serve.py --port=<preferred port>
    3. Send a post request to  http://localhost:<port>/<twitterhandle> and get a json string back format {'tweet': <html>}
