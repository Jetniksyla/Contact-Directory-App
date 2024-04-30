# Contact Directory App

This is a simple contact directory application that allows users to add and remove contact cards. The application is built with webpack for bundling, utilizes service workers for caching static assets, and uses IndexedDB for storing contact information locally. The application also includes PWA functionality for installation.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Deployment](#deployment)
- [Built With](#built-with)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Installation

1. **Clone the repository:**

```bash
git clone https://github.com/your-repo/contact-directory-app.git
```

2. **Navigate to the project directory:**

```bash
cd contact-directory-app
```

3. **Install dependencies for the client:**

```bash
npm install
```

4. **Install dependencies for the server:**

```bash
cd server
npm install
```

## Usage

## **To start the application, run the following command from the root directory:**

1. **This will start both the client and server.**

```bash
npm start
```

2. **To start just the server, run:**

```bash
npm run server
```

3. **To start just the client, run:**

```bash
npm run client
```

## Deployment

The application is deployed using Heroku. To deploy the application, ensure you have the Heroku CLI installed and are logged in. Then, follow these steps:

1. **Create a new Heroku app:**

```bash
heroku create
```

2. **Add the Heroku Postgres add-on:**

```bash
heroku addons:create heroku-postgresql:hobby-dev
```

3. **Push the code to Heroku:**

```bash
git push heroku master
```

4. **Open the app in your browser:**

```bash
heroku open
```

## Built With

- [Express.js](https://expressjs.com/) - Web framework for Node.js
- [MongoDB](https://www.mongodb.com/) - NoSQL database
- [Mongoose](https://mongoosejs.com/) - MongoDB object modeling tool
- [Webpack](https://webpack.js.org/) - Module bundler
- [IndexedDB](https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API) - Browser-based database
- [Service Workers](https://developer.mozilla.org/en-US/docs/Web/API/Service_Worker_API) - For caching static assets

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.

## Contact

For inquiries or collaboration opportunities, please feel free to reach out to **Jetnik Syla:**

- **Email:** [sjetnik@gmail.com](mailto:sjetnik@gmail.com)
- **GitHub Profile:** [Jetnik Syla](https://github.com/JetnikSyla)
