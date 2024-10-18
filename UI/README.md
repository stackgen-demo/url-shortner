
# flask-url-shortener-ui
URL Shortener UI in Python Flask host on S3 

## Running Standalone:

```bash
$ pip install -r requirements.txt
$ export TINY_API_URL=https://tiny-api.mydomain.com/create
$ export X_API_KEY=someRandomSecretKey09876543210
$ gunicorn -w 2 -b 0.0.0.0:8080 --access-logfile=/dev/stdout --error-log=/dev/stderr app:app
```

