# SwissBankPayment Changelog

## 1.0.0

  * Set new version for publishing fork on packagist.

## 0.6.0 (2018-03-25)

  * Enforce stricter validation of inputs.
  * Escape all inputs.
  * Added support for sanitization of user inputs.
  * Added support for 19 new currencies.
  * Set charge bearer of SEPA payments.

## 0.5.0 (2017-03-07)

  * Added support for transaction purposes.
  * Improved validation of postal account numbers.

## 0.4.1 (2016-08-31)

  * Write IID without leading zeroes (for legacy systems)

## 0.4.0 (2016-08-28)

  * Added support for general account identifiers.
  * Added support for intermediary transaction agents.
  * Allow transfers in Euro for payment types 2 and 3.
  * Deprecate `Mxgma\SwissBankPayment\BC` in favor of `Mxgma\SwissBankPayment\IID`.
  * Added support for ISR payments (type 1).
  * Deprecate setting the creditor agent BIC of SEPA payments.

## 0.3.0 (2016-01-01)

  * Added support for foreign and SEPA payments.
  * Added support for GBP, USD and JPY.
  * Renamed `Mxgma\SwissBankPayment\PostalAddress` to `Mxgma\SwissBankPayment\StructuredPostalAddress`.

## 0.2.0 (2015-03-09)

  * Added support for domestic BC numbers.
  * Improved documentation.

## 0.1.0 (2014-09-06)

  * Initial release.
