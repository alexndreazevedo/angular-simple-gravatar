# angular-angular [![Build Status](https://secure.travis-ci.org/daemon1981/angular-angular.png)](https://travis-ci.org/daemon1981/angular-angular)

## Description

A simple directive to display a gravatar image given an email
From [angular-app](https://github.com/angular-app/angular-app/blob/master/client/src/common/directives/gravatar.js)

## Installation

```
bower install angular-angular
```

## Use

### Include in your header

```
<script src="angular.min.js"></script>
<script src="angular-gravatar.js"></script>
```

### Include module in your angular module

```
angular.module('myModule', ['angular-angular']);
```

### Exemple of using it for a list of posts

```
<gravatar email="email" size="30" default-image="'monsterid'"></gravatar>
```

## Contributing to the project

### Development
#### Prepare your environment
* Install [Node.js](http://nodejs.org/) and NPM (should come with)
* Install global dev dependencies: `npm install -g grunt-cli`
* Install local dev dependencies: `npm install`

#### Build
* Build the project: `grunt`

#### TDD
* Run test: `grunt test-watch`
 
This will start Karma server and will continuously watch files in the project, executing tests upon every change.

### Projects using angular-angular

 - [Workbook](https://github.com/eleven-labs/Workbook)
