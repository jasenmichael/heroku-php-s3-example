# heroku-php-s3-example

### php hosted on Heroku connected to s3 bucket example


```
git clone https://github.com/jasenmichael/heroku-php-s3-example.git
cd heroku-php-s3-example

heroku create
## set heroku env 
heroku config:set AWS_ACCESS_KEY_ID=key-id AWS_SECRET_ACCESS_KEY=secret-key S3_BUCKET=bucket-name
git add -A 
git commit -m "file upload test form"
git push heroku master
```
