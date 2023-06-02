# ERC20Pods

[![Build Status](https://github.com/deta/erc20-pods/workflows/CI/badge.svg)](https://github.com/deta/erc20-pods/actions)
[![Coverage Status](https://codecov.io/gh/deta/erc20-pods/branch/master/graph/badge.svg?token=Z3D5O3XUYV)](https://codecov.io/gh/deta/erc20-pods)
[![NPM Package](https://img.shields.io/npm/v/@deta/erc20-pods.svg)](https://www.npmjs.org/package/@deta/erc20-pods)

ERC20 extension enabling external smart contract based Pods to track balances of those users who opted-in to these Pods.

Examples of ERC20 Pods:
- [FarmingPod](https://github.com/deta/farming)
- [DelegatingPod](https://github.com/deta/delegating)

Usage:
- Inherit your tokens or tokenized protocol shares from `ERC20Pods`

Contribution:
- Install dependencies: `yarn` 
- Run tests: `yarn test` or `run test:ci`
