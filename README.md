# findage

Get age from DOB.

[![npm (scoped)](https://img.shields.io/badge/findage-1.0.0-blue.svg)](https://www.npmjs.com/package/findage)

## Install

```
$ npm install findage --save
```

## Usage

```js
const getAge = require("findage");

getAge.fullAge("07/09/2000");		// 19 years 7 months 16 days
getAge.inMonths("07/09/2000");		// 235 months 16 days
getAge.inHours("07/09/2000");		// 172032 hours
getAge.inMinutes("07/09/2000");		// 10321920 minutes
getAge.inSeconds("07/09/2000");		// 619315200 seconds

```

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.