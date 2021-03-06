# Express API Boilerplate

Includes API Server utilities:

* [morgan](https://www.npmjs.com/package/morgan)
  * HTTP request logger middleware for node.js
* [helmet](https://www.npmjs.com/package/helmet)
  * Helmet helps you secure your Express apps by setting various HTTP headers. It's not a silver bullet, but it can help!
* [dotenv](https://www.npmjs.com/package/dotenv)
  * Dotenv is a zero-dependency module that loads environment variables from a `.env` file into `process.env`
* [axios](https://axios-http.com/)
  * Promise based HTTP client for the browser and node.js
* [prisma](https://www.prisma.io/)
  * Build faster with an open source ORM
* [mysql2](https://www.npmjs.com/package/mysql2)
  * MySQL client for Node.js with focus on performance. Supports prepared statements, non-utf8 encodings, binary log protocol, compression, ssl much more

Development utilities:

* [nodemon](https://www.npmjs.com/package/nodemon)
  * nodemon is a tool that helps develop node.js based applications by automatically restarting the node application when file changes in the directory are detected.
* [mocha](https://www.npmjs.com/package/mocha)
  * ☕️ Simple, flexible, fun JavaScript test framework for Node.js & The Browser ☕️
* [supertest](https://www.npmjs.com/package/supertest)
  * HTTP assertions made easy via superagent.

## Setup

```
pnpm install
```

## Test

```
pnpm test
```

## Development

```
pnpm dev
```

## Information
Any middleware prefixed with `__` will be ignored from global middlewares.
Example `__jwt.js` will be ignored.
