# log-api
## API Documentation
## Base URL https://demo.c0de-8.com/api
### Register User

* Endpoint: POST /register
*  Purpose: Registers a new user.

 #### Request:
```javascript
{
    "name":"chovwe",
    "email":"chovwe",
    "password":"1234",
    "password_confirmation":"1234"

}
```

 #### Response Format:
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
* Purpose: Logs in a user and generates an authentication token.
  
#### Request:
```javascript
{
    "email": "john.doe@example.com",
    "password": "secretpassword"

}
```
#### Response Format:
```javascript
{
    "email": "john.doe@example.com",
    "password": "secretpassword"

}
```
### List Products

* Endpoint: GET /products
*Purpose: Retrieves a list of all products.

### Get Product by ID
* Endpoint: GET /products/{id}
* Purpose: Retrieves a specific product by its ID.
* Example: GET /products/1 to retrieve product with ID 1.

### Search Products by Name
* Endpoint: GET /products/search/{name}
* Purpose: Searches for products by name.
+ Example: GET /products/search/apple to search for products with "apple" in the name.
