# LUA Cosmetic

## Overview
Welcome to the **LUA Cosmetic**.This is an e-commerce platform designed to provide many options for customers in terms of cosmetics. Our mission is to provide a safe and accessible shopping experience for everyone.

## Technologies
This project is built with robust and modern technologies to ensure high performance and scalability:
- EJS templates for rendering HTML pages.
- Prisma ORM for database access.
- MySQL database.
- Environment variables using dotenv.
- Tailwind CSS for styling.
- ESLint and Prettier for code linting and formatting.
- Nodemon for auto-reloading the server during development.
- Winston for logging.
- Express-validator for request validation.
- Helmet for securing the app by setting various HTTP headers.
- Compression for compressing the response data.
- Morgan for logging HTTP requests.
- Vite for building the frontend assets. Support - HMR (Hot Module Replacement) in development mode.
- Build the frontend assets with npm run build.

## Our mockup: 
[https://github.com/uydeptrai/Web-Final](https://stirring-stroopwafel-2e38e7.netlify.app/productpage)

## Detail of the project
- [Wireframe](content/wireFrame/README.md)
- [Planning](content/Planning/README.md)
- [Task](content/Task/README.md)
- [ERD diagram](content/databaseimg/README.md)
- [ScreenShot](content/screenshot/README.md)

## Prerequisites

Before running this project, ensure you have the following installed:

- [Node.js](https://nodejs.org/en/download/)
- [MySQL](https://dev.mysql.com/downloads/mysql/)
- [Git](https://git-scm.com/downloads)

## Project Structure

Here is an overview of the main directories and files in the project:

- **/controllers**: Contains the logic for handling requests and returning responses.
- **/views**: Contains the EJS templates for rendering HTML pages.
- **/config**: Holds configuration files for the database connection and environment variables.
- **/public**: Static files like CSS, JavaScript, and images.
- **server.js**: The main entry point of the application.
- **package.json**: Lists the project dependencies and scripts.

## Setup Instructions

1. **Clone the Repository**

```bash
git clone https://github.com/uydeptrai/Web-Final

cd WebDesignProject
cd webapp
```

2. **Install Dependencies**

Install all required dependencies using npm:

```bash
npm install
```

3. **Database Setup**

- Ensure MySQL is running on your machine.
- Create a new database called `apps`.
- Update the database configuration in environment variables (`.env` file).

Create `.env` like `.env.example` and set the values. For example:
```
PORT=3000
SITE_NAME="LBJ"
NODE_ENV=development
DATABASE_URL="mysql://root:password@localhost:3306/apps"
```

4. **Run Database Migrations**

Run the migrations to set up the database schema:

```bash
npx prisma migrate dev
```

5. **Seed the Database**

Populate the database with initial data:

```bash
node prisma/seed.js
```

6. **Start the Server**

If you want to run the server in production mode, use:
```bash
npm start
```

If you want to run in development mode, use:
```bash
npm run dev
```

### Reset Database

To reset the database, you could run the following command to undo all migrations and re-run them.
```
npx prisma migrate reset
node prisma/seed.js
```

## Contributors

1. uydeptrai - Hoàng Gia Uy
2. QL250904 - Lê Quang Lâm
3. Vophamthanhan - Võ Phạm Thành An


## Contact
* Email: Lam.le220912@vnuk.edu.vn

# Web-Final

## Home Page
![Trang chủ](https://github.com/uydeptrai/Web-Final/assets/74178707/84bb1fe6-93cf-4cfe-9b65-ec6c77138d21)
## Product Page
![Sản phẩm](https://github.com/uydeptrai/Web-Final/assets/74178707/d60a3bdc-afd5-4f19-8b86-091bb70450bb)
## Detailed Product Page
![Chi tiết sản phẩm](https://github.com/uydeptrai/Web-Final/assets/74178707/b5e58024-57f7-4066-97cc-a0a0a6337a78)
