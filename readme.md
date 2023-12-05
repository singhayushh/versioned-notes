# Versioned Notes

## About this Project

Versioned Notes is a robust note-taking application designed to address two key objectives in the field of documentation:

1. **Versioning System:**
   - Implements Myers' diff algorithm for efficient versioning.
   - Saves incremental changes with a version number and timestamp for easy identification and retrieval of previous versions.
   - Enables users to review and revert to older versions of their notes.

2. **Collaborative Editing with Suggestions:**
   - Allows users to select a section of the note and suggest changes.
   - Suggested changes are reflected as annotations, visible to the note owner.
   - Facilitates collaborative editing, with the note owner having the final say on accepting or rejecting suggestions.

## Technologies Used

- **NodeTS:** The project is built using TypeScript on the Node.js runtime for a scalable and maintainable codebase.

- **Express:** Utilizes the Express.js framework to streamline the development of the server-side application, ensuring robustness and efficiency.

- **Mongoose:** Implements Mongoose, an elegant MongoDB object modeling tool designed to work in an asynchronous environment. Mongoose simplifies interactions with the MongoDB database, providing a schema-based solution for data validation and structuring.

## Getting Started

To run this project locally, follow these steps:

1. **Clone the Repository:**
```bash
git clone https://github.com/singhayushh/versioned-notes.git
```
2. **Install Dependencies**
```bash
cd versioned-notes
npm install
```
3. **Configure Env**
Use the .env.example file to create a .env with necessary configs.

4. **Run the Application**
```bash
npm start
```
5. **Access the API**
Use the postman collection shared for testing out he APIs.

## Contributing Guidelines

Feel free to contribute by opening issues, suggesting features, or submitting pull requests. Follow the standard coding guidelines and documentation conventions.

## License
This project is licensed under the MIT License. See the LICENSE file for details.