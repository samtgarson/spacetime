# v1.0.0 :rocket:

## v1.2.0
* adds isBetween() method

## v1.3.0
* adds `spacetime.whereIts()` method
* actually implement 😓 season by hemisphere

## v1.3.1
* adds `spacetime.i18n()` method
* adds `spacetime.nearest()` method
* support for `"quarterHour"` units - '4:15, 4:30, 4:45, 5:00' etc

## v1.3.2
* fix for inf-loop regression on DST-switch

## v2.0.0
* fix major [southern-hemisphere issue](https://github.com/smallwins/spacetime/issues/27)
* re-structure `d.timezone()` response
* add `.hemisphere()` method
* use proper short-day forms
## v2.1.0
* support unix/unicode time-formating basic-level
* add `.era()` get/set method
* found 6 or 7 wrong offsets
