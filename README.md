# smiles-module

🧐 Smiles-module in JSON formate

😌 Test:
```js
const smiles = require('./imports.json');
console.log(smiles[0])
```

😜 Вывод всех смайлов:
```js
const smiles = require('./imports.json');
smiles.forEach(e=>console.log(e));
```

😌 Test, ES6:
```js
import smiles from './imports.json';
console.log(smiles[0])
```

😜 Вывод всех смайлов, ES6:
```js
import smiles from './imports.json';
smiles.forEach(e=>console.log(e))
```
