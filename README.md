# nodejs_mongodb_wc_showCase_Api_Service_Products_findAll_findOne_selectData_unSelectData

## Description
This is a Node.js API service utilizing MongoDB for showcasing products. It includes functionality to find all products, find a specific product, and select or unselect certain data fields.

## Installation
To set up this project, please follow these steps:
1. Clone the repository: `git clone [repository URL]`
2. Change to the project directory: `cd nodejs_mongodb_wc_showCase_Api_Service_Products_findAll_findOne_selectData_unSelectData`
3. Install necessary dependencies: `npm install`

## Usage
The API offers the following endpoints:

- **GET `/products`**: Retrieve all products.
  - Endpoint: `GET http://localhost:3052/products`
  - Example: Refer to [postman - get all product.md](./postman%20-%20get%20all%20product.md)

- **GET `/products/:id`**: Retrieve a single product by ID.
  - Endpoint: `GET http://localhost:3052/products/:id`
  - Example: See [postman - get product.md](./postman%20-%20get%20product.md)

- **Select/Unselect Data**: Customize which data fields to return.
  - Usage details are included in the codebase.

## MongoDB Connection
Connect to the MongoDB server using: `mongodb://localhost:27017`

## Contributing
We welcome contributions. To contribute, please:
1. Fork the repository.
2. Create a new feature branch.
3. Commit your changes.
4. Push to the branch and submit a pull request.
   
For more detailed examples, refer to see [README.png](./README.png).

## License
This project is available under the [MIT License](LICENSE.md).
