# Wiki-APi

The Wiki API is designed to manage a collection of articles in a simple and efficient manner. It provides a set of endpoints to perform various operations, including retrieving all articles, adding new articles, updating existing ones, and deleting articles. The application uses technologies like Express, EJS, and MongoDB to facilitate seamless interaction with the database. Whether you're a developer looking to integrate with the API or a user seeking to manage articles, the wikiDB API offers a straightforward solution for handling these tasks.

## Table of Contents

- [Introduction](#introduction)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)
- [Acknowledgements](#acknowledgements)

## Introduction

This documentation is your guide to the Article-Api project. It use Express, EJS, and MongoDB to handle a collection of articles. Whether you're fetching information, adding new articles, or making updates, this API has got you covered. Take a look at the documentation to understand how to use the different endpoints.

## Technologies Used

- [Express](https://expressjs.com/)
- [EJS](https://ejs.co/)
- [Mongoose](https://mongoosejs.com/)
- [Body-parser](https://www.npmjs.com/package/body-parser)
- [MongoDB](https://www.mongodb.com/)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Olusegun-Light/Wiki-Api.git
   cd Wiki-API
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the server:

   ```bash
   npm run dev
   ```

## Usage

Once the server is up and running, you can use API endpoints to perform various operations. Refer to the [API Endpoints](#api-endpoints) section for details on available endpoints and their functionalities.

## API Endpoints

### `GET /articles`

Retrieves all articles from the database.

### `POST /articles`

Adds a new article to the database.

### `DELETE /articles`

Deletes all articles from the database.

### `GET /articles/:articleTitle`

Retrieves a specific article by title.

### `PUT /articles/:articleTitle`

Updates a specific article by title (full update).

### `PATCH /articles/:articleTitle`

Partially updates a specific article by title.

### `DELETE /articles/:articleTitle`

Deletes a specific article by title.

## Contributing

Contributions are welcome! If you find any issues or have improvements to suggest, feel free to create a pull request.

1. Fork the repository
2. Create your feature branch: `git checkout -b feature/new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature/new-feature`
5. Open a pull request

## Acknowledgements

- [Express.js Documentation](https://expressjs.com/)
- [EJS Documentation](https://ejs.co/)
- [Mongoose Documentation](https://mongoosejs.com/)
- [MongoDB Documentation](https://docs.mongodb.com/)

---
