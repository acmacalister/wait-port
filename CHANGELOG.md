# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

## [1.0.4](https://github.com/dwmkerr/wait-port/compare/v1.0.3...v1.0.4) (2022-10-18)


### Bug Fixes

* Handle systems without IPv6 properly ([#97](https://github.com/dwmkerr/wait-port/issues/97)) ([7cc0fac](https://github.com/dwmkerr/wait-port/commit/7cc0facab2c6735b6f03c1528a1114d1d9658eae))

## [1.0.3](https://github.com/dwmkerr/wait-port/compare/v1.0.2...v1.0.3) (2022-10-12)


### Bug Fixes

* fix publish ([#95](https://github.com/dwmkerr/wait-port/issues/95)) ([446798a](https://github.com/dwmkerr/wait-port/commit/446798a9cf789b38b1ea84ee6306f2f2e34fd3e8))

## [1.0.2](https://github.com/dwmkerr/wait-port/compare/v1.0.1...v1.0.2) (2022-10-12)


### Bug Fixes

* Handle EADDRNOTAVAIL if IPv6 not enabled ([#93](https://github.com/dwmkerr/wait-port/issues/93)) ([4b2d30b](https://github.com/dwmkerr/wait-port/commit/4b2d30beb4db3142475184c275ef56a14e0f7801))

## [1.0.1](https://github.com/dwmkerr/wait-port/compare/v1.0.0...v1.0.1) (2022-09-20)


### Bug Fixes

* correct return code on timeout ([#90](https://github.com/dwmkerr/wait-port/issues/90)) ([75988cc](https://github.com/dwmkerr/wait-port/commit/75988cc09cb6c0398df42afb9a94a124bae81255)), closes [#89](https://github.com/dwmkerr/wait-port/issues/89)

## [1.0.0](https://github.com/dwmkerr/wait-port/compare/v0.3.1...v1.0.0) (2022-09-08)


### ⚠ BREAKING CHANGES

* Returns now an object instead of an boolean. The object contains the property `open: boolean` and if `open` is `true` it will also contain `ipVersion` which will be `4` or `6` dependening on which IP version the open port was found on.

### Bug Fixes

* Check both IPv4 and IPv6 when dns-name supplied ([#84](https://github.com/dwmkerr/wait-port/issues/84)) ([3c3821c](https://github.com/dwmkerr/wait-port/commit/3c3821ca7e7079ca238ce28c0886b0fabaa49470))

## [0.3.1](https://github.com/dwmkerr/wait-port/compare/v0.3.0...v0.3.1) (2022-09-05)


### Miscellaneous Chores

* release 0.3.1 ([d333e8f](https://github.com/dwmkerr/wait-port/commit/d333e8fc99219042406bee2467d6abd32cd1c9ef))

## [0.3.0](https://github.com/dwmkerr/wait-port/compare/v0.2.14...v0.3.0) (2022-07-11)


### Features

* enable node 10 compatibility ([4ea012f](https://github.com/dwmkerr/wait-port/commit/4ea012f27956dda0bc123344878793b37a5e1eef))

## [0.2.14](https://github.com/dwmkerr/wait-port/compare/v0.2.13...v0.2.14) (2022-07-11)


### Miscellaneous Chores

* release 0.2.13 ([cf301a2](https://github.com/dwmkerr/wait-port/commit/cf301a2e92f54f303af7c9f0584e69ad4dbaf4b8))
* release 0.2.14 ([3755a37](https://github.com/dwmkerr/wait-port/commit/3755a37e1d6b6fca80de7ce63bd460a3af601df4))

## [0.2.13](https://github.com/dwmkerr/wait-port/compare/v0.2.12...v0.2.13) (2022-07-11)


### Miscellaneous Chores

* release 0.2.13 ([dfe917d](https://github.com/dwmkerr/wait-port/commit/dfe917d28bb1a8e2289091f584618a0ae3405910))

## [0.2.12](https://github.com/dwmkerr/wait-port/compare/v0.2.11...v0.2.12) (2022-07-11)


### Miscellaneous Chores

* release 0.2.12 ([6ae36dd](https://github.com/dwmkerr/wait-port/commit/6ae36dd8cb687dd3de514415115c43a2cc4f7392))

## [0.2.11](https://github.com/dwmkerr/wait-port/compare/v0.2.10...v0.2.11) (2022-07-11)


### Miscellaneous Chores

* release 0.2.11 ([acd047f](https://github.com/dwmkerr/wait-port/commit/acd047f5e5cf3514296daf7ffc85246eb3cd18f6))

## [0.2.10](https://github.com/dwmkerr/wait-port/compare/v0.2.9...v0.2.10) (2022-07-11)


### Bug Fixes

* **http:** send valid HTTP Request ([#70](https://github.com/dwmkerr/wait-port/issues/70)) ([27e83c9](https://github.com/dwmkerr/wait-port/commit/27e83c9e80c6ad0eb5a6395e836fe91ea1a5ba23))

### [0.2.9](https://github.com/dwmkerr/wait-port/compare/v0.2.8...v0.2.9) (2020-05-26)

### [0.2.8](https://github.com/dwmkerr/wait-port/compare/v0.2.7...v0.2.8) (2020-05-26)

### [0.2.7](https://github.com/dwmkerr/wait-port/compare/v0.2.6...v0.2.7) (2019-12-12)

### [0.2.6](https://github.com/dwmkerr/wait-port/compare/v0.2.5...v0.2.6) (2019-10-07)


### Features

* better error messages for invalid targets ([e4a2f31](https://github.com/dwmkerr/wait-port/commit/e4a2f31)), closes [#43](https://github.com/dwmkerr/wait-port/issues/43)

### [0.2.5](https://github.com/dwmkerr/wait-port/compare/v0.2.4...v0.2.5) (2019-10-07)

### [0.2.4](https://github.com/dwmkerr/wait-port/compare/v0.2.3...v0.2.4) (2019-10-03)


### Features

* add the 'wait-for-dns' flag ([#47](https://github.com/dwmkerr/wait-port/issues/47)) ([31418c2](https://github.com/dwmkerr/wait-port/commit/31418c2)), closes [#41](https://github.com/dwmkerr/wait-port/issues/41)

### [0.2.3](https://github.com/dwmkerr/wait-port/compare/v0.2.2...v0.2.3) (2019-10-03)


### Bug Fixes

* pin sinon to 5.0.8 ([1a8fe7d](https://github.com/dwmkerr/wait-port/commit/1a8fe7d))
* **package:** update commander to version 3.0.0 ([7265c1d](https://github.com/dwmkerr/wait-port/commit/7265c1d))
* **package:** update debug to version 4.1.0 ([fa3dd5f](https://github.com/dwmkerr/wait-port/commit/fa3dd5f)), closes [#26](https://github.com/dwmkerr/wait-port/issues/26)


### Features

* show a sensible error message if the address cannot be found ([#46](https://github.com/dwmkerr/wait-port/issues/46)) ([b980aa8](https://github.com/dwmkerr/wait-port/commit/b980aa8))
