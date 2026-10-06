# Taquito Sandbox

Tezos application prototype using Taquito, jQuery, and Parcel. Based on
[ecadlabs/taquito-boilerplate](https://github.com/ecadlabs/taquito-boilerplate).

## Local Development

```bash
npm install
npm run watch
```

Open `http://localhost:1234`.

## Commands

```bash
npm run build   # Build with Parcel
npm run clean   # Remove dist/
```

`npm test` is a placeholder and exits with an error.

## Files

- `src/app.ts`: application logic.
- `src/main.ts`: entry point.
- `src/index.html`: page markup.
- `src/app.css`: styles.
- `tsconfig.json`: TypeScript settings.

The documented test network is Ghostnet. Wallet integration is not implemented.
See `LICENSE` for license terms.
