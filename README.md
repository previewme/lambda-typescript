# typescript-lambda

[![lambda](https://github.com/previewme/lambda-typescript/actions/workflows/lambda.yml/badge.svg)](https://github.com/previewme/lambda-typescript/actions/workflows/lambda.yml)

This is a template repository for creating typescript lambda projects.

After cloning this template, The following files need to be modified to suit your project.

### package.json

* name
* version
* description
* license

### sonar-project.properties

* sonar.projectKey
* sonar.links.homepage
* sonar.links.ci
* sonar.links.scm
* sonar.links.issue

## Build

To build the lambda function run the following.

```
npm install
npm build
```

## Test

To run the tests.

```
npm test
```

## Package

The following will package the lambda function into a zip bundle to allow manual deployment.

```
zip -q -r dist/lambda.zip node_modules dist
```
