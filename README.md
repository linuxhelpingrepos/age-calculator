# age-calculator
> Get age in different formats.

[![npm (scoped)](https://img.shields.io/badge/age-calculator-0.0.1-blue.svg)](https://www.npmjs.com/package/@asif92/age-calculator)

- [Installation](#install)
- [Usage](#usage)
- [License](#license)

## Install

```
$ npm install findage --save
```

## Usage


```js
const getAge = require("findage");

// Input Format (MM/DD/YYYY)

getAge.fullAge("01/01/2000");		// 19 years 7 months 16 days
getAge.inMonths("01/01/2000");		// 235 months 16 days
getAge.inHours("01/01/2000");		// 172032 hours
getAge.inMinutes("01/01/2000");		// 10321920 minutes
getAge.inSeconds("01/01/2000");		// 619315200 seconds

```

## License

The MIT License. Please see [License File](LICENSE) for more information.