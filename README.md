# Pass Vault Backend

This is the backend component of the Pass Vault application. It provides the necessary APIs and functionality to securely store and retrieve passwords.

## Prerequisites

Before running the Pass Vault Backend, make sure you have the following installed:

- Node.js (version 20)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/pass-vault-backend.git
   ```

2. Install the dependencies:

   ```bash
   cd pass-vault-backend
   npm install
   ```

3. Configure the environment variables:

   Create a `.env` file in the root directory of the project and provide the following variables:

   ```plaintext
   PORT=3000
   MONGODB_URI=mongodb://localhost:27017/pass-vault
   JWT_SECRET=7680727ce8e4505580c302c8521b729b271edac9479b69323bca00542e4277fa
   ```

   Adjust the values according to your setup.

4. Start the server:

   ```bash
   npm start
   ```

   The backend server will start running on `http://localhost:5000`.

## License

This project is licensed under the [MIT License](./LICENSE).
