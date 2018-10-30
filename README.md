# TPL-Dapp

To run the dapp locally, first install the required dependencies:
```
$ yarn install
```

To run a development version of the frontend (https is required for ledger support and will show a security warning due to the self-signed cert):

```
$ HTTPS=true yarn start
```

To build the production frontend (compiles to `build` folder), set the `homepage` field in `package.json` followed by:

```
$ yarn run build
```
