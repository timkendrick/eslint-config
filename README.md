# @timkendrick/eslint-config
[![npm version](https://img.shields.io/npm/v/@timkendrick/eslint-config.svg)](https://www.npmjs.com/package/@timkendrick/eslint-config)
![Stability](https://img.shields.io/badge/stability-stable-brightgreen.svg)

> ESLint configuration for JavaScript projects

## Installation

```bash
npm install @timkendrick/eslint-config --save-dev
```

## Overview

A collection of opinionated rules based on the [Airbnb ESLint config](https://www.npmjs.com/package/eslint-config-airbnb) to ensure consistent lint settings across projects.

## Usage

### Standard projects

Add the following to your project's `.eslintrc.json`:

```json
{
  "extends": "@timkendrick/eslint-config"
}
```

### React projects

Add the following to your project's `.eslintrc.json`:

```json
{
  "extends": "@timkendrick/eslint-config/react"
}
```

### ES5 projects

Add the following to your project's `.eslintrc.json`:

```json
{
  "extends": "@timkendrick/eslint-config/legacy"
}
```

## Rules

Custom rule settings are specified in [`lib/rules/eslintrc.json`](./lib/rules/eslintrc.json)
