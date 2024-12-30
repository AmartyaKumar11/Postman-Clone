# Postman Clone

A **Postman Clone** is a web-based tool designed for sending and testing HTTP requests. It replicates essential features of Postman, providing a simplified interface for interacting with APIs and viewing their responses. This project is built using modern web development tools and libraries.

## Features

- Select HTTP methods (GET, POST, PUT, DELETE, etc.).
- Enter and edit URLs.
- Add and manage query parameters and headers.
- Compose and send JSON request bodies.
- Display response details such as:
  - Status code
  - Response time
  - Response size
  - Response headers
  - Response body (formatted JSON).
- Syntax highlighting and formatting for JSON using CodeMirror.

## Built With

- **HTML/CSS/JavaScript**: For the user interface and core functionality.
- **Snowpack**: For development and module bundling.
- **Axios**: For making HTTP requests.
- **CodeMirror**: For code editing with syntax highlighting.
- **Bootstrap**: For responsive and modern UI design.
- **Pretty-Bytes**: For formatting file sizes in the response details.

## Getting Started

### Prerequisites

- Node.js (latest LTS version recommended)
- npm or yarn (for managing dependencies)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/AmartyaKumar11/postman-clone.git
   ```
2. Navigate to the project directory:
   ```bash
   cd postman-clone
   ```
3. Install dependencies:
   ```bash
   npm install
   ```

4. Start the development server:
   ```bash
   npm run start
   ```

5. Open your browser and navigate to:
   ```
   http://localhost:8080
   ```

## Usage

1. Select an HTTP method (e.g., GET, POST).
2. Enter the API URL in the input field.
3. Add query parameters and headers as needed.
4. Write the request body in the JSON editor (if applicable).
5. Click the **Send** button to execute the request.
6. View the response details in the response section.

## Project Structure

```
postman-clone/
├── public/              # Static files
├── src/
│   ├── index.html       # Main HTML file
│   ├── styles/          # CSS styles
│   ├── scripts/         # JavaScript code
│   └── components/      # Modular components (headers, query parameters, etc.)
├── package.json         # Project configuration
├── snowpack.config.js   # Snowpack configuration
└── README.md            # Project documentation
```

## Future Improvements

- Add authentication options (e.g., API keys, OAuth).
- Implement request history and save functionality.
- Support for raw, form-data, and binary request bodies.
- Provide dark mode for better usability.

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m "Add feature-name"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Inspired by Postman.
- Built for learning and demonstration purposes.
