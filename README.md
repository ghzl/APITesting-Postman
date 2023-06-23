# Postman Project: HTTP Method Testing

This Postman project is designed to facilitate testing and validation of various HTTP methods (GET, POST, PUT, DELETE) for your API. It provides a collection of requests that can be executed to verify the functionality and behavior of your endpoints.

## Getting Started

To use this Postman project, follow the steps below:

1. Install Postman: If you haven't already, download and install Postman from the official website (https://www.postman.com/downloads/).

2. Clone the Repository: Clone this GitHub repository to your local machine or download the project as a ZIP file.

3. Import the Project: Open Postman and import the project by clicking on "Import" in the toolbar. Select the project folder or the exported JSON file (.postman_collection.json) from the cloned repository.

4. Configure Environment (if applicable): If your API requires specific environment variables, create or import the necessary environment file (.postman_environment.json) to set up the environment variables.

5. Set up Variables (if applicable): If your requests require dynamic variables like access tokens, IDs, or URLs, make sure to configure the appropriate variables in the Postman environment or request body.

## Collection Structure

The Postman project is organized into different folders, each representing an HTTP method. Here's a brief overview of each folder:

- **GET**: Contains requests that use the GET method to retrieve data from [reqres.in](https://reqres.in/) API.
- **POST**: Contains requests that use the POST method to create new resources or submit data to [reqres.in](https://reqres.in/) API.
- **PUT**: Contains requests that use the PUT method to update existing resources in [reqres.in](https://reqres.in/) API.
- **DELETE**: Contains requests that use the DELETE method to remove resources from [reqres.in](https://reqres.in/) API.

Each folder contains a set of pre-configured requests that you can execute directly or modify to match your specific test cases.

## Executing Requests

To execute a request, simply select the desired request from the corresponding folder and click the "Send" button. Postman will send the request to [reqres.in](https://reqres.in/) API and display the response details, including status codes, headers, and body content.

Make sure to review the request configuration, including request URL, headers, parameters, and request body, to ensure it aligns with your testing requirements.

## Customization and Contribution

Feel free to customize this Postman project based on your specific API endpoints, requirements, or additional testing scenarios. You can add new requests, modify existing ones, or create separate folders for different features or modules of your API.

If you find any issues or have suggestions for improvement, please open an issue or submit a pull request on the GitHub repository.

## License

This Postman project is released under the [GPL-3.0 License](LICENSE). You are free to use, modify, and distribute this project as per the terms of the license.
