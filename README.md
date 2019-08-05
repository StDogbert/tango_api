# Tango OpenAPI Specification
[![Build Status](https://travis-ci.com/StDogbert/tango_api.svg?branch=master)](https://travis-ci.com/StDogbert/tango_api)

## Links

- [Reference Documentation (ReDoc)](https://stdogbert.github.io/tango_api/)
- [SwaggerUI](https://stdogbert.github.io/tango_api/swagger-ui/)
- OpenAPI Raw Files: [JSON](https://stdogbert.github.io/tango_api/openapi.json) [YAML](https://stdogbert.github.io/tango_api/openapi.yaml)

**Warning:** All above links are updated only after Travis CI finishes deployment

## Working on specification
### Install

1. Install [Node JS](https://nodejs.org/)
2. Clone repo and run `npm install` in the repo root

### Usage

#### `npm start`
Starts the development server.

#### `npm run build`
Bundles the spec and prepares web_deploy folder with static assets.

#### `npm test`
Validates the spec.

#### `npm run gh-pages`
Deploys docs to GitHub Pages. You don't need to run it manually if you have Travis CI configured.
