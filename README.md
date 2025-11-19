
# 🧪Pet Store API Testing Project

<img width="310" height="163" alt="image" src="https://github.com/user-attachments/assets/d2677ec5-cdfb-4111-9107-ce0944e1c1bc" />

## 📖 Introduction
This project is dedicated to testing the functionalities of the Swagger Petstore API. It serves as a practical exercise in API testing, focusing on managing pets, stores, and user accounts through CRUD operations.

## ✨ Features
- Authentication: Implement API key–based authentication where required.

- Pet Management:

1. Add new pets to the store.**

2. Retrieve pets by ID or status (available, pending, sold).**

3. Update existing pet details.**

4. Delete pets from the store.
-  Store Operations:

1. Place orders for pets.

2. Retrieve order details.

3. Manage inventory.

4. User Management:

- Create new users.

1. Log in and log out.

2. **Retrieve, update, and delete user accounts.

## 🛠️ Installation

Follow these steps to set up the project locally:

1. Install Node.js
   Download and install Node.js from the [official website](https://nodejs.org/).

2. Install Newman and HTML Extra Reporter
   Open your terminal and run:

   ```bash
   npm install -g newman
   npm install -g newman-reporter-htmlextra

3. Clone this repository:

   ```bash
   git clone https://github.com/mabdel130/API-testing-for-Swagger-Pet-store.git
   ```

4. Navigate to the project directory:**

   ```bash
   cd API-testing-Restful-Booker-Project
   ```

5. Import the Postman collection and environment into Postman:
   - Open Postman.
   - Import the provided `petstore.swagger.postman_collection` and `Petstore_Testing.postman_environment` files.

## 🚀 Usage

You can run the tests in two ways:

### Option 1: Run manually from Postman
- Open Postman.
- Choose the imported collection.
- Select the correct environment.
- Click **Run** to execute the test cases manually.

### Option 2: Run automatically using `run.bat`
- Locate the `run.bat` file inside the project directory.
- Double-click the `run.bat` file to start running the tests.
- This will automatically:
  - Run the Postman collection using Newman.
  - Generate an **HTML report** inside the `newman/` folder.


## 📄 Notes

- After the test execution, an HTML report will be available in the `newman` folder.
- If you face permission issues, run the terminal or `.bat` file as an administrator.
