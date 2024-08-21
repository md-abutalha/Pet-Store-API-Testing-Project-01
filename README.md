 # Pet Store API Testing Project

 
**Pet-Store-API-Testing-Project-01**.  
[![Postman](https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg)](https://www.postman.com/)

This repository contains REST API Testing using Postman, focusing on the Pet Store API. It includes scripts for testing both JSON and XML data formats, demonstrating how to create, retrieve, update, and delete users and pets via the Pet Store API.

## Table of Contents
- [JSON Testing](#json-testing)
  - [Create User](#create-user)
  - [Get User by ID](#get-user-by-id)
  - [Update User by ID](#update-user-by-id)
  - [Delete User by ID](#delete-user-by-id)
- [XML Testing](#xml-testing)
  - [Add New Pet](#add-new-pet)
  - [Find Pet by ID](#find-pet-by-id)
  - [Update Existing Pet Details](#update-existing-pet-details)
  - [Delete Pet](#delete-pet)
- [Published Documentation](#published-documentation)

## JSON Testing

### Create User

**Endpoint:** POST https://petstore.swagger.io/v2/user

bash
curl -X 'POST' \
  'https://petstore.swagger.io/v2/user' \
  -H 'accept: application/json' \
  -H 'Content-Type: application/json' \
  -d '{
  "id": 0,
  "username": "john",
  "firstName": "john",
  "lastName": "Ripper",
  "email": "john@gmail.com",
  "password": "johnpass",
  "phone": "9482929592",
  "userStatus": 1
}'

Request Headers:

- accept: application/json
- Content-Type: application/json

Request Body (JSON):
{
  "id": {{id}},
  "username": "{{username}}",
  "firstName": "{{firstName}}",
  "lastName": "{{lastName}}",
  "email": "{{email}}",
  "password": "{{password}}",
  "phone": "{{phone}}",
  "userStatus": {{userStatus}}
}

Get User by ID
Endpoint: GET https://petstore.swagger.io/v2/user/{{id}}

Update User by ID
Endpoint: PUT https://petstore.swagger.io/v2/user/{{id}}

Request Body (JSON):
{
  "id": {{id}},
  "username": "{{username}}",
  "firstName": "{{firstName}}",
  "lastName": "{{lastName}}",
  "email": "{{email}}",
  "password": "{{password}}",
  "phone": "{{phone}}",
  "userStatus": {{userStatus}}
}

# Pet Store API Testing Project


This repository contains REST API Testing using Postman, focusing on the Pet Store API. It includes scripts for testing both JSON and XML data formats, demonstrating how to create, retrieve, update, and delete users and pets via the Pet Store API.

## JSON Testing

### Create User

**Endpoint:** `POST https://petstore.swagger.io/v2/user`

curl -X 'POST' \
  'https://petstore.swagger.io/v2/user' \
  -H 'accept: application/json' \
  -H 'Content-Type: application/json' \
  -d '{
  "id": 0,
  "username": "john",
  "firstName": "john",
  "lastName": "Ripper",
  "email": "john@gmail.com",
  "password": "johnpass",
  "phone": "9482929592",
  "userStatus": 1
}'

# Request Headers:

accept: application/json
Content-Type: application/json

# Request Body (JSON):
json
Copy code
{
  "id": {{id}},
  "username": "{{username}}",
  "firstName": "{{firstName}}",
  "lastName": "{{lastName}}",
  "email": "{{email}}",
  "password": "{{password}}",
  "phone": "{{phone}}",
  "userStatus": {{userStatus}}
}

# Get User by ID
-Endpoint: GET https://petstore.swagger.io/v2/user/{{id}}

# Update User by ID
-Endpoint: PUT https://petstore.swagger.io/v2/user/{{id}}

# Request Body (JSON):

json
Copy code
{
  "id": {{id}},
  "username": "{{username}}",
  "firstName": "{{firstName}}",
  "lastName": "{{lastName}}",
  "email": "{{email}}",
  "password": "{{password}}",
  "phone": "{{phone}}",
  "userStatus": {{userStatus}}
}

# Delete User by ID
-Endpoint: DELETE https://petstore.swagger.io/v2/user/{{id}}

## XML Testing

#Add New Pet
-Endpoint: POST https://petstore.swagger.io/v2/pet

curl -X 'POST' \
  'https://petstore.swagger.io/v2/pet' \
  -H 'accept: application/xml' \
  -H 'Content-Type: application/xml' \
  -d '
<?xml version="1.0" encoding="UTF-8"?>
<Pet>
  <id>0</id>
  <Category>
    <id>0</id>
    <name>string</name>
  </Category>
  <name>doggie</name>
  <photoUrls>
    <photoUrl>string</photoUrl>
  </photoUrls>
  <tags>
    <Tag>
      <id>0</id>
      <name>string</name>
    </Tag>
  </tags>
  <status>available</status>
</Pet>'


# Request Headers:

-accept: application/xml
-Content-Type: application/xml

#Request Body (XML):

<?xml version="1.0" encoding="UTF-8"?>
<Pet>
  <id>0</id>
  <Category>
    <id>0</id>
    <name>string</name>
  </Category>
  <name>doggie</name>
  <photoUrls>
    <photoUrl>string</photoUrl>
  </photoUrls>
  <tags>
    <Tag>
      <id>0</id>
      <name>string</name>
    </Tag>
  </tags>
  <status>available</status>
</Pet>

# Find Pet by ID
- Endpoint: GET https://petstore.swagger.io/v2/pet/{{petid}}

# Update Existing Pet Details
-Endpoint: PUT https://petstore.swagger.io/v2/pet

# Request Body (XML):

<?xml version="1.0" encoding="UTF-8"?>
<Pet>
  <id>{{petid}}</id>
  <Category>
    <id>0</id>
    <name>string</name>
  </Category>
  <name>tommy</name>
  <photoUrls>
    <photoUrl>string</photoUrl>
  </photoUrls>
  <tags>
    <Tag>
      <id>0</id>
      <name>string</name>
    </Tag>
  </tags>
  <status>available</status>
</Pet>

# Delete Pet
-Endpoint: DELETE https://petstore.swagger.io/v2/pet/{{petid}}

## Published Documentation
## Published Documentation
- JSON Testing Documentation: [https://documenter.getpostman.com/view/37041522/2sA3sAi8PA](https://documenter.getpostman.com/view/37041522/2sA3sAi8PA)
- XML Testing Documentation: [https://documenter.getpostman.com/view/37041522/2sAXjDdEfh](https://documenter.getpostman.com/view/37041522/2sAXjDdEfh)


# This project is intended to demonstrate API testing using Postman. Feel free to clone this repository and adapt the tests to your own API testing needs.

Md. Abu Talha  
[GitHub Profile](https://github.com/md-abutalha)  
E-Mail: abutalha03333@gmail.com
