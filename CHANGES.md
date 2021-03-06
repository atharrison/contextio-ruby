# Changes

## 1.2.4

* Add link to gem documentation to top of README. - Ben Hamill
* Expand README to clarify gem usage. - Ben Hamill
* Make `ResourceCollection#[]` correctly pass down the "owning" associated
  object to instances created with it. - Ben Hamill
* Work around the OAuth gem handling PUT request signing a bit oddly. - Ben
  Hamill

## 1.2.3

* Fix infinite loop in ConnectToken URL building. - Ben Hamill

## 1.2.2

* Fix `PUT` and `POST` parameter submission. - Ben Hamill
* Added missing `server` argument to `SourceCollection.create`. - Dominik Gehl
* Moved erroneous `File.sync_data` and `File.sync!` over to `Source` where it
  belonged in the first place. - Bram Plessers

## 1.2.1

* Fixed syntax error typo in previous release. - Geoff Longman

## 1.2.0

* Add `#empty?` and `#size` to resource collections so you can treat them even
  *more* like arrays! - Geoff Longman

## 1.1.0

* Allow passing options to `OAuth` through the gem. Notably, `:timeout` and
  `:open_timeout`. - Geoff Longman

## 1.0.1

* Updated homepage link in README distributed with the gem. - Ben Hamill
