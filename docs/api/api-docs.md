---
sidebar_position: 1
---

# API Docs

You can call our API from anywhere to check if a wallet has been reported as hacked

```js
`https://burnmywallet.com/api/isBurned?address=${address}&chain=${chain}`;
```

For example https://burnmywallet.com/api/isBurned?address=0x3D9d22E1821Be3b1Ce2A8ACB6FE47fFEF04243c3&chain=rinkeby

returns

```json
{
  "hacked": true
}
```
