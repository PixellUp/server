```sh
npm i @ragemp-tools/server@beta
```

```javascript
const { server } = require('@ragemp-tools/server')

server('1.1.1.1:11111').then(console.log) 
// output:
// {
//   name: 'Test Server',
//   gamemode: 'testplay',
//   url: 'mur.cx',
//   lang: 'ru',
//   players: 1109,
//   peak: 1109,
//   maxplayers: 1109
// }
```
#### server(ip)

- `ip` <[String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)>

- `returns` <[Promise](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)<[Object](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object)>> { name: <[String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)>, gamemode: <[String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)>, url: <[String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)>, lang: <[String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)>, players: <[Number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)>, peak: <[Number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)>, maxplayers: <[Number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)>}
