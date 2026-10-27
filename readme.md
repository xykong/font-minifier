# font-minifier

Typescript-based Font compressor/minifier (with Node.js support).

## Development

Use Node.js 22 or newer and Yarn 1.22.22.

```shell
yarn install --frozen-lockfile
yarn build
yarn test --runInBand
yarn audit
```

Build before testing: integration tests exercise both TypeScript source and the compiled CLI.
CI runs these checks on Node.js 22 and 24. Dependabot checks dependencies weekly.

## Customizing your CLI

Check out the documentation at https://github.com/infinitered/gluegun/tree/master/docs.

## Publishing to NPM

To package your CLI up for NPM, do this:

```shell
$ npm login
$ npm whoami
$ npm lint
$ npm test
(if typescript, run `npm run build` here)
$ npm publish
```

# License

Apache-2.0 - see LICENSE

