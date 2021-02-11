
## Project specific

```shell
heroku run python manage.py migrate
heroku run python manage.py createsuperuser
heroku run python manage.py search_index --rebuild -f
heroku run python manage.py books_create_test_data
heroku run python manage.py search_index --delete -f
heroku run python manage.py elasticsearch_remove_indexes --with-protected --dry-run
```
