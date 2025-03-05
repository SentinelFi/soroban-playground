# Soroban Playground

---

## Freighter Wallet:

Recommendation. Use Freighter wallet extension for testing:

https://www.freighter.app/

https://developers.stellar.org/docs/build/guides/freighter

Import accounts, enable trust lines, swap assets.

---

## Quick Start:

```
cd soroban-playground-dapp
npm install
npm run dev
```

---

## Dapp Scaffold:

```
npx create-next-app@latest soroban-playground-dapp

cd soroban-playground-dapp

// dev command in package.json: "dev": "next dev --turbopack --experimental-https"

npm install @stellar/freighter-api bignumber.js

npm install --save @stellar/stellar-sdk

npm run dev

// Save the SSL certificate

// Open https://localhost:3000/
```

https://developers.stellar.org/docs/build/guides/dapps/frontend-guide

https://github.com/stellar/js-stellar-sdk

https://docs.freighter.app/docs/guide/usingFreighterWebApp
