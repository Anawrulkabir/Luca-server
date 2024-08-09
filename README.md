Welcome to the backend repository of the Luca project! This guide will help you set up the backend after cloning it from GitHub.

## Prerequisites

Ensure you have the following installed on your machine:

- **Node.js** (v14 or higher)
- **npm** (v6 or higher)
- **Git**
- **MongoDB** (running locally or on a cloud service like MongoDB Atlas)

## Getting Started

### Clone the Repository

Clone the repository from GitHub and navigate to the project directory:

```bash
git clone https://github.com/anawrulkabir/Luca-server.git
cd Luca-server
```

### Set Up Environment Variables

To configure the necessary environment variables, follow these steps:

1. **Create the `.env` file:**

   Inside the `Luca-server` directory, create a file named `.env`.

   ```bash
   touch .env
   ```

2. **Add the following environment variables to the `.env` file:**

   ```bash
   DB_USER=your_database_user
   DB_PASS=your_database_password
   STRIPE_SECRET_KEY=your_stripe_secret_key
   TRANSPORTER_EMAIL=your_email_for_transporter
   TRANSPORTER_PASS=your_email_password_for_transporter
   ACCESS_TOKEN_SECRET=your_access_token_secret
   ```

   Replace the placeholders (`your_database_user`, `your_stripe_secret_key`, etc.) with your actual configuration values.

### Install Dependencies

Install the required dependencies:

```bash
npm install
```

### Run the Development Server

Start the backend server:

```bash
npm start
```


### Access the Application

The backend server will typically run on `http://localhost:8000`. Ensure that your frontend is correctly configured to communicate with this backend.
