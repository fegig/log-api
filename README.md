# log-api
## API Documentation

### Register User

* Endpoint: POST /register

* Controller Action: [AuthController::class, 'register']

#### Purpose: Registers a new user.


*  Request Body (JSON):
```javascript
{
    "name":"chovwe",
    "email":"chovwe",
    "password":"1234",
    "password_confirmation":"1234"

}
```
### Login User
* Endpoint: POST /login
  
* Controller Action: [AuthController::class, 'login']

* Purpose: Logs in a user and generates an authentication token.
####Request Body (JSON):
