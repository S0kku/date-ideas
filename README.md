# Date ideas

## Functions in the application

* The user can create an account and log in to the application.
* The user can post date ideas in the application. The user can edit or delete any of their own posts.
* The user can see all posts added to the application.
* The user can search for posts by keyword.
* The application has user pages that show all posts added by a specific user.
* The user can select one or more categories for their post (e.g. art, food, games, sightseeing, price range).
* The user can add comments under posts with suggestions on how to make the date better.

## Instructions for installing

Install `flask`-library:

```
$ pip install flask
```

Create database tables & add basic categories:

```
$ sqlite3 database.db < schema.sql
$ sqlite3 database.db < init.sql
```

Run the application using:

```
$ flask run
```
