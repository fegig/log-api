# log-api
##API Documentation

###Register User

###Endpoint: POST /register


###Controller Action: [AuthController::class, 'register']


###Purpose: Registers a new user.


###Request Body (JSON):
... {
    "name": "John Doe",
    "email": "john.doe@example.com",
    "password": "secretpassword"
}
...
