# Logger program changelog


## Next release

### Data Table Changes

* In table *tsdata*, remove any suffixes denoting processing. The suffixes are
  still present in table *stats*.
* In tables *tsdata* and *stats*, change capitalization so abbreviations of
  'sulfur dioxide' are `SO2` not `so2`
* New data table *settings_hist* contains historical record of settings used
  by the program, including the user-defined linear scaling applied to gas
  analyzers

### Fixes made

* Add user-defined linear scaling to each gas analyzer, for use in applying
  calibration coefficients



## 20171222-deploy

This is the original release. 

### Known issues

* No calibration scaling applied to gas analyzers. Some are in good shape but
  others have significant deviations without the appropriate linear scaling.

