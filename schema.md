MVP Schema
==========

User:
-----
* id
* name
* email
* current_location - geocode at login
* contributions - has many contributions
* stories - has many stories
* created_at
* updated_at

Story:
------
* id
* title
* origin longitude
* origin latitude
* contributions - has many contributions
* contribution limit
* completed boolean
* created_at
* updated_at

Contribution:
-------------
* id
* user: - belongs to a user
* story - belongs to a story
* content
* longitude
* latitude
* created_at
* updated_at

