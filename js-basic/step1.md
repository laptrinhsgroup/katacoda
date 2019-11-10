# SMM RESTful API — Starter Files

## Requirements

> Node.js v8.x with `async/await`
>
> This version of SMM RESTful API uses **hapi v18**. For hapi v18, use a [`1.x` release](https://github.com/duongvietminhtri/smm-api/issues)

The SMM RESTful API base Starter Kit uses hapi v18 and has full `async/await` support.

**Requirements**

- Node.js **v8.x** or later
- NPM/Yarn to install the project’s dependencies

## Setup and Run

To run your own SMM RESTful API base instance, clone this repository, install the dependencies, start a postgreSQL instance on your own machine.

```bash
# clone repository
git clone https://github.com/laptrinhsgroup/typescript-api-base.git
cd typescript-api-base

# install dependencies
npm install

# create database with pgAdmin4
name: smm

# Run migration-up
$ npm migrate:latest

# Run migration-down
$ npm migrate:rollback

# Create a named migration or seed file
$ npm migrate:make <name>
$ npm seed:make <make>

# Run seed files
$ npm seed:run

# Build application
$ npm run build

# Run normally
$ npm run start

# Run the application with nodemon for development
$ npm run dev

# that’s it :)
```

The starter kit doesn’t contain any logging. If you don’t see any errors while starting the `build/index.js`,
[visit localhost:3000](http://localhost:3000). Have fun!

## Test

```bash
# create database with pgAdmin4
name: smm-test

# Test
$ npm run test                           # Run all test
$ npm run test:integration               # Run only integration test

# Test consistent coding style (Lint)
$ yarn watch:lint                        # Search error and warning
```

## Thank You with a Hug!

It’s great to see you exploring this repository. Really! Dig through the code and hopefully you’ll take wins away ❤️
