
**Mta Server Info | SykoCoder**

**Site:** https://sykocoder.tk

**NPM:** https://npmjs.com/package/mta-server-info

**Bug Report:** SykoCoder#4105

## Example

```
const SykoCoder = require("mta-server-info");

SykoCoder.getInfo("Server ip").then((info) => {

console.log(info) // Get server all info
console.log(info.name) //Get server name
console.log(info.player) //Get server player amount
console.log(info.port) //Get server port
console.log(info.version) //Get server version
console.log(info.password) //Get server password
})
 ```

 ## Installation

```
npm i mta-server-info
```
