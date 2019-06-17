# LAB - 19

## Message Queue - API Server

### Author: Jesse Van Volkinburg

### Links and Resources
* [submission PR](https://github.com/401-advanced-javascript-jv/19-api/pull/1)
* [travis](https://travis-ci.com/401-advanced-javascript-jv/19-api)
* [API Server](https://lab19-api.herokuapp.com/)

### Documentation Links
* [JSDocs](https://lab19-api.herokuapp.com/docs)
* [Swagger API Docs](https://lab19-api.herokuapp.com/api/v1/docs)

### Setup
#### `.env` (environment variable) requirements
- `PORT` - port to run backend server on
- `MONGODB_URI` - MongoDB URI
- `Q_SERVER` - URL (with port, if necessary) to the running Q Server - NO trailing slash!
  - Example: `Q_SERVER=localhost:3333` or `Q_SERVER=http://test-server.test.com`

#### Running the app
* `npm start`

#### Tests
* `npm test` to run tests

