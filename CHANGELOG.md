## 2021-04-23 Release 0.2.2
###Summary

Minor change to allow installation without errors on Ubuntu 18.04 bionic

### Feature
- Support Ubuntu 18.04 (bionic)

## 2021-03-17 Release 0.2.1
###Summary

Minor change to allow installation without errors on Debian 10.

### Feature
- Support Debian 10 (buster)

## 2017-03-13 Release 0.2.0
###Summary
This release added features for plain config files and blocks.
I also did some refactoring to allign with the recommended puppet module structure.

### Feature
- Add define `syslog_ng::block`
- Add define `syslog_ng::config::file`
- Add define `syslog_ng::config::template`

## 2017-03-07 Release 0.1.2
###Summary
Minor bug fixes and some new features

###Features
- Allow IPv6 in source and destination
- Allow Array in source and destination
- Support for Debian stretch

## 2015-03-15 Release 0.1.1
###Summary
This release fixes some bugs and add a rough implementation of syslog_ng::rewrite and syslog_ng::parser

###Features
- Add `syslog_ng::rewrite` define
- Add `syslog_ng::parser` define
 
## 2015-01-18 Release 0.1.0
###Summary
This is the initial release
