# CodeSnipper - Secure Coding Notes Storage App

![CodeSnipper Logo](https://example.com/codesnipper_logo.png)

CodeSnipper is an application designed to help developers securely store coding notes. It provides authentication and authorization functionalities using JSON Web Tokens (JWT) to ensure that only authorized users can access and manage their saved code snippets. With user-friendly features like code block creation with a copy button, React Markdown support, and a convenient search bar, CodeSnipper aims to enhance the coding experience and streamline the organization of code snippets.

## Features

### Authentication and Authorization

CodeSnipper implements JWT-based authentication and authorization to ensure that only registered and logged-in users can access the app's functionalities. This adds an extra layer of security to protect sensitive coding notes.

### Code Block Creation with Copy Button

When adding a code snippet, CodeSnipper allows users to create a code block that includes a convenient "Copy to Clipboard" button. This feature enables users to quickly copy code snippets to their clipboard and use them in their projects without the hassle of manual copying.

### React Markdown Support

CodeSnipper supports rendering code snippets using React Markdown. Users can format their notes with Markdown syntax to create clear and readable code blocks, add comments, and organize their code snippets efficiently.

### Search Bar

To facilitate easy access to saved coding notes, CodeSnipper offers a search bar. Users can quickly search for specific code snippets by keywords, tags, or any relevant text, making it effortless to find the information they need.

## Installation

To run CodeSnipper locally, follow these steps:

1. Clone the repository from GitHub:
   ```
   git clone https://github.com/yourusername/codesnipper.git
   cd codesnipper
   ```

2. Install the required dependencies:
   ```
   npm install
   ```

3. Set up environment variables:
   - Create a `.env` file in the root directory.
   - Add the following environment variables with your values:
     ```
     DATABASE_URL=your_database_connection_string
     JWT_SECRET=your_jwt_secret_key
     ```

4. Start the development server:
   ```
   npm start
   ```

5. Access CodeSnipper in your browser at `http://localhost:3000`.

## Technologies Used

- Frontend:
  - React.js
  - Redux for state management
  - React Markdown for rendering code blocks
  - Axios for API communication

- Backend:
  - Node.js with Express.js
  - MongoDB for data storage

- Authentication:
  - JSON Web Tokens (JWT)

## Contributing

Contributions to CodeSnipper are welcome! If you find any bugs, have feature suggestions, or want to improve the app, please feel free to open an issue or submit a pull request. We highly appreciate your input and contributions.

## License

CodeSnipper is licensed under the [MIT License](https://opensource.org/licenses/MIT).

## Contact

If you have any questions, feedback, or need support, you can reach the CodeSnipper team at support@codesnipper.com or join our community on Discord at [https://discord.gg/codesnipper](https://discord.gg/codesnipper).

Happy coding with CodeSnipper! 🚀
