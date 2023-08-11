Retrieve all products with pagination (GET): Send a GET request to http://localhost:8000/api/products.

Retrieve a specific product (GET): Send a GET request to http://localhost:8000/api/products/{id} where {id} is the product's ID.

Create a new product (POST): Send a POST request to http://localhost:8000/api/products with the necessary data in the request body.

Update a product (PUT): Send a PUT request to http://localhost:8000/api/products/{id} with the updated data in the request body. Use RAW for updating data using Postman , not form-data. Example : { "name" : "BOAT UPDATED" }

Upload a photo for a product (POST): Send a POST request to http://localhost:8000/api/products/{id}/photo using the form-data option to upload an image.

Delete a product (DELETE): Send a DELETE request to http://localhost:8000/api/products/{id} where {id} is the product's ID.