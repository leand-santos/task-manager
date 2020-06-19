# Task Manager

A complete task manager API.

## Getting Started

### Prerequisites

```
nodejs
npm
```

### Installing

Open a Terminal in backend and frontend folders and run:

Using `npm`

```
npm install
```

### Running localy

Create a config folder with the dev.env file containing the following variables:

```
PORT=<port number>
SENDGRID_API_KEY=<sendgrid key>
JWT_SECRET=<secret>
MONGODB_URL=<url>
```

Finally run:

```
npm run dev
```

### Running tests

Create in the config folder a test.env file containing the following variables:

```
PORT=<port number>
SENDGRID_API_KEY=<sendgrid key>
JWT_SECRET=<secret>
MONGODB_URL=<test url>
```

Finally run:

```
npm run test
```

## Built With

* [nodeJS](https://nodejs.org/en/docs/) - The web framework used
* [npm](https://www.npmjs.com/) - Back-End package manager
* [express](https://expressjs.com/) - Routes framework
* [@sendgrid/mail](https://www.npmjs.com/package/@sendgrid/mail) - Service for interaction with the mail endpoint 
* [jsonwebtoken](https://www.npmjs.com/package/jsonwebtoken) - Token generator
* [mongodb](https://www.npmjs.com/package/mongodb) - API for mongodb
* [mongoose](https://mongoosejs.com/) - Mongodb schema
* [multer](https://www.npmjs.com/package/multer) - File uploader
* [sharp](https://www.npmjs.com/package/sharp) - Image uploader
* [validator](https://www.npmjs.com/package/validator) - Library for string validators
