## Description

This project is a web application for managing a car dealership's inventory and customer accounts. It includes features for user authentication, inventory management, and administrative functions. The application is built using Node.js, Express, and PostgreSQL, with EJS templating for the front-end.

## Installation

install the necessary dependencies using npm:

```bash
npm install
```

create a postgresql database and configure the connection settings in the `.env` file.

with the following variables:

```
SESSION_SECRET=your_session_secret_here
DATABASE_URL=your_database_connection_string_here
PORT=your_port_number_here
PGSSLMODE=require
ACCESS_TOKEN_SECRET=your_access_token_secret_here
```

then run the app by executing:

```bash
npm start
```

### Admin Account

An admin account has been created for testing purposes:
- Email: tony@gmail.com
- Password: Admin123?