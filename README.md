# Repro Attribution Reporting issue locally

[Issue #40](https://github.com/GoogleChromeLabs/privacy-sandbox-dev-support/issues/40)

## Set up 

- `git clone`

In the project folder (`./repro-attribution-reporting-issue`):
- `npm i`
- `brew install mkcert`
- `mkcert -install`
- `mkcert localhost`

## Run
- Run as localhost HTTPS: `node ./index-https.js`
- Run as localhost HTTP: `node ./index.js`
