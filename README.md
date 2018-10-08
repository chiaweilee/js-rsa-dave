# RSA Js-rsa-dave
- A fork of RSA
- A suite of routines for performing RSA public-key computations in JavaScript
- by Dave Shapiro

<a href="https://npmcharts.com/compare/js-rsa-dave?minimal=true"><img src="https://img.shields.io/npm/dm/js-rsa-dave.svg" alt="Downloads"></a>
<a href="https://www.npmjs.com/package/js-rsa-dave"><img src="https://img.shields.io/npm/v/js-rsa-dave.svg" alt="Version"></a>
<a href="https://www.npmjs.com/package/js-rsa-dave"><img src="https://img.shields.io/npm/l/js-rsa-dave.svg" alt="License"></a>

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

```javascript
RSA.encryptedString(RSA.getKeyPair(rsaTokenPublicExponent, '', rsaTokenPublicModulus), userInputPassword)
// return encrypted password
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
