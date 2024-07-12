# EcomEdge

***Welcome to the repository for our ecommerce website (EcomEdge) built with the MERN stack (MongoDB, Express.js, React, and Node.js). This project aims to create a full-featured ecommerce platform that provides a seamless shopping experience for users.***

![Thumbnail](/thumb.png)

**Features:**

-   **User Authentication:** Securely register and log in users with password management.

-   **Product Listings:** Display products with detailed information, images, and reviews.

-   **Shopping Cart:** Add items to a persistent shopping cart, manage quantities, and apply discounts.

-   **Order Management:** Place orders, track their status, and manage past orders.

-   **Admin Panel:** Admin users can manage products, users, orders, and other aspects of the website.

-   **Payment Integration:** Secure payment processing using a reputable gateway.

-   **Responsive Design:** Adaptable layout for various devices (desktop, mobile, tablet).

## Project Structure of EcomEdge:

**EcomEdge/**<br>
├── **frontend/** **_React frontend code_**<br>
│ ├── **_src/_**<br>
│ │ ├── _components/_ => Reusable UI components<br>
│ │ ├── _pages/_ => React application pages<br>
│ │ ├── _services/_ => API interaction logic<br>
│ │ ├── _App.js_ => Main application root<br>
│ │ └── ... => Other frontend files<br>
├── **backend/** **_Node.js backend with Express_**<br>
│ ├── **_controllers/_** => API controller functions<br>
│ ├── **_models/_** => Mongoose data models for MongoDB<br>
│ ├── **_routes/_** => API routes<br>
│ ├── **_middlewares/_** => Middleware functions for authentication, authorization, etc.<br>
│ ├── **_config/_** => Configuration files (database, etc.)<br>
│ └── **_index.js_** => Server entry point<br>
├── **public/** => Static assets (images, fonts, etc.)<br>
├── **.env** => Environment variables for development and deployment<br>
└── **package.json** => Project dependencies and scripts<br>

**Getting Started:**

1. **Clone the repository:**

    ```bash
    git clone https://github.com/prashant-sagar-shakya/EcomEdge.git
    ```

2. **Install Dependencies:**

    ```bash
    cd frontend
    npm i
    cd ..
    npm i
    ```

3. **Configure environment variables:**
   Create a .env file in the root directory. Add the following environment variables:
    ```bash
    NODE_ENV=development
    PORT=5000
    MONGO_URI=<your-mongodb-connection-string>
    JWT_SECRET=<your-jwt-secret>
    PAYPAL_CLIENT_ID=<your-paypal-client-id>
    ```
4. **Run the Development Server:**
In the root directory of project run the command:
    ```bash
    npm run dev
    or,
    yarn dev
    ```
    This will start the server and typically open your browser to http://localhost:5173 from the vite server (the default port may vary).
