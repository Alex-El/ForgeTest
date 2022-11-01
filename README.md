# ForgeTest

### Docker deploy to Heroku:

0. heroku login
1. cd /docker dir/
2. heroku login
3. sudo docker login --username=_ --password=$(heroku auth:token) registry.heroku.com
4. sudo heroku container:push web -a /app name/
5. sudo heroku container:release web -a /app name/
