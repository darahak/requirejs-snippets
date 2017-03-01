# RequireJS snippets for Atom

Adding shortcuts for defining and importing modules with [RequireJS](http://requirejs.org/).

## Install

```
apm install requirejs-snippets
```

## Snippets

### Define a module

```js
define(['<deps>'], function (<deps>) {
  var exports = {
  
  };

  return exports;
});
```

### Define a module with a name

```js
define('<name>', ['<deps>'], function (<deps>) {
  var exports = {
  
  };

  return exports;
});
```

### Import a module

```js
require('<deps>', function (<deps>) {

});
```
