# han-nextts-quickstart

> Get started on Next.js with TypeScript by just a single click

This is an example setup of Next.js building on top of [the official TypeScript example](https://github.com/zeit/next.js/tree/master/examples/with-typescript). It adds the following:
* Basic Prettier setup
* ESLint config with [eslint-config-kentcdodds](https://github.com/kentcdodds/eslint-config-kentcdodds) and a few rules that I often use.
* TypeScript typechecking as part of `test` script (ready to plug into any CI)
* Update regularly

## Deploy

Deploy the example using [Netlify](https://netlify.com)
[![Netlify Status](https://api.netlify.com/api/v1/badges/f330cc35-8687-4711-960c-55daf4b36b24/deploy-status)](https://app.netlify.com/sites/han-nextts-quickstart/deploys)

## How to Use

Execute [create-next-app](https://github.com/vercel/next.js/tree/canary/packages/create-next-app) with [npm](https://docs.npmjs.com/cli/init) or [Yarn](https://yarnpkg.com/lang/en/docs/cli/create/) to bootstrap the example:

```
npx create-next-app --example https://github.com/hanihusam/han-nextts-quickstart han-nextts-quickstart-app
# or
yarn create next-app --example https://github.com/hanihusam/han-nextts-quickstart han-nextts-quickstart-app

```
