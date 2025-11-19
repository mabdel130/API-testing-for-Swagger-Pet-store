
# 🧪Pet Store API Testing Project
https://www.google.com/imgres?q=pet%20store%20api%20documentation&imgurl=https%3A%2F%2Fassets.publish.postman.com%2Fog-image%3Fheading%3DCOLLECTION%26entityName%3DSwagger%2520Petstore%26entityType%3Dcollection-documentation%26imageUrl%3Dhttps%253A%252F%252Fres.cloudinary.com%252Fpostman%252Fimage%252Fupload%252Ft_team_logo%252Fv1%252Fteam%252Fdefault-H2%26isVerified%3Dfalse%26teamName%3DHex1&imgrefurl=https%3A%2F%2Fwww.postman.com%2Fmitshex1%2Fswagger-petstore%2Fdocumentation%2Fu3v1299%2Fswagger-petstore&docid=RuzcP_CdYrgJ9M&tbnid=QuhCaK_SChCkQM&vet=12ahUKEwiu0ZO9lv6QAxXuK_sDHcXqK4wQM3oECCoQAA..i&w=1200&h=630&hcb=2&ved=2ahUKEwiu0ZO9lv6QAxXuK_sDHcXqK4wQM3oECCoQAA

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
