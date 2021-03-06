# Changelog

## 2.2.1 (2020-09-01)

### Tax Rate Updates

* **Ireland**: 23% to 21% (1st September 2020 to 28th February 2021) [[@gierschv](https://github.com/gierschv)].

## 2.2.0 (2020-06-12)

### Non-Breaking Changes

* Return a detailed view of all sub-tax rates used when calling `getSalesTax()` and `getAmountWithSalesTax()` (this is useful eg. for Canada, which has multiple tax rates ie. state and country taxes) [[@maktouch](https://github.com/maktouch), [@valeriansaliou](https://github.com/valeriansaliou), [6e5b9be](https://github.com/valeriansaliou/node-sales-tax/commit/6e5b9be2df632ca6e4b97286a690529fffae3b98), [#27](https://github.com/valeriansaliou/node-sales-tax/pull/27)].

## 2.1.0 (2020-06-11)

### Non-Breaking Changes

* Add a way to schedule tax rate updates for a country or state in a future date [[@valeriansaliou](https://github.com/valeriansaliou), [accda53](https://github.com/valeriansaliou/node-sales-tax/commit/accda53ce1d89ac48f2a1c77d9a58b04d143cc36)].

### Tax Rate Updates

* **Germany**: 19% to 16% (1st July 2020 to 31st December 2020) [[@valeriansaliou](https://github.com/valeriansaliou)].
* **Kenya**: 16% to 14% (1st April 2020) [[@adrai](https://github.com/adrai)].
* **Saudi Arabia**: 5% to 15% (1st July 2020) [[@adrai](https://github.com/adrai)].

## 2.0.0 (2017-10-27)

### New Features

* More methods added [[@valeriansaliou](https://github.com/valeriansaliou)].

## 1.0.0 (2017-05-05)

### New Features

* Initial release [[@valeriansaliou](https://github.com/valeriansaliou)].
