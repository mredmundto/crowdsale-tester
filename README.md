# SelfKey Crowdsale Test UI

The Test UI for the SelfKey Crowdsale

* `develop` [![Build Status](https://www.travis-ci.org/SelfKeyFoundation/crowdsale-tester.svg?branch=develop)](https://www.travis-ci.org/SelfKeyFoundation/crowdsale-tester)
* `master` [![Build Status](https://www.travis-ci.org/SelfKeyFoundation/crowdsale-tester.svg?branch=master)](https://www.travis-ci.org/SelfKeyFoundation/crowdsale-tester)

## Development

The website is a standard React/Redux single page app built with [`create-react-app`](https://github.com/facebookincubator/create-react-app)

It uses the following:

* Styling and basic UI components from React Bootstrap
* Routing using React Router version 4
* Code is linted using `eslint` and prettified using `prettier`
* Tests are run using `jest`

### Prerequisites

* [NodeJS](https://nodejs.org) — `brew install nvm` then `nvm use 9.3.0` (or later)
* [`create-react-app`](https://github.com/facebookincubator/create-react-app) — `npm install -g create-react-app`

### Start it

Run

    npm install

Now run `npm start` to start the development web server on port `3000`

### Test it

* `npm test` — runs the unit tests (quick)

### Lint it

    npm run lint

## Contributing

Contributions are welcomed.  Please see the attached [CONTRIBUTING notes](CONTRIBUTING.md).
