# Postman-API-Testing

# Postman Collection: Contact List API
This repository contains a Postman collection for testing the Contact List API, which is a RESTful API for managing contacts.

# Getting Started
To get started with testing the Contact List API, follow these steps:

Import the Collection: Import the Contact_List.postman_collection.json file into your Postman application.
Environment Variables: Set up the necessary environment variables in Postman. You may need to set variables like token, firstname, and lastname.
Run Requests: Run the requests in the collection to test various endpoints of the Contact List API. Ensure that you have the correct environment selected.
Review Responses: Review the responses from the API requests to verify that they meet the expected criteria.

# Collection Structure
The Postman collection is organized into folders, each representing a different aspect of testing the Contact List API:

Basic End Point Test: This folder contains requests for basic endpoint testing, including login, fetching contact lists, adding contacts, updating contacts, retrieving individual contacts, and deleting contacts.
Negative Test: This folder contains requests for testing error scenarios, such as unauthorized access, handling not found errors, missing required fields, and invalid input data.
Tests and Assertions

Each request in the collection is accompanied by tests and assertions to ensure that the API behaves as expected. These tests cover various aspects such as status codes, response times, content types, and data integrity.

# Pre-request and Post-request Scripts
The collection includes pre-request and post-request scripts to set up necessary data before sending requests and to process responses after receiving them. These scripts handle tasks such as extracting tokens, setting environment variables, and performing assertions.

# Contributing
Contributions to this Postman collection are welcome! If you encounter any issues, have suggestions for improvements, or want to add new tests, feel free to open an issue or submit a pull request.

# License
This project is licensed under the MIT License. Feel free to use, modify, and distribute the code as needed.
