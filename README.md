# Node.js MongoDB Showcase Projects


This is a personal project series based on the lessons by @anonystick ([https://github.com/anonystick](https://github.com/anonystick)).
## 1. [Authentication and API Key Management (HS256)](https://github.com/phamhung075/2-nodejs_mongodb_wc_showCase_Dynamic_for_ApiKey_and_Permissions_HS256/tree/master)

## 2. [ErrorHandler ApiResponse](https://github.com/phamhung075/3-nodejs_mongodb_wc_showCase_ErrorHandler_API)

## 3. [Success Handler ApiResponse](https://github.com/phamhung075/4-nodejs_mongodb_wc_showCase_ApiResponseUseClass/tree/master?tab=readme-ov-file)

## 4. [SignUp and Login Public Access](https://github.com/phamhung075/5-nodejs_mongodb_wc_showCase_SignUpLogin)

## 5. [Logout Authentication](https://github.com/phamhung075/6-nodejs_mongodb_wc_showCase_LogoutAuthentication)
## 6. [Refresh Token and Token Verification](https://github.com/phamhung075/7-nodejs_mongodb_wc_showCase_RefreshToken_verifyToken)
## 7. [Schema for Products in E-commerce](https://github.com/phamhung075/8-nodejs_mongodb_wc_showCase_Schema_Products_Ecommerce)
## 8. [API for Products Using Factory Pattern](https://github.com/phamhung075/11-nodejs_mongodb_wc_showCase_Api_Service_use_Factory_Pattern_Products_Senior_lv)

## 9. [API Service for Product Draft, Publish, and Unpublish](https://github.com/phamhung075/12-nodejs_mongodb_wc_showCase_Api_Service_Products_isDraft_isPublish_unPublish)
## 10. API Service for Product Data Retrieval

### Introduction

`13-nodejs_mongodb_wc_showCase_Api_Service_Products_findAll_findOne_selectData_unSelectData` is a Node.js application designed to showcase advanced data retrieval techniques for products in a MongoDB database. This project focuses on implementing various methods to find and select product data, providing flexibility in how data is queried and presented.

### Installation

- Clone the repository:

    `git clone https://github.com/phamhung075/13-nodejs_mongodb_wc_showCase_Api_Service_Products_findAll_findOne_selectData_unSelectData.git`
    
- Change to the directory:

    `cd 13-nodejs_mongodb_wc_showCase_Api_Service_Products_findAll_findOne_selectData_unSelectData`
    
- Install dependencies:
 
    `npm install`
    

### Features

- **Product Service** (`./services/product.service.js`): Implements methods for finding all products, finding a single product, and selectively including or excluding data fields.
- **Product Repository** (`./repositories/product.repo.js`): Manages database interactions for product queries.
- **Product Controller** (`./controllers/product.controller.js`): Handles API requests for product data retrieval, leveraging service and repository layers.
- **Utilities** (`./utils/utils.js`): Provides utility functions to support data retrieval operations.

### Usage

- Demonstrates various ways to retrieve product data, including finding all products, finding specific products, and customizing the selection of data fields. This function can call by user not registered
- Offers a modular and efficient approach to handling product queries in a web application.

### MongoDB Connection

- Connect to MongoDB using: `mongodb://localhost:27017/yourDatabase`

### Postman Examples

- **Get All Products**:
    - POSTMAN request details for fetching all products.
- **Get Specific Product**:
    - POSTMAN request details for fetching a specific product.

### Additional Notes

- This project is an excellent resource for developers looking to implement advanced query capabilities in MongoDB-based applications.
- The approaches used can be adapted or extended to suit different types of data retrieval requirements in web applications.

### Postman Examples

- **Signup**, **Login**, **Logout** examples as in the previous project.
- **Token Refresh** examples as in the previous project.
- **Create Product** examples as in the previous project.
- **Publish Product** examples as in the previous project.
- **UnPublish Product** examples as in the previous project.
- **get all Draft Products** examples as in the previous project.
- **get all Published Products** examples as in the previous project.
- **Find Product** examples
``` 
@url_dev=http://localhost:3052/v1/api/product/

### Find Product
GET {{url_dev}}/[PRODUCT_ID]
Content-Type: application/json
x-api-key: [API_KEY]
```
- **Find All Products** examples
``` 
@url_dev=http://localhost:3052/v1/api/product/

### Find All Products
GET {{url_dev}}
Content-Type: application/json
x-api-key: [API_KEY]
```
- **Search Products by name** examples
``` 
@url_dev=http://localhost:3052/v1/api/product/

### Search Products by name
GET {{url_dev}}/search/[keysearch]
Content-Type: application/json
x-api-key: [API_KEY]
```

For more detailed examples, refer to see [README.png](./help13.png).
