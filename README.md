# laravel-task

Task: Build a Laravel REST API

In this task, you will be building a REST API using Laravel. The API will provide CRUD operations for managing a list of products. Each product should have a name, description, price, and an image URL.

Requirements:

1. Build a Laravel project with a single RESTful endpoint for managing products.

2. The endpoint should support the following operations:
* GET /products: Get a list of all products.
* GET /products/{id}: Get a single product by its ID.
* POST /products: Create a new product.
* PUT /products/{id}: Update an existing product.
* DELETE /products/{id}: Delete an existing product.

3. Implement data validation to ensure that all required fields are present and have valid data.

4. Also add Google verification V3 before submiting data in the front-end form (https://developers.google.com/recaptcha/docs/v3)

5. Use Laravel's Eloquent ORM to interact with the database.

6. Use Laravel's built-in authentication system to secure the API.

7. Implement pagination to limit the number of products returned in a single request.

8. And add a UI for the API to visible the data.  

Bonus points:

* Implement search and filtering capabilities for the product list.
* Implement an endpoint for uploading product images.

Deliverables:

* A GitHub repository containing the Laravel project and any associated files.
* A README file with instructions on how to set up and run the project, including any required dependencies.
* A brief write-up explaining your design decisions and any trade-offs you made.

