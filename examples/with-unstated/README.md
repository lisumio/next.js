# Unstated example

This example shows how to integrate Unstated in Next.js. For more info about Unstated you can visit [here](https://github.com/jamiebuilds/unstated). The example is basically same as [redux example](https://github.com/zeit/next.js/tree/canary/examples/with-redux).

The "counter" shows you how to preserve state from server to client and share the state within different page, you can expect the same state for "counter" when switching between Index and About page, observe that "counter" behaves differently from the "clock" example.

## Deploy your own

Deploy the example using [ZEIT Now](https://zeit.co/now):

[![Deploy with ZEIT Now](https://zeit.co/button)](https://zeit.co/import/project?template=https://github.com/zeit/next.js/tree/canary/examples/with-unstated)

## How to use

### Using `create-next-app`

Execute [`create-next-app`](https://github.com/zeit/next.js/tree/canary/packages/create-next-app) with [npm](https://docs.npmjs.com/cli/init) or [Yarn](https://yarnpkg.com/lang/en/docs/cli/create/) to bootstrap the example:

```bash
npm init next-app --example with-unstated with-unstated-app
# or
yarn create next-app --example with-unstated with-unstated-app
```

### Download manually

Download the example:

```bash
curl https://codeload.github.com/zeit/next.js/tar.gz/canary | tar -xz --strip=2 next.js-canary/examples/with-unstated
cd with-unstated
```

Install it and run:

```bash
npm install
npm run dev
# or
yarn
yarn dev
```

Deploy it to the cloud with [ZEIT Now](https://zeit.co/import?filter=next.js&utm_source=github&utm_medium=readme&utm_campaign=next-example) ([Documentation](https://nextjs.org/docs/deployment)).
