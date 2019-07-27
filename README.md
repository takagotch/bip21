### bip21
---
https://github.com/bitcoinjs/bip21


```js
var bip21 = require('bip21')
var decoded = bip21.decode('bitcoin:xxx?amount=20.3&label=Foobar')
console.log(decoded)

console.log(bip21.encode('xxx'))
console.log(bip21.encode('xxx', {
  amount: 20.3,
  label: 'Foobar'
}))


```

```
```

```
```


