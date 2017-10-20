# lychee
Official lightweight javascript framework of Digital Asset Omnificence (DAO) protocol atop the Ethereum.

## Install, Build and Test
```
$ npm install
$ npm run compile
$ npm run start
```

## Simulation Demo
\#Contract \#Issue \#Token \#Coupon \#Hash \#Transfer \#Payment \#PrimaryMarket \#SecondaryMarket

### Primary Market
- smart contract compiled by solidity and test protocol step by step under JavaScript code control
- 'super-admin' can create dasset market for dasset asset issuance by issuer users
- 'super-admin', 'token-issuer' and 'coupon-issuer' (rather than 'user') can create/issue dasset asset
- then issuer users can send dasset asset to any user as primary market issuance

**Case: lottery contract**
- super user create a lottery contract, then send to market place, users can participate in the lottery withdraw

### Secondary Market
- users who keep dasset asset in vault can send the dasset asset to recipients in the friendlist
- 'coupon-merchant' can request payment of specified dasset asset from its clients in circle/friendlist
- users who received the request payment can accept or reject it according to relevant business activities


