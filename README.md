# # How to Run a Node Application

In this guide, we will walk you through the steps to run a Node.js application. We'll cover the installation of Node.js, managing dependencies with npm, and running the application locally. We'll also provide instructions on setting up a MongoDB database and viewing data using MongoDB Atlas.

## Prerequisites
Before you begin, make sure you have the following prerequisites installed on your system:

1. Node.js: Visit the official Node.js website (https://nodejs.org) and download the appropriate version for your operating system. Follow the installation instructions to complete the setup.

2. MongoDB: If you don't have MongoDB installed, we'll provide instructions on how to install it in the "Installing MongoDB" section.

## Installing Dependencies
To install the dependencies for your Node.js application, follow these steps:

1. Open a terminal or command prompt.

2. Navigate to the root directory of your Node.js application.

3. Run the following command to install the dependencies listed in the `package.json` file:


This will fetch and install all the required dependencies into your local environment.

## Running the Node Application
Once you have installed the dependencies, you can run the Node.js application using the following steps:

1. Open a terminal or command prompt.

2. Navigate to the root directory of your Node.js application.

3. Run the following command to start the application:


Replace `app.js` with the filename of your application's entry point.

Your Node.js application should now be running locally and can be accessed by visiting `http://localhost:3000` (or the appropriate URL specified in your application).

## Installing MongoDB
If you haven't installed MongoDB on your system, follow these steps to set it up:

1. Visit the MongoDB download page (https://www.mongodb.com/try/download/community) and select the appropriate version for your operating system.

2. Follow the installation instructions for your operating system to complete the setup. Make sure to note the installation directory.

3. Once MongoDB is installed, open a terminal or command prompt.

4. Run the following command to start the MongoDB service:


MongoDB will now be running locally on the default port `27017`.

## Viewing Data using MongoDB Atlas
MongoDB Atlas is a cloud-based service that allows you to manage and view your MongoDB data. Follow these steps to use MongoDB Atlas:

1. Visit the MongoDB Atlas website (https://www.mongodb.com/cloud/atlas) and sign up for an account.

2. Create a new project and follow the prompts to set up your MongoDB cluster.

3. Once your cluster is created, click on the "Connect" button and select "Connect your application".

4. Follow the instructions to copy the connection string.

5. Open your terminal or command prompt.

6. Run the following command, replacing `<connection-string>` with the copied connection string:


This will connect your local MongoDB instance to the MongoDB Atlas cluster.

7. Once connected, you can use various MongoDB commands to view and manage your data. Refer to the MongoDB documentation (https://docs.mongodb.com/) for more information on working with MongoDB.

Congratulations! You have successfully learned how to run a Node.js application, install MongoDB, and view data using MongoDB Atlas. Feel free to explore further and enhance your application based on your specific requirements.


