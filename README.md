# Tron Unit Conversion Utilities

It contains functions to convert between string representations and numeric
representations of numbers, including those out of the range of JavaScript.

For more information, see the [documentation](https://docs.tron.io/v5/api/utils/display-logic/).

## Importing

Most users will prefer to use the [umbrella package](https://www.npmjs.com/package/tron),
but for those with more specific needs, individual components can be imported.

```javascript
const {
  formatUnits,
  parseUnits,

  formatEther,
  parseEther,

  commify
} = require('@tronproject/units');
```

## License

MIT License
