# Change Log

## [3.3.0](2018-05-21)

### Fixed

* Promisifying client.connect [#265](https://github.com/salsita/node-pg-migrate/pull/265)

## [3.2.1](2018-05-21)

### Fixed

* Fix type name issue when the type is not in the default schema [#264](https://github.com/salsita/node-pg-migrate/pull/264)

## [3.2.0](2018-05-17)

### Added

* Add support for opclass option in createIndex [#259](https://github.com/salsita/node-pg-migrate/pull/259)
* Ability to specify extension schema [#260](https://github.com/salsita/node-pg-migrate/pull/260)

## [3.1.2](2018-05-14)

### Fixed

* Using dollar-quoted strings in comments [#255](https://github.com/salsita/node-pg-migrate/pull/255)

## [3.1.1](2018-05-02)

### Fixed

* Fixing optional options in create and drop statements [#250](https://github.com/salsita/node-pg-migrate/pull/250)

## [3.1.0](2018-04-19)

### Added

* Handling SQL files [#246](https://github.com/salsita/node-pg-migrate/pull/246)

## [3.0.0](2018-04-12)

## [3.0.0-rc5](2018-04-06)

### Fixed

* Fix comment not being optional [#244](https://github.com/salsita/node-pg-migrate/pull/244)
* Fix behavior when singleTransaction is not set [#245](https://github.com/salsita/node-pg-migrate/pull/245)

## [3.0.0-rc4](2018-04-03)

### Changed

* Implement failsafe locking [#239](https://github.com/salsita/node-pg-migrate/pull/239)
* Updated docs about locking [#240](https://github.com/salsita/node-pg-migrate/pull/240)

## [3.0.0-rc3](2018-04-03)

### Added

* Add log option to runner.js [#238](https://github.com/salsita/node-pg-migrate/pull/238)
* Structuring docs [#237](https://github.com/salsita/node-pg-migrate/pull/237)
* Prettier formatting [#236](https://github.com/salsita/node-pg-migrate/pull/236)
* Displaying function name on infer failure [#235](https://github.com/salsita/node-pg-migrate/pull/235)
* Materialized views handling [#234](https://github.com/salsita/node-pg-migrate/pull/234)
* Handling Views [#233](https://github.com/salsita/node-pg-migrate/pull/233)
* Cockroach test [#231](https://github.com/salsita/node-pg-migrate/pull/231)
* Prettier [#230](https://github.com/salsita/node-pg-migrate/pull/230)

## [3.0.0-rc2](2018-03-26)

### Fixed

* Fixing setting comments on columns [#228](https://github.com/salsita/node-pg-migrate/pull/228)

## [2.26.3](2018-03-26)

### Fixed

* Fixing setting comments on columns [#228](https://github.com/salsita/node-pg-migrate/pull/228)

# [3.0.0-rc](2018-03-23)

### Breaking changes

* Single transaction as default [#205](https://github.com/salsita/node-pg-migrate/pull/205)
* Versioning type shorthands [#190](https://github.com/salsita/node-pg-migrate/pull/190)
  (type shorthands were moved from global config to migrations scripts)
* Using camel case in API [#189](https://github.com/salsita/node-pg-migrate/pull/189)
* Removed `pg-migrate` script
  (use `node-pg-migrate`)

### Added

* Running test migrations on CircleCI [#221](https://github.com/salsita/node-pg-migrate/pull/221)

## [2.26.2](2018-03-23)

### Fixed

* Fix runner for zero migrations [#224](https://github.com/salsita/node-pg-migrate/pull/224)

## [2.26.1](2018-03-23)

### Fixed

* Fixing altering role [#222](https://github.com/salsita/node-pg-migrate/pull/222)
* Fixes from 3.0 [#223](https://github.com/salsita/node-pg-migrate/pull/223)

## [2.26.0](2018-03-16)

### Added

* Support for policies [#219](https://github.com/salsita/node-pg-migrate/pull/219)

## [2.25.1](2018-03-16)

### Fixed

* Role inherit fix [#218](https://github.com/salsita/node-pg-migrate/pull/218)

## [2.25.0](2018-03-08)

### Fixed

* (No)Transaction handling [#213](https://github.com/salsita/node-pg-migrate/pull/213)
* Parens around INHERITS clause [#214](https://github.com/salsita/node-pg-migrate/pull/214)

### Added

* Exposing DB [#212](https://github.com/salsita/node-pg-migrate/pull/212)

## [2.24.1](2018-03-05)

### Fixed

* Fix auto create schema [#206](https://github.com/salsita/node-pg-migrate/pull/206)

## [2.24.0](2018-03-01)

### Added

* Add `--single-transaction` option [#204](https://github.com/salsita/node-pg-migrate/pull/204)

## [2.23.1](2018-02-21)

### Fixed

* Correct handling of multiline constraints [#202](https://github.com/salsita/node-pg-migrate/pull/202)

## [2.23.0](2018-02-20)

### Changed

* Updating deps, removing vulnerablity status for peer and optional dependencies [#199](https://github.com/salsita/node-pg-migrate/pull/199)
* Removing regex [#198](https://github.com/salsita/node-pg-migrate/pull/198)
* Adding ability to specify database name with 'database' option [#197](https://github.com/salsita/node-pg-migrate/pull/197)

## [2.22.2](2018-02-20)

### Fixed

* Role encrypted default [#196](https://github.com/salsita/node-pg-migrate/pull/196)
* Running queries in order [#195](https://github.com/salsita/node-pg-migrate/pull/195)

## [2.22.1](2018-02-20)

### Fixed

* Passing props [#194](https://github.com/salsita/node-pg-migrate/pull/194)

## [2.22.0](2018-02-20)

### Added

* Auto create configured schemas if they don't exist [#192](https://github.com/salsita/node-pg-migrate/pull/192)
* Add ifNotExists option to create extension [#188](https://github.com/salsita/node-pg-migrate/pull/188)
* Programmatic API docs [#187](https://github.com/salsita/node-pg-migrate/pull/187)

## [2.21.0](2018-02-12)

### Added

* Table and column comments [#183](https://github.com/salsita/node-pg-migrate/pull/183)

## [2.19.0](2018-02-06)

### Added

* `migration-file-language` can be set in config file [#180](https://github.com/salsita/node-pg-migrate/pull/180)
* Treat number argument to up/down migration as timestamp [#179](https://github.com/salsita/node-pg-migrate/pull/179)

## [2.18.1](2018-02-06)

### Fixed

* Fixing addConstraint method with object expression [#176](https://github.com/salsita/node-pg-migrate/pull/176)

## [2.18.0](2018-02-05)

### Added

* Add no lock option [#171](https://github.com/salsita/node-pg-migrate/pull/171)
* Updated docs [#174](https://github.com/salsita/node-pg-migrate/pull/174)

### Changed

* Remove old version number from index.d.ts [#173](https://github.com/salsita/node-pg-migrate/pull/173)
* Remove default match in column reference [#172](https://github.com/salsita/node-pg-migrate/pull/172)
* Refactor code to use camel casing [#167](https://github.com/salsita/node-pg-migrate/pull/167)

## [2.17.0](2018-01-26)

### Added

* Added typescript migration template [#165](https://github.com/salsita/node-pg-migrate/pull/165)
* Updated type definitions to accept db client config [#166](https://github.com/salsita/node-pg-migrate/pull/166)

## [2.16.2](2018-01-25)

### Fixed

* Deleted duplicate declaration [#164](https://github.com/salsita/node-pg-migrate/pull/164)

## [2.16.1](2018-01-25)

### Changed

* Updated dependencies [#158](https://github.com/salsita/node-pg-migrate/pull/158)

### Fixed

* Typescript definition fixes [#162](https://github.com/salsita/node-pg-migrate/pull/162)

## [2.16.0](2018-01-23)

### Added

* Uniting drop statements [#154](https://github.com/salsita/node-pg-migrate/pull/154)
* Handling domains [#155](https://github.com/salsita/node-pg-migrate/pull/155)
* Operator operations [#156](https://github.com/salsita/node-pg-migrate/pull/156)
* Sequences operations [#157](https://github.com/salsita/node-pg-migrate/pull/157)

## [2.15.0](2018-01-11)

### Fixed

* Handle rejections in migration actions [#148](https://github.com/salsita/node-pg-migrate/pull/148)

### Added

* TypeScript declaration file [#147](https://github.com/salsita/node-pg-migrate/pull/147) [#150](https://github.com/salsita/node-pg-migrate/pull/150)

## [2.14.0](2017-11-14)

### Added

* Deferrable column constraints [#139](https://github.com/salsita/node-pg-migrate/pull/139)
* Possibility to use function in multi-column index [#140](https://github.com/salsita/node-pg-migrate/pull/140)

### Changed

* Changed all references from pg-migrate to node-pg-migrate [#141](https://github.com/salsita/node-pg-migrate/pull/141)

  !!! Breaking change from version 3 !!! (now with warning)

## [2.13.2](2017-11-03)

### Fixed

* Cannot use embedded value in config [#137](https://github.com/salsita/node-pg-migrate/pull/137)
* add space before `USING` keyword [#138](https://github.com/salsita/node-pg-migrate/pull/138)

## [2.13.1](2017-10-23)

### Fixed

* addTypeValue's `after` option is using BEFORE instead of AFTER [#133](https://github.com/salsita/node-pg-migrate/pull/133)

## [2.13.0](2017-10-12)

### Added

* Ability to specify files to ignore in migrations directory [#131](https://github.com/salsita/node-pg-migrate/pull/131)

## [2.12.0](2017-10-09)

### Fixed

* Dollar quoted string constants [#127](https://github.com/salsita/node-pg-migrate/pull/127)
* Table unique constraint can be array of arrays [#126](https://github.com/salsita/node-pg-migrate/pull/126)

### Changed

* If user disables migration, return Error instead of string [#125](https://github.com/salsita/node-pg-migrate/pull/125)
* Circle CI integration [#124](https://github.com/salsita/node-pg-migrate/pull/124)
* Moved to Salsita organization [#122](https://github.com/salsita/node-pg-migrate/pull/122)

## [2.11.1](2017-09-26)

### Fixed

* Fixed SQL for dropping multiple columns [#120](https://github.com/salsita/node-pg-migrate/pull/120)

## [2.11.0](2017-09-25)

### Added

* Schemas operations [#119](https://github.com/salsita/node-pg-migrate/pull/119)

## [2.10.1](2017-09-25)

### Fixed

* Fixed invalid SQL for table level foreign key [#118](https://github.com/salsita/node-pg-migrate/pull/118)

## [2.10.0](2017-09-21)

### Added

* Ability to specify constraints on table level [#114](https://github.com/salsita/node-pg-migrate/pull/114)

## [2.9.0](2017-09-12)

### Added

* Alter type functions [#111](https://github.com/salsita/node-pg-migrate/pull/111)
* redo command [#112](https://github.com/salsita/node-pg-migrate/pull/112)

## [2.8.2](2017-09-11)

### Fixed

* Fix automatic reversal of addColumns [#110](https://github.com/salsita/node-pg-migrate/pull/110)

## [2.8.1](2017-09-06)

### Fixed

* Fixing referencing column [#107](https://github.com/salsita/node-pg-migrate/pull/107)

### Changed

* Formatting changes, added licence [#108](https://github.com/salsita/node-pg-migrate/pull/108)

## [2.8.0](2017-09-04)

### Added

* Trigger operations [#104](https://github.com/salsita/node-pg-migrate/pull/104)

## [2.7.1](2017-08-28)

### Fixed

* Support object with schema and table name in more places [#105](https://github.com/salsita/node-pg-migrate/pull/105)

## [2.7.0](2017-08-01)

### Added

* Function operations [#103](https://github.com/salsita/node-pg-migrate/pull/103)

## [2.6.0](2017-07-20)

### Added

* Support for pg >=4.3.0 <8.0.0
* Interpret only files as migrations in migration directory [#101](https://github.com/salsita/node-pg-migrate/pull/101)

## [2.5.0](2017-07-19)

### Added

* USING clause in alter column [#99](https://github.com/salsita/node-pg-migrate/pull/99)
* Role operations [#100](https://github.com/salsita/node-pg-migrate/pull/100)

## [2.4.0](2017-07-17)

### Changed

* Do not check file extension of migration file [#93](https://github.com/salsita/node-pg-migrate/pull/93)

## [2.3.0](2017-06-20)

### Added

* JSON config and type shorthands [see](README.md#json-configuration) [#91](https://github.com/salsita/node-pg-migrate/pull/91)

## [2.2.1](2017-05-26)

### Fixed

* Syntax error in node 4

## [2.2.0](2017-05-25)

### Added

* Better error logging [#86](https://github.com/salsita/node-pg-migrate/pull/86)
* Locking migrations [#88](https://github.com/salsita/node-pg-migrate/pull/88)
* Updated docs [#89](https://github.com/salsita/node-pg-migrate/pull/89)

## [2.1.1](2017-05-18)

### Fixed

* Down migration when down method is inferred [#84](https://github.com/salsita/node-pg-migrate/pull/84)

## [2.1.0](2017-05-10)

### Added

* Enable string functions and arrays as default column values [#82](https://github.com/salsita/node-pg-migrate/pull/82)

## [2.0.0](2017-04-28)

Rewritten using es6 (transpiled via [babel](https://babeljs.io/)) and Promises.

### Breaking Changes

* supports only node >= 4
* `check-order` flag now defaults to `true` (to switch it off supply `--no-check-order` on command line)
* [dotenv](https://www.npmjs.com/package/dotenv) package is `optionalDependency`
* `s` option is now alias for `schema` which sets schema for migrations SQL, if you only need to change schema of migrations table use `--migrations-schema`

### Added

* [config](https://www.npmjs.com/package/config) package as `optionalDependency`
* Migration can return `Promise`
