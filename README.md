# RSA Js-rsa-dave

[![Greenkeeper badge](https://badges.greenkeeper.io/chiaweilee/js-rsa-dave.svg)](https://greenkeeper.io/)

___
A suite of routines for performing RSA public-key computations in JavaScript
modified from project of Dave Shapiro

<a href="https://npmcharts.com/compare/js-rsa-dave?minimal=true"><img src="https://img.shields.io/npm/dm/js-rsa-dave.svg" alt="Downloads"></a>
<a href="https://www.npmjs.com/package/js-rsa-dave"><img src="https://img.shields.io/npm/v/js-rsa-dave.svg" alt="Version"></a>
<a href="https://www.npmjs.com/package/js-rsa-dave"><img src="https://img.shields.io/npm/l/js-rsa-dave.svg" alt="License"></a>

## Install
```cmd
npm install js-rsa-dave
```
## 👃 Dave's Doc
http://www.ohdave.com/rsa/

## Usage

```javascript
// in components
import RSA from 'js-rsa-dave'
RSA.encryptedString()
RSA.getKeyPair()
```

```javascript
RSA.encryptedString(RSA.getKeyPair(rsaTokenPublicExponent, '', rsaTokenPublicModulus), userInputPassword)
// return encrypted password
```
