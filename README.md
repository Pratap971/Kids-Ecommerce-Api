# Kids-Ecommerce-API-Test
 
Url-(https://kids-e-commerce-front-backend-1.onrender.com/api/product/products)

## Prerequisites

- Install [Postman](https://www.postman.com/downloads/).
- Ensure the Kids-Ecommerce API is running.

## Setup

1. **Import Collection**: Import the Kids-Ecommerce API collection into Postman.
2. **Environment Setup**: Create an environment with the following variables:
   - `base_url`: Base URL(https://kids-e-commerce-front-backend-1.onrender.com/api/product/products) of the API.
   - `api_key`: API key (if required).
   - `booking_id`: (Optional) Used to store a Product ID.

## Test Cases 
We have 2 Test case Scenario:
1. Positive Endpoints:
   a) Get USER IDs
   b) Get Alluser Details
   c) Create User
   d) Update User
   e) Delete User
   

  3. Negative Endpoints:
     a) Get User Details Invalid Id
     b) Create User Invalid chars/id

## Running Tests

- Open the collection in Postman and click `Run`.
- Review results to ensure all tests pass.

## Troubleshooting

- **400**: Check request body.
- **401**: Verify API key.
- **500**: Check API server status.

# Newman:
Newman is a command-line tool used to run Postman collections. Here are the steps to install Newman:

Step 1: Install Node.js and npm
Newman requires Node.js and npm (Node Package Manager). If you don't have these installed, follow these steps:

Download Node.js:

Go to the Node.js official website.
Download the latest LTS version (which includes npm).
Install Node.js:

Run the installer and follow the installation instructions.
Ensure the option to install npm is checked during the installation.
Verify Installation:

Open a terminal or command prompt.

Run the following commands to verify the installation:

node -v

npm -v

You should see version numbers for both Node.js and npm.

Step 2: Install Newman
With Node.js and npm installed, you can now install Newman:

Open Terminal/Command Prompt:

On Windows, you can use Command Prompt or PowerShell.

On macOS/Linux, use the Terminal.

Install Newman Globally:

Run the following command to install Newman globally on your system:

npm install -g newman

The -g flag installs Newman globally, making it accessible from anywhere on your system.
Verify Newman Installation:

After installation, verify that Newman was installed correctly by running:

Newman -v
You should see the version number of Newman.

Step 3: Run a Postman Collection with Newman

Once Newman is installed, you can run Postman collections using the following command:

Run a Collection:

Navigate to the directory where your Postman collection is located, or provide the path to the collection.
Run the collection with Newman:

newman run your_collection.json

Replace your_collection.json with the path to your Postman collection file.
Example Command:

newman run my_postman_collection.json

If your collection requires an environment file, you can include it with the -e flag:

newman run Kids-Ecommerce-Api_collection.json -e TestGlobal environment.json

Step 4: Explore Additional Newman Features (Optional)

Generate HTML Report:

newman run Kids-Ecommerce-Api_collection.json -r HTML

Run a Collection from a URL:

newman run https://www.example.com/your_collection.json

These steps will set up Newman and allow you to run your Postman collections directly from the command line.

# Screenshots:

1. Kids-Ecommerce-API Run Collections:
   
![Screenshot 2025-02-24 083848](https://github.com/user-attachments/assets/9cf45c9e-8c77-4aca-81a3-f8426b7e031d)


2. Newman-Run-Report:
![Screenshot 2025-02-24 084550](https://github.com/user-attachments/assets/b20de19f-703f-40d5-9b0e-0ab5d14a33ed)


3. Newman-Dashboard-Html:


![Screenshot 2025-02-24 084241](https://github.com/user-attachments/assets/f5b5dc76-d167-4616-bd30-21962456acc3)










