[![Travis Build Status](http://img.shields.io/travis/ayhankuru/omdb-api.svg?style=flat-square)](https://travis-ci.org/ayhankuru/omdb-api) [![Circle Build Status](https://img.shields.io/circleci/project/ayhankuru/omdb-api.svg?style=flat-square)](https://circleci.com/gh/ayhankuru/omdb-api) [![Appveyor Build Status](https://img.shields.io/appveyor/ci/ayhankuru/omdb-api.svg?style=flat-square)](https://ci.appveyor.com/project/ayhankuru/omdb-api) [![Build Status](https://img.shields.io/david/ayhankuru/omdb-api.svg?style=flat-square)](https://david-dm.org/ayhankuru/omdb-api) [![io.js supported](https://img.shields.io/badge/io.js-supported-green.svg?style=flat-square)](https://iojs.org)




## Install

```
npm install omdb-api
```

## Usage


```js
var omdb = require('omdb-api');
```

```js
omdb({s:"Fight Club",r:"json"}).then(function(data){
	console.log(data)
})
```

***[Parameters](http://www.omdbapi.com/)***
