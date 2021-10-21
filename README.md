# example-webpack-plugin-semaphoreci

[![RelativeCI](https://badges.relative-ci.com/badges/lNDx9r1Tk28uvN1U1gSW?branch=master)](https://app.relative-ci.com/projects/lNDx9r1Tk28uvN1U1gSW)

> [@relative-ci/agent](https://github.com/relative-ci/agent) webpack plugin setup example for [semaphore](https://semaphoreci.com)


## Example app

Basic webpack setup:
- `Javascript`: babel with `@babel/preset-env` and `@babel/preset-react`
- `CSS`: `postcss`(`autoprefixer`, `cssnano`), `css-modules`, `mini-css-extract`
- assets:
  - `public`: `copy-webpack-plugin`
  - `src`: `file-loader`
  - `inline.svg`: - `svgr`
