# API

## Sign In Google
### Request
#### POST /auth/google-signin
##### Body Request
```json
  {
    "accessToken": "string,required"
  }
```
##### Body Response
```json
  {
    "token": "string",
    "user": {
      "id": "int",
      "name": "string",
      "email": "string",
      "picture": "string",
      "phone": "string",
      "createdAt": "int",
      "updatedAt": "int"
    }
  }
```


## Sign In (Tanpa Google)
### Request
#### POST /auth/google-signin
##### Body Request
```json
  {
    "name": "string,required",
    "email": "string,required",
    "phone": "string"
  }
```
##### Body Response
```json
  {
    "token": "string",
    "user": {
      "id": "int",
      "name": "string",
      "email": "string",
      "picture": "string",
      "phone": "string",
      "createdAt": "int",
      "updatedAt": "int"
    }
  }
```
