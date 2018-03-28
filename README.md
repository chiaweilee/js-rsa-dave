# RSA Js-rsa-dave 2018-03-28 fork ver. 0.0.2
- A fork of RSA
- A suite of routines for performing RSA public-key computations in JavaScript
- by Dave Shapiro

- Fork and modify by +v

## Doc
http://www.ohdave.com/rsa/

## Useage
> rsa.node.js (NEW, suggest)
```javascript
// in components
import RSA from '../../plugin/rsa'
RSA.encryptedString(...)
RSA.getKeyPair(...)
```

> rsa.window.js (OLD)
```javascript
// in entry
import myRSA from './rsa.window.js'
myRSA()
```
```javascript
// in components
window.RSAUtils.encryptedString(...)
window.RSAUtils.getKeyPair(...)
```
