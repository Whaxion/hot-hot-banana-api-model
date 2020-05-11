# Hot Hot Banana  WebSocket API model

![Scheme](https://raw.githubusercontent.com/Whaxion/hot-hot-banana-api-model/master/hot-hot-banana.svg)

## [01a-getToken](01a-getToken.json)
Get token if we don't already have one.
NOTE: Will actually create a new user in database.

## [01b-getUsername](01b-getUsername.json)
Get username if we already have a token.
NOTE: Use it when you're resuming an old session.
ANOTHER NOTE: You must have at least have done getToken once
