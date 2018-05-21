# @my-ideas/winston-cloudwatch 
[![Build Status](https://travis-ci.org/my-ideas/winston-cloudwatch.svg?branch=master)](https://travis-ci.org/my-ideas/winston-cloudwatch)

Forked from [v1.13.1](https://github.com/lazywithclass/winston-cloudwatch/blob/master/CHANGELOG.md#1131)

# Why?

Mainly to reduce the footprint of this great module!

* `aws-sdk` and `winston` are peer dependencies
* removed `chalk` - used only to colorize debug statement
* removed `lodash` - where used only `_.isEmpty` which has been replaced with a lodash-compatible function
* removed `proxy-agent` - no support for http proxy in this version

## Todo
* Remove `async`  

