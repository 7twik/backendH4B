# Backend Server

This is the backend server for our ecommerce website. It is built using Node.js and Express.js, and it is connected to a MongoDB database.

## Description

The backend server acts as the intermediary between the frontend user interface and the MongoDB database. It handles various API endpoints for managing vendor information, customer queries, and payment transactions.

## Technologies Used

- Node.js: A JavaScript runtime environment for server-side development.
- Express.js: A web application framework for Node.js that provides robust routing and middleware capabilities.
- MongoDB: A NoSQL database for storing and managing data.
- Mongoose: An object data modeling (ODM) library for MongoDB and Node.js.

## Installation

1. Clone the repository: `git clone https://github.com/7twik/backendH4B`
2. Navigate to the project directory: `cd your-project`
3. Install the dependencies: `npm install`

## Configuration

1. Rename the `.env.example` file to `.env`.
2. Update the environment variables in the `.env` file to match your MongoDB configuration.

## Usage

1. Start the server: `npm start`
2. The server will be running on `http://localhost:8009`.

## Models

1. ItemModel
2. Pin
3. User
4. userScheme
5. web3db

## Packages

1. bcrypt
2. dotenv
3. bycryptjs
4. cookie-parser
5. cors
6. express
7. jsonwebtoken
8. mongoose
9. validator

## API Endpoints

- /api/customers/register POST
- /api/customer/login POST
- /api/web3/order POST
- /api/web3/customer POST
- /api/web3/customerdone GET
- /api/web3/customeraccept POST
- /api/web3/customerdeny POST
- /api/web3/hawker GET
- /api/web3/hawkerdone GET
- /api/web3/hawkeraccept POST
- /api/web3/hawkerreach POST
- /api/web3/hawkerrecieve POST
- /api/web3/hawkerdeny POST
- /api/web3/admin GET
- /api/users/register POST
- /api/users/login POST
- /api/users/block POST
- /api/users/admin GET
- /api/pins/POST
- /api/pins/del POST
- /api/pins/GET
- /api/pins/updatepins POST
- /api/pins/category GET
- /api/pins/block POST
- /api/items/POST
- /api/items/del POST
- /api/items/deleteAll POST
- /api/items/GET

## Contributing

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature/your-feature`
5. Submit a pull request.

## License

This project is built for Hack4Bengal 2.0. 