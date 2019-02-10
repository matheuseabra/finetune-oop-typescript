# FineTune OOP Typescript 🚀

[![Build Status](https://travis-ci.org/wswebcreation/protractor-cucumber-typescript-boilerplate.svg?branch=master)](https://travis-ci.org/wswebcreation/protractor-cucumber-typescript-boilerplate)

Project built for the FineTune Selection, demonstrating how to structure OOP concepts with TypeScript, writing tests using Protactor as testing library along with CucumberJS and Gherkin language.

## Features

* working configuration out of the box for **CucumberJS 3.x**
* feature and step-files
* no need to compile TypeScript testfiles before running
* automatically making screenshots on failed steps (you can adjust the filename to whatever you want, it's just a simple setup)

## Quickstart

```javascript

# 1. Clone this repository
git clone https://github.com/matheuseabra/finetune-oop-typescript.git

# 2. Navigate to the project root directory
cd finetune-oop-typescript

3. Install project dependencies
npm install

# 4. Run tests
npm run e2e // Run all the available feature files
npm run e2e -- --feature= example // Run a specific tagged test(s) / feature file(s)
```

## CucumberJS compiles on-the-fly

With the provided setup in the [`protractor.shared.conf.js`](/e2e-tests/config/protractor.shared.conf.js) you don't need to compile the TypeScript files before you run them. It will be done automatically for you with the `compiler` in the `cucumberOpts`.

## Author

This project was developed by Matheus Seabra.

matheuseabra.me
