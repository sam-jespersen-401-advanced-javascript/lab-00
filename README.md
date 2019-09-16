# LAB 00 

## Proof of life server

### Author: Sam Jespersen

### Links and Resources
* [submission PR](https://github.com/sam-jespersen-401-advanced-javascript/lab-00/pull/1)
* [travis](https://travis-ci.com/sam-jespersen-401-advanced-javascript/lab-00)
* [front-end](http://sam-jespersen-lab-00.herokuapp.com/)

#### Documentation
* [jsdoc](http://sam-jespersen-lab-00.herokuapp.com/docs) (Server assignments)
### Modules
#### `pos.js`
##### Exported Values and Methods

###### `isAlive(dead) -> boolean`
Return true/false to indicate how the server works

### Setup
#### `.env` requirements
* `PORT` - Port Number


#### Running the app

* `npm start`
    * runs `index.js`
* `npm run lint`
    *   runs `eslint`
* `npm test`
    * runs `jest`
* `npm run test-watch`
    *   runs `jest` with the flags `--watchAll --verbose --coverage`
* `npm run jsdoc`
    * runs `jsdoc` to create doc files at `/docs/config/`

  
#### Tests
* Unit tests: `npm test`
* Lint tests: `npm run lint`
