# OData V4 Tutorial

This project is a UI5 demo application designed to demonstrate the usage of OData V4. It includes a mock server, sample data, and various UI5 components to help you understand how to work with OData V4 in a UI5 application.

## Project Structure

-   `webapp/`: Contains the main application files.
    -   `localService/`: Contains the mock server and mock data.
        -   `mockdata/people.json`: Sample data for the application.
        -   `mockserver.js`: Mock server initialization.
    -   `model/`: Contains the model definitions.
        -   `models.js`: Device model creation.
    -   `initMockServer.js`: Initializes the mock server.
    -   `Component.js`: Main component initialization.
-   `ui5.yaml`: UI5 configuration file.
-   `package.json`: Project metadata and dependencies.

## Getting Started

### Prerequisites

-   Node.js (version 14 or higher)
-   UI5 CLI

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/your-repo/odata-v4-tutorial.git
    ```
2. Navigate to the project directory:
    ```sh
    cd odata-v4-tutorial
    ```
3. Install the dependencies:
    ```sh
    npm install
    ```

### Running the Application

Start the application using the UI5 CLI:

```sh
npm start
```

This will start a local server and open the application in your default web browser.

## Usage

The application demonstrates how to use OData V4 with UI5. It includes sample data and a mock server to simulate OData V4 services. You can explore the code to understand how different components interact with the OData V4 service.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.
