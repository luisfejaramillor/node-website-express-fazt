API for managing products - WomenWhoCode

This API allows users to manage products by creating, reading, updating, and deleting them. It uses Express.js and Joi for validation.


Setup


Clone the repository to your local machine.

Install dependencies by running npm install.

Create a .env file with your environment variables.

Run the server by running npm start.


Usage

The API has the following endpoints:



GET /api/v1/products: Get a list of all products.

POST /api/v1/products: Create a new product.

PATCH /api/v1/products/:id: Update a product by ID.

DELETE /api/v1/products/:id: Delete a product by ID.


To create a product, make a POST request to /api/v1/products with a JSON body containing the following fields:



name (required, string)

description (required, string)

price (required, number)

qty (required, number)

category (required, number)

id (forbidden)


To update a product, make a PATCH request to /api/v1/products/:id with a JSON body containing the fields you want to update.


To delete a product, make a DELETE request to /api/v1/products/:id.


Technologies used


Express.js

Joi


Contributions

This project is open for contributions. Please submit a pull request or issue if you would like to contribute.


Acknowledgements


Developers at Mint Bean Hackathon for providing the challenge for this project.

Express.js documentation

Joi documentation
