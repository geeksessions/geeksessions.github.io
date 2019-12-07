# Geek Sessions website

This repos is used to hold the geek sessions website

## Building and running on localhost

First install dependencies:

```sh
npm install
```

To create a production build:

```sh
npm run build
```

To create and run a development build:

```sh
npm run build-dev
```

Then on a new terminal window run:

```sh
./node_modules/serve/bin/serve.js public
```

Open a browser on `localhost:5000`
