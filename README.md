# ShopExpress - Node.js MySQL E-commerce Platform

A full-featured e-commerce platform built with Node.js, Express.js, and MySQL, following the MVC architecture pattern.

## Features

- 🛍️ **Product Management**
  - Add, edit, and delete products
  - Product listing with details
  - Product image management
  
- 🛒 **Shopping Cart**
  - Add/remove items
  - Update quantities
  - Real-time cart updates
  
- 🔐 **User Management**
  - User authentication
  - User profiles
  - Order history
  
- 📦 **Order Processing**
  - Checkout process
  - Order management
  - Order history tracking
  
- 👨‍💼 **Admin Panel**
  - Product management
  - Order management
  - User management

## Tech Stack

- **Backend:** Node.js, Express.js
- **Database:** MySQL with Sequelize ORM
- **Frontend:** EJS templating engine
- **Styling:** CSS
- **Authentication:** Session-based auth

## Prerequisites

- Node.js (v12 or higher)
- MySQL Server
- npm or yarn

## Installation

1. Clone the repository
```bash
git clone https://github.com/sajid73/nodejs-mysql.git
cd nodejs-mysql
```

2. Install dependencies
```bash
npm install
```

3. Configure environment variables
Create a `.env` file in the root directory and add:
```env
DB_NAME=your_database_name
DB_USER=your_database_user
DB_PASSWORD=your_database_password
DB_HOST=localhost
```

4. Initialize the database
```bash
npm run init-db   # If this script exists in package.json
```

5. Start the development server
```bash
npm start
```

The application will be available at `http://localhost:3000`

## Project Structure

```
├── app.js                 # Application entry point
├── controllers/          # Route controllers
├── models/              # Database models
├── routes/              # Application routes
├── views/              # EJS templates
├── public/             # Static files
└── util/               # Utility functions
```

## Available Scripts

- `npm start` - Starts the development server with nodemon
- `npm run start-server` - Starts the server without nodemon

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the ISC License.

## Author

Originally created by Maximilian Schwarzmüller
Modified by sajid73
