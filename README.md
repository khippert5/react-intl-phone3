# React-Intl-Phone3
Highly customizable phone input component with auto formatting. This is a version of the existing react-phone-input-2 with fixes for area code exclusion. Everything in here except for the fix is from https://github.com/bl00mber/react-phone-input-2. 

For usage and abilities please see: https://github.com/bl00mber/react-phone-input-2
If this connection is severed, please contact me to revert readme back to usage.

## Additional feature(s):
autoSelectCountry - Allows country guessing to be turned on/off. Default is true. Turning off will default to the defaultCountry.
This is best used when autoFill is triggered. This will ensure that country is not guessed and forces the user to change the flag drop down to select dialcode

```
autoSelectCountry={false}

```

Best use case for autoSelectCountry: 
```
autoSelectCountry={false}
autoFormat={false}
autoPlaceholder={false}
countryCodeEditable={false}
defaultCountry={[// passed default country 2 letter iso code]}
disableAreaCodes={true}
disableCountryCode={false}
disableSearchIcon={true}
```

## Contributing
Code style changes not allowed

## License
[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/khippert5/react-intl-phone3/blob/master/LICENSE)

Based on [react-phone-input-2](https://github.com/bl00mber/react-phone-input-2)
