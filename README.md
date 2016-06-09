[![Build Status](https://travis-ci.org/alenoir/username-generator.svg?branch=master)](https://travis-ci.org/alenoir/username-generator)

# username-generator

Generate a username randomly

##Installation

```javascript
npm install username-generator --save
```

### Example

```javascript

var UsernameGenerator = require('username-generator');

var username1 = UsernameGenerator.generateUsername();
var username2 = UsernameGenerator.generateUsername("-");

username1 // codgerrevolting
username2 // tautology-modest

```
