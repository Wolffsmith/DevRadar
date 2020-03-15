# DevRadar

DevRadar is a complete app to register and search Devs near you.

This is the backend installation.

## Installation

##### Use the package manager of your preference. I've used yarn, so the examples will be with yarn.

### Database Setup

To use this backend, you will need a MongoDB account. I've created one on MongoDB Atlas.

Follow this example to create an account and a database: [MongoDB Atlas](https://docs.atlas.mongodb.com/getting-started/)

After creating your account a cluster and a collection you will find the connection string:

Something like this: "mongodb+srv://username:<password>@cluster0-qtyvb.mongodb.net/test"

Open the project and go to the file:

#### index.js

Change the line that says:

#### "INSERT YOUR URL FOR A MONGODB DATABASE"

And change it with your connection string.

### Dependencies

To install the dependencies just open the backend folder within a command line and type:

```bash
yarn install
```

## Usage

Again on your command line type:

```bash
yarn start
```

After that, your server will be running on http://localhost:3333/

## License

[MIT](https://choosealicense.com/licenses/mit/)
