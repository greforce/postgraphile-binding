# `postgraphile-binding`

This library is a fork of a simple [basic-binding](https://github.com/artetecha/basic-binding) implementation with added fragmentReplacements option, and intended for use with postgraphile.

## Overview

`postgraphile-binding` provides a convenience layer for building GraphQL servers on top of postgraphile GraphQL service. In short, it simplifies implementing your GraphQL resolvers by _delegating_ execution of queries (or mutations) to the API of the underlying postgraphile GraphQL service.

## Install

```sh
$ yarn add postgraphile-binding
# or:
$ npm install postgraphile-binding
```

## Future plans

The idea is to develop this package, making it useful for postgraphile users. For the moment you may refer to the examples in this repository.
