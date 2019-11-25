# js-band-hw-task-4
Ciklum University: JS Band Internship. Homework task #4
Demo: http://marunyak.github.io/js-band-hw-task-4

## Description
It is POC of the tracking system that helps collect data about transport.
What type of information it collect:

**Ships/Argosy**:
 - id
 - Model
 - Serial number/Name
 - Produced year
 - Capacity (in kg)
 - Average speed (in nm)
 - Count of team

**Trucks**:
 - id
 - Model
 - License plate
 - Produced year
 - Capacity (in kg)
 - Average speed (in km)
 - Type of gas

**Cost of delivery**:
 - Transport Model
 - Cost (by 1 kg of cargo)
 - Cost (by 1 km of distance)

## Table of Contents
* [Installation](#installation)
* [Available console commands](#other-commands)
* [Usage](#usage)
* [Technologies](#technologies)
* [Scripts description](#scripts-description)
* [Status](#status)
* [License](#license)

## Installation
1. Clone the reprository:
```sh
$ git clone https://github.com/marunyak/js-band-hw-task-4.git
```
2. Use [npm](https://npmjs.org/) to install node_modules
```sh
$ npm init
```
3. Run project:
```sh
$ npm run dev
```

## Available console commands
For build project:
```sh
$ npm run build
```
For testing using [Jest](https://jestjs.io/) tool:
```sh
$ npm run test
```
For lint javascript:
```sh
$ npm run lint
```
For fix errors which [Eslint](https://eslint.org/) found:
```sh
$ npm run fix
```

## Usage
- Add new ship
- Add new truck
- Add cost of delivery information

## Technologies
 - [Babel](https://babeljs.io/) - toolchain that is mainly used to convert ECMAScript 2015+ code into a backwards compatible version of JavaScript in current and older browsers
 - [Webpack](https://webpack.js.org/) - tool for bundle scritps
 - [Jest](https://jestjs.io/) - tool for test scripts
 - [Eslint](https://eslint.org/) - tool for identifying and reporting on patterns found in ECMAScript/JavaScript code, with the goal of making code more consistent and avoiding bugs.
 - [Commitizen](https://github.com/commitizen/cz-cli) - tool for prompted to fill out any required commit fields at commit time

## Scripts description
* `./src/index.html` - main html file;
* `./src/css/main.css` - main css file with stylesheets;
* `./src/js/index.js` - main file where are event listeners that respond to button clicks also this file is responsible for rendering  catalog page;
* `./src/js/sum.js` - test file for use Jest;
* `./src/js/modules/Catalog/Catalog.js` - file where is the logic for rendering, adding to the catalog;
* `./src/js/modules/CostOfDelivery/CostOfDelivery.js` - file for work with cost of delivery;
* `./src/js/modules/Form/Form.js` - file for work with forms;
* `./src/js/modules/LocalStorage/LocalStorage.js` - file for work with LocalStorage for set and get JSON file with information;
* `./src/js/modules/Pattern/TransportFactory.js` - file for creating different transport class instances;
* `./src/js/modules/Transport/Transport.js` - file that describes the structure of all vehicles;
* `./src/js/modules/Transport/Ship.js` - file for working with an entity Ship;
* `./src/js/modules/Transport/Truck.js` - file for working with an entity Truck;
* `./test/sum.test.js` - file which test sum.js
* `./webpack/webpack.common.js` - file for common webpack configuration;
* `./webpack/webpack.dev.js` - file for development webpack configuration;
* `./webpack/webpack.prod.js` - file for production webpack configuration;
* `.eslintrc` - file for eslint configuration;
* `.gitignore` - file to ignore files that are registered inside;
* `babel.config.js` - file for babel configuration;
* `jest.config.js` - file for jest configuration;
* `package-lock.json` - automatically generated for any operations where npm modifies either the node_modules tree, or package.json;
* `package.json` - file is used to give information to npm that allows it to identify the project as well as handle the project's dependencies.

## Status
Project is: _in progress_

## License
[ISC]
