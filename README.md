#Rest Server

The rest  server is a RESTful service that will add 
the tests into and receive the results from 
the database. The endpoints for the service are

- POST /test
- GET /test

All data is passed using JSON.
```javascript
{ URL: "", state: "" }
```

##Usage

The rest service requires four parameters.

### Parameters
- MYSQL_HOST={ mysql hostname } 
- MYSQL_USERNAME={ mysql username } 
- MYSQL_PASSWORD={ mysql password } 
- MYSQL_DATABASE={ mysql database } 

example...
```bash 
MYSQL_HOST=localhost \
MYSQL_USERNAME=myser \
MYSQL_PASSWORD=mypassword \
MYSQL_DATABASE=aginic \
npm start
```

