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
    return {};
});
```

### Define a module with a name

```js
define('<name>', ['<deps>'], function (<deps>) {
    return {};
});
```

### Import a module

```js
require('<deps>', function (<deps>) {

});
```
