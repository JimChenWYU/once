# Changelog

All notable changes to `once` will be documented in this file

## 2.1.1 - 2019-06-27

- do not throw an error when using `once` in `eval`

## 2.1.0 - 2019-06-19

- add enabling/disable the cache
- add `flush` method
- drop support for PHP 7.1 and below

## 2.0.2 - 2018-12-27

- add ability to use `once` in static functions

## 2.0.1 - 2018-01-31

- improvements around serialization

## 2.0.0 - 2018-01-31

- ditch `__memoized` in favor of `Spatie\Once\Cache`

## 1.1.0 - 2017-08-24

- add `MemoizeAwareTrait`

## 1.0.1 - 2016-11-14

- fix cacheability of falsy return values

## 1.0.0 - 2016-11-07

- initial release
