# aegislabs
creating a simple REST API using Laravel framework with two endpoints
 
1. Create User API : 

curl --location 'http://127.0.0.1:8000/api/users' \
--header 'Content-Type: application/json' \
--data-raw '{
    "email": "example1@example.tes",
    "password": "example1",
    "name": "John Doe 2"
}'

2. Get Users API

curl --location --request GET 'http://127.0.0.1:8000/api/users' \
--header 'Content-Type: application/json' \
--data '{
    "search": "example",
    "page": 1,
    "sortBy": "name"
}'
