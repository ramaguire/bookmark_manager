#bookmark_manager

### To set up the database

Connect to `psql` and create the `bookmark_manager` database:

```
CREATE DATABASE bookmark_manager;
```

To set up the appropriate tables, connect to the database in `psql` and run the SQL scripts in the `db/migrations` folder in the given order.


# bookmark_manager user stories

As a web browser
So that I can access my favourite websites quickly
I would like to be able to view a list of all my bookmarked webpages

As a user
So that I can keep my bookmarks up to date
I would like to be able to add webpages to my list of bookmarks

As a user
So that I can keep my bookmarks up to date
I would like to be able to delete webpages from my list of bookmarks

As a user
So that I can keep my bookmarks up to date
I would like to be able to update webpages in my list of bookmarks

As a user
So that I can keep my bookmarks organised
I would like to be able to add comments to my bookmarks

As a user
So that I can keep my bookmarks organised
I would like to be able to tag my bookmarks into categories

As a user
So that I can access bookmarks quickly
I would like to be able to filter my bookmarks by tags

As a user
So that I can have sole use of my bookmarks
I would like to only be able to edit my bookmark list and not those of other users
