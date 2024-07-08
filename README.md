# Uniswap V2 - modernized

This repository is a fork of Uniswap V2 which is compilable versions of `solc` more recent than 0.5.16.

In updating the code, there may be some warts introduced - for example cases where Uniswap relied on overflow as a feature
which now cause reversions during execution.

If you run into something like this, please create an [issue](https://github.com/zomglings/uniswap-v2-core/issues/new)
or a pull request, and I will try to address it quickly.

[Uniswap V2 docs](https://docs.uniswap.org/contracts/v2/overview)

- - -

## Original documentation

[![Actions Status](https://github.com/Uniswap/uniswap-v2-core/workflows/CI/badge.svg)](https://github.com/Uniswap/uniswap-v2-core/actions)
[![Version](https://img.shields.io/npm/v/@uniswap/v2-core)](https://www.npmjs.com/package/@uniswap/v2-core)

In-depth documentation on Uniswap V2 is available at [uniswap.org](https://uniswap.org/docs).

The built contract artifacts can be browsed via [unpkg.com](https://unpkg.com/browse/@uniswap/v2-core@latest/).

## Local Development

The following assumes the use of `node@>=10`.

### Install Dependencies

`yarn`

### Compile Contracts

`yarn compile`

### Run Tests

`yarn test`
