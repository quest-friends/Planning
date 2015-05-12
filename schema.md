1. Currently Harriet's schema ramblings. Edit at will.

```
User:
id
name
email
current_location - geocode at login
friends -> has many users
contributions -> has many contributions
stories -> has many stories
inbox -> has many stories pending contribution
created_at
updated_at

Story:
id
title
origin geocode
contributions -> has many contributions
users -> has many users who have contributed
current_user - > user who has been tagged
created_at
updated_at

Contribution:
id
user: -> belongs to a user
story -> belongs to a story
content
geocode
created_at
updated_at
```
