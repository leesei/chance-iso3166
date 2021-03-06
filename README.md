# chance-iso3166

Chance.js mixin to generate ISO-3166 country codes

## Install

```sh
npm install -S chance chance-iso3166
```

## Usage

```js
// initialize chance instance
const chance = require('chance').Chance();

// add this module as mixin
chance.mixin({
  iso3166: require('chance-iso3166')
});

// profit
chance.iso3166();
/*
{
  name: 'Georgia',
  alpha2: 'GE',
  alpha3: 'GEO',
  numeric: '268'
}
*/
```

## Reference

[ISO 3166-1 - Wikiwand](http://www.wikiwand.com/en/ISO_3166-1)  
[ISO 3166-2 - Wikiwand](http://www.wikiwand.com/en/ISO_3166-2)  

[lukes/ISO-3166-Countries-with-Regional-Codes](https://github.com/lukes/ISO-3166-Countries-with-Regional-Codes) (`all.json` is pulled from here)  
[datasets/country-codes](https://github.com/datasets/country-codes)  
[mledoze/countries](https://github.com/mledoze/countries)  
