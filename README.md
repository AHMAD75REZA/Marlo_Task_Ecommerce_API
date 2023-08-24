# Marlo_Task_Ecommerce_API
I would like to explain some points regarding working this project

1. Registration API:
 Accepts a POST request at the /register endpoint.
 Requires a JSON request body containing "first_name" and "last_name".
 Successfully registers a new user and responds with a JSON message confirming the registration.
 
2. Login API:
 Accepts a POST request at the /login endpoint.
 Requires a JSON request body containing "username" and "password".
 Validates the credentials and responds with a success message if the credentials are correct, or an error message if they are not.

 3. Product Upload API:
 Accepts a POST request at the /upload_products endpoint.
 Supports uploading a CSV file containing product data.
 
4. Product Review API:
 Accepts a POST request at the /submit_review endpoint.
 Requires a JSON request body containing "product_id", "review_text", and "rating".
 Stores the product review and rating.

6. Product View Pagination API:
 Accepts a GET request at the /get_products endpoint.
 Supports pagination by allowing the client to specify the page number.
 Sorts the products by review rating in descending order.
 
