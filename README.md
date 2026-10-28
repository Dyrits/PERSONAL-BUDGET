# PERSONAL-BUDGET

A simple back-end API to manage a budget using the envelope budgeting method.

## About The Project

Users can create, read, update and delete envelopes, and transfer money between them. Built as the Personal Budget portfolio project of the Codecademy Back-End Engineer Career Path.

The app currently uses a JavaScript object to store the data: this is suitable for a demo, but not for a production app, which would use a database. The data is lost when the app restarts.

### API

- Retrieve envelopes: `GET /api/v1/envelopes`
- Find a single envelope: `GET /api/v1/envelopes/{id}`
- Create an envelope: `POST /api/v1/envelopes`
- Update an envelope: `PUT /api/v1/envelope/{id}`
- Delete an envelope: `DELETE /api/v1/envelope/{id}`
- Transfer money between envelopes: `POST /api/v1/envelope/{from}/transfer/{to}`

### Built With

- Node.js + Express
- Swagger (swagger-jsdoc, swagger-ui-express)

## Getting Started

### Prerequisites

- Node.js

### Installation

```sh
npm install
npm start
```

Once running, the API is available at `http://localhost:5000/`, with Swagger documentation and testing at `http://localhost:5000/api-swagger`.

## License

No license file is present in this repository.

## Contact

Dyrits - https://github.com/Dyrits
