# Changelog

All notable changes to this project will be documented in this file, in reverse chronological order by release.

## 2.4.5 - 2015-07-28

### Added

- Nothing.

### Deprecated

- Nothing.

### Removed

- Nothing.

### Fixed

- [zendframework/zend-inputfilter#7](https://github.com/zendframework/zend-inputfilter/pull/7) fixes an issue
  with the combination of `required` and `allow_empty`, now properly
  invalidating a data set if the `required` input is missing entirely
  (previously, it would consider the data set valid, and auto-initialize the
  missing input to `null`).
