# log-api
## API Documentation

### Register User

* Endpoint: POST /register
* Controller Action: [AuthController::class, 'register']
*  Purpose: Registers a new user.

 #### equest Body (JSON):
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
  
#### Request Body (JSON):
```javascript
{
    "email": "john.doe@example.com",
    "password": "secretpassword"

}
```
### List Products

* Endpoint: GET /products
* Controller Action: [ProductController::class, 'index']
*Purpose: Retrieves a list of all products.

### Get Product by ID
* Endpoint: GET /products/{id}
* Controller Action: [ProductController::class, 'show']
* Purpose: Retrieves a specific product by its ID.
* Example: GET /products/1 to retrieve product with ID 1.

### Search Products by Name
* Endpoint: GET /products/search/{name}
* Controller Action: [ProductController::class, 'search']
* Purpose: Searches for products by name.
+ Example: GET /products/search/apple to search for products with "apple" in the name.
