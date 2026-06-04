# Node.js + MySQL Skeleton API

A robust backend boilerplate/skeleton using Node.js, Express, and MySQL (with Sequelize ORM). This skeleton comes pre-configured with essential tools for authentication, security, and file uploading.

## Features

- **Express.js Server**: Fast, unopinionated, minimalist web framework.
- **MySQL & Sequelize**: Relational database integration with Sequelize ORM.
- **Authentication**: Secure password hashing with `bcryptjs` and token-based authentication with `jsonwebtoken` and `express-jwt`.
- **File Uploads**: Form data and file upload parsing using `formidable` and `form-data`.
- **Security & Utilities**: CORS enabled, environment variables via `dotenv`, and handy utilities with `lodash` & `crypto`.
- **Modern JavaScript**: Configured to use ES Modules (`type: "module"`).
- **Development Environment**: Hot-reloading enabled via `nodemon` (dev dependency).

## Prerequisites

Before starting, make sure you have the following installed:
- [Node.js](https://nodejs.org/) (v14 or higher recommended)
- [MySQL Server](https://dev.mysql.com/downloads/mysql/)

## Installation

1. Clone the repository or download the skeleton.
2. Install the project dependencies:
   ```bash
   npm install