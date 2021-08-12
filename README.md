# Fashion Cloud

REST API that exposes methods to interact with a cache.

## GET request  /cache

This API Path will list down all cache entries that exists in a database.

## GET request  /cache/{key}

This API will return the particular information against the provided key

## POST request  /cache/{key}

This API will add a key in the database against the information provided

## DELETE request /cache/{key}

This API will delete the particular entry against the key provided

## DELETE request /cache

This API call will remove all entries from database

## Run project

1) Install app dependencies.
```javascript
npm install
```

2) Run the tests
```javascript
npm run test
```
3) Run APP
```javascript
node app.js
```
