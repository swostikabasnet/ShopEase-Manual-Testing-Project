# API Testing for ShopEase(For products and users)

## Products
### 1. GET
#### GET all products:
- Method: GET
- Endpoint: http://localhost:3000/products
- Expected: Status 200, list of all products

#### GET single product by id :
- Method: GET
- Endpoint: http://localhost:3000/products/1
- Expected: Status 200, correct product data 

### 2. POST
#### Add/Create a new product:
- Method : POST
- Endpoint: http://localhost:3000/products
- Expected: Status 201, product created

### 3. PUT
#### Update the product:
- Method : POST
- Endpoint: http://localhost:3000/products
- Expected: Status 200, updated data 

### 4. DELETE
#### Delete a product
- Method : DELETE
- Endpoint: http://localhost:3000/products/1
- Expected: Status 200, product deleted


## Users
### 1. GET
#### GET all users:
- Method: GET
- Endpoint: http://localhost:3000/users
- Expected: Status 200, list of all users

#### GET user by id:
- Method: GET
- Endpoint: http://localhost:3000/users/1
- Expected: Status 200, correct user data 
