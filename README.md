# Project Name

> Project description

## Related Projects

  - https://github.com/llaminati/Banner-Gallery
  - https://github.com/llaminati/Menu
  - https://github.com/llaminati/Reservations
  - https://github.com/llaminati/Reviews

## Table of Contents

1. [Usage](#Usage)
1. [Requirements](#requirements)
1. [Development](#development)

## Usage

> Server-DEV: npm run server
> Server-PRO: npm start

## Requirements

An `nvmrc` file is included if using [nvm](https://github.com/creationix/nvm).

- Node 6.13.0
- etc

## Development

### Installing Dependencies

From within the root directory:

```sh
npm install -g webpack
npm install
```
## CRUD API Routes

'GET': /api/listings/:restaurantID/reviews
  - finds all reviews for a particular restaurant

'POST': /api/listings/:restaurantID/reviews
  - posts a new review for a particular restaurant

'PUT': /api/listings/:restaurantID/reviews/:reviewID
  - updates a review for a particular restaurant

'DELETE': /api/:restaurantID/reviews/:reviewID
  - deletes a review for a particular restaurant
