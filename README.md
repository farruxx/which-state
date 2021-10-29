# which-state

Get US state name by coordinates

Forked from [which-country](https://github.com/vkurchatkin/which-country)

Powered by [rbush](https://github.com/mourner/rbush) and modified
[Natural Earth 50m countries dataset](http://www.naturalearthdata.com/downloads/50m-cultural-vectors/50m-admin-0-countries-2/).

If you are interested in more general solution, try [which-polygon](https://github.com/mapbox/which-polygon).

# Usage

```
npm install which-state
```

and then:

```javascript
var wc = require('which-state');

// pass [lng, lat]
console.log(wc([-107, 40])); // Colorado
console.log(wc([40, -40])); // null, somewhere in Atlantic Ocean
```

# Development

Run tests:

```
npm test
```

Generate R-tree:

```
npm run generate
```


# License

MIT
