# DWalk
[nodejs] Return directories in path

### Install
```
npm install kc-dwalk
```

### Use
```js
var dwalk = require('kc-dwalk');
var dirs = dwalk('my-dir');
console.log(dirs);

// If you don't need to list recursively:
var dirs = dwalk('my-dir', false);
console.log(dirs);
```
