# State Clicker

A small React exercise practicing component state: click the button to get a random number 1-10; get a "YOU WIN!" message when it lands on 7.

## Tech stack

- React 16 (Create React App)

## Running it

```bash
npm install
npm start
```

Then open `http://localhost:3000`.

**Note:** on a modern Node.js version, `npm start`/`npm run build`/`npm test` need `NODE_OPTIONS=--openssl-legacy-provider` because this project uses an older webpack version incompatible with OpenSSL 3, e.g.:

```bash
NODE_OPTIONS=--openssl-legacy-provider npm start
```
