# NAF CLI 
A Node API Generating project. It uses MongoDB, Fastify and Swagger.

## Prerequisites
- Nodejs
- MongoDB

## Build Setup

#### Install dependencies
`npm install`

#### Serve with hot reload at localhost:8080
`npm start`

## Scripts for generating
#### Initial a local generating scripts
`npm link`

#### Scripts
You can use the `naf` command to generate controllers:

```javascript
# entering the alias
naf controller

# The system will ask you enter your Controller name, then you can:

# Entering the alias
new-controller-name
/**
 * Your controller named `new-controller-name.controller.js` will be generated in src/controllers
 * Your route names named `new-controller-name.route.js` will be generated in src/routes
 * Your schema named `new-controller-name.schema.js` will be generated in src/schemas
 */

# Or entering relative path generation
admin/feature/new-controller-name
/**
 * Your controller will be generated in src/controllers/admin/feature
 * Your route will be generated in src/routes/admin/feature
 * Your schema will be generated in src/schemas/admin/feature
 */

```
You can find all possible blueprints in the table below:

Scaffold  | Usage
---       | ---
[Model]      | `naf model`
[Controller, Route, Schema]      | `naf controller`

`Note that, Your models always generated in src/models`
