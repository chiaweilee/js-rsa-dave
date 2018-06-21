# RSA Js-rsa-dave
- A fork of RSA
- A suite of routines for performing RSA public-key computations in JavaScript
- by Dave Shapiro

- 🔧 Fork and modify by +v

## Install
```cmd
npm install js-rsa-dave --save
```
## 👃 Dave's Doc
http://www.ohdave.com/rsa/

## Usage
> rsa.node.js (🆕 NEW, suggest)
```javascript
// in components
import RSA from 'js-rsa-dave'
RSA.encryptedString(...)
RSA.getKeyPair(...)
```

> rsa.window.js (OLD)
```javascript
// in entry
import myRSA from 'js-rsa-dave/rsa.window.js'
myRSA()
```
```javascript
// in components
window.RSAUtils.encryptedString(...)
window.RSAUtils.getKeyPair(...)
```
