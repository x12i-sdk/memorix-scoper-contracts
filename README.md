# @x12i/memorix-scoper-contracts usage example

Zod schemas and types for Memorix Scoper.

This consuming application demonstrates **validate incoming json and report contract errors** using the published npm package, pinned to `3.1.0`.

## Run

Requires Node.js 24 or newer and npm. The example needs no service credentials.

```sh
npm install --ignore-scripts
npm start
```

## Example

[`src/index.mjs`](src/index.mjs) contains the complete example. Assertions check the demonstrated behavior and the program prints a small result.

## When to use the package

- Validate a Scoper request with the shared schemas.
- Share Scoper response types between its host and consumer.

## Links

- [npm package](https://www.npmjs.com/package/@x12i/memorix-scoper-contracts)
- [Implementation monorepo](https://github.com/x12i/scoper-monorepo)
- [Reviewed package source](https://github.com/x12i/scoper-monorepo/tree/1fbab09cdcf68c47f68594bd91b2145a31128f77/packages/contracts)

The current source snapshot has a different manifest version from the pinned npm dependency. This example is validated against the installed npm release.

The `package.json` in this repository is private to prevent accidental publication of the example application under an npm package name.
