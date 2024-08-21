# Pet Store API Testing Project

**Pet-Store-API-Testing-Project-01**  
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

**Endpoint:** `POST https://petstore.swagger.io/v2/user`
@@@@@
Request Headers:

accept: application/json
Content-Type: application/json
Request Body (JSON):
@@@@@@@@

Get User by ID
Endpoint: GET https://petstore.swagger.io/v2/user/{{id}}

Update User by ID
Endpoint: PUT https://petstore.swagger.io/v2/user/{{id}}

Request Body (JSON): 

@@@@@

Delete User by ID
Endpoint: DELETE https://petstore.swagger.io/v2/user/{{id}}

XML Testing
Add New Pet
Endpoint: POST https://petstore.swagger.io/v2/pet

@@@@@

Request Headers:

- accept: application/xml
- Content-Type: application/xml
Request Body (XML):

@@@@@

Find Pet by ID
Endpoint: GET https://petstore.swagger.io/v2/pet/{{petid}}

Update Existing Pet Details
Endpoint: PUT https://petstore.swagger.io/v2/pet

Request Body (XML):

@@@@@

Delete Pet
Endpoint: DELETE https://petstore.swagger.io/v2/pet/{{petid}}

Published Documentation
JSON Testing Documentation: https://documenter.getpostman.com/view/37041522/2sA3sAi8PA
XML Testing Documentation: https://documenter.getpostman.com/view/37041522/2sAXjDdEfh

@@@@

This project is intended to demonstrate API testing using Postman. Feel free to clone this repository and adapt the tests to your own API testing needs.

Md. Abu Talha
GitHub Profile
E-Mail: abutalha03333@gmail.com




