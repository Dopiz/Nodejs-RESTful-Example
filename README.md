# Nodejs-RESTful-Example

```
node server.js
```

## POST
```
curl -X POST --data '{Something}' --header 'Content-Type: text/plain' http://localhost:3000/todo 
```
## GET (Default)
```
curl -X GET http://localhost:3000/todo/:id
curl http://localhost:3000/todo
```
## PUT
```
curl -X PUT --data '{Something}' --header 'Content-Type: text/plain' http://localhost:3000/todo/:id
```
## DELETE
```
curl -X DELETE http://localhost:3000/todo/:id
```
