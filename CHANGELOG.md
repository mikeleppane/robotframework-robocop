# Changelog

## 0.1.0 (2025-12-23)


### Features

* add commented-out-code detection rule (COM06) ([#1564](https://github.com/mikeleppane/robotframework-robocop/issues/1564)) ([8afa9d2](https://github.com/mikeleppane/robotframework-robocop/commit/8afa9d268d4ca909cf56225992962c39a088f8bf))
* add docs_urls property to rule class ([#1545](https://github.com/mikeleppane/robotframework-robocop/issues/1545)) ([ab29942](https://github.com/mikeleppane/robotframework-robocop/commit/ab299428a84e3c53980c167674332293277c6306))
* add extend-select linter option ([#1554](https://github.com/mikeleppane/robotframework-robocop/issues/1554)) ([851bb4d](https://github.com/mikeleppane/robotframework-robocop/commit/851bb4df28ca014483dd9c01f7279314b2e42fee))
* add file-level caching for linter and formatter to skip unchanged files ([#1565](https://github.com/mikeleppane/robotframework-robocop/issues/1565)) ([ceb02cc](https://github.com/mikeleppane/robotframework-robocop/commit/ceb02ccff7cf5316ef8debb5040bfa625981eba0))
* add three separate rules for variable type annotations (RF 7.3+) ([#1579](https://github.com/mikeleppane/robotframework-robocop/issues/1579)) ([03ef483](https://github.com/mikeleppane/robotframework-robocop/commit/03ef483446a153137035c48f8f6e63ce02cca480))
* allow to manually disable report ([#1543](https://github.com/mikeleppane/robotframework-robocop/issues/1543)) ([856f5dd](https://github.com/mikeleppane/robotframework-robocop/commit/856f5ddafb10efb7b241f76d0a4c80e0de70fbc1))
* automate release process with release-please ([#1571](https://github.com/mikeleppane/robotframework-robocop/issues/1571)) ([4bd6d3f](https://github.com/mikeleppane/robotframework-robocop/commit/4bd6d3f5cddaa4c85085ca87b8960720e77d8dd6))
* change mixed-tabs-and-spaces rule behaviour to report all occurences of mixed tabs and spaces in a file ([#1530](https://github.com/mikeleppane/robotframework-robocop/issues/1530)) ([b90c8be](https://github.com/mikeleppane/robotframework-robocop/commit/b90c8be7cd72e6be8078b77bcb25e7d1fb5f8b42))
* extend disablers to ignore whole node ([#1551](https://github.com/mikeleppane/robotframework-robocop/issues/1551)) ([8bb27f7](https://github.com/mikeleppane/robotframework-robocop/commit/8bb27f749b968d7be8081cf1bb4b081ed73f3c19))
* Ignore unused variables starting with `_` underscore ([#1550](https://github.com/mikeleppane/robotframework-robocop/issues/1550)) ([6c325b5](https://github.com/mikeleppane/robotframework-robocop/commit/6c325b554fedea7089c600509d36a88e016b8ce6))
* Implement multiple configuration files config manager ([#1208](https://github.com/mikeleppane/robotframework-robocop/issues/1208)) ([957aa12](https://github.com/mikeleppane/robotframework-robocop/commit/957aa12a49ae39176ca7b7bc090299f183f84f21))
* inherit another configuration file with extends option ([#1537](https://github.com/mikeleppane/robotframework-robocop/issues/1537)) ([6a514b1](https://github.com/mikeleppane/robotframework-robocop/commit/6a514b117fa53be6e1546612cc3b37f5ad30e132))
* Integrate Formatter with Robocop ([#1210](https://github.com/mikeleppane/robotframework-robocop/issues/1210)) ([ca524c3](https://github.com/mikeleppane/robotframework-robocop/commit/ca524c3ba29a8a50fb84a95f32492a0c1cdf69ff))
* per_file_ignores option to ignore rules matching file patterns ([#1542](https://github.com/mikeleppane/robotframework-robocop/issues/1542)) ([a8be5b1](https://github.com/mikeleppane/robotframework-robocop/commit/a8be5b1a84352b6a010aa9df33cec32d493c2d4d))
* rename custom-formatters to extend-select ([#1553](https://github.com/mikeleppane/robotframework-robocop/issues/1553)) ([0df328a](https://github.com/mikeleppane/robotframework-robocop/commit/0df328ab858c1e3a1e8adf7ea7d877252966afce))
* restore project checks as separate command ([#1556](https://github.com/mikeleppane/robotframework-robocop/issues/1556)) ([e06371c](https://github.com/mikeleppane/robotframework-robocop/commit/e06371c5ae0f2896ea0129b0d8f63e261dec3e71))
* split too long settings from settings section ([#1559](https://github.com/mikeleppane/robotframework-robocop/issues/1559)) ([9bf3788](https://github.com/mikeleppane/robotframework-robocop/commit/9bf3788106b369ce16b66b4de037e1cd64998cd3))
* Split wrong-case-in-keyword-name into itself and wrong-case-in-keyword-call ([10393cb](https://github.com/mikeleppane/robotframework-robocop/commit/10393cb9295a8b12ff25793e039b2b93fc9c16bf))
* **VAR02:** add ignore parameter for unused-variable rule ([#1576](https://github.com/mikeleppane/robotframework-robocop/issues/1576)) ([0c2ebf4](https://github.com/mikeleppane/robotframework-robocop/commit/0c2ebf41a2f43f0cb73e586b3e254c02cdfacf7c))


### Bug Fixes

* `wrong-case-in-keyword-name` rule false positive reports on `.` characters ([#1561](https://github.com/mikeleppane/robotframework-robocop/issues/1561)) ([f2eb584](https://github.com/mikeleppane/robotframework-robocop/commit/f2eb5848ed5b98ea171c6c5d814da5b880117184))
* elevating scope of variable raises possible-variable-overwritting ([#1064](https://github.com/mikeleppane/robotframework-robocop/issues/1064)) ([e5d30f4](https://github.com/mikeleppane/robotframework-robocop/commit/e5d30f418402cd64896844d517ec46daaeff4b9a))
* Fix `AlignKeywordsSection` and `AlignTestCasesSection` not aligning VAR variables ([#1531](https://github.com/mikeleppane/robotframework-robocop/issues/1531)) ([4aa28a3](https://github.com/mikeleppane/robotframework-robocop/commit/4aa28a30eb6b883e61f9e188297b6cdbad3537a6))
* ignore variables in tags & keyword tags ([#1066](https://github.com/mikeleppane/robotframework-robocop/issues/1066)) ([ecfd497](https://github.com/mikeleppane/robotframework-robocop/commit/ecfd4977e694ee6df824982a88aa143dbbd94931))
* Invalid Robocop disabler accepted as disabler for all rules ([#1569](https://github.com/mikeleppane/robotframework-robocop/issues/1569)) ([595ffdb](https://github.com/mikeleppane/robotframework-robocop/commit/595ffdb83a3b50ccebf4883493b221076782836b))
* optional `no-embedded-keyword-arguments` rule fatal exception when reading a file with invalid syntax ([#1534](https://github.com/mikeleppane/robotframework-robocop/issues/1534)) ([cc7e83f](https://github.com/mikeleppane/robotframework-robocop/commit/cc7e83f4dcd1c51e1a7f169d41011672061e262e))
* path to dependency file should be directory ([#1154](https://github.com/mikeleppane/robotframework-robocop/issues/1154)) ([7b165cd](https://github.com/mikeleppane/robotframework-robocop/commit/7b165cd72e1901963e66a188f2f9c646e250286d))
* piping output not working on WIndows because of code lines converted to emojis ([#1541](https://github.com/mikeleppane/robotframework-robocop/issues/1541)) ([07aea82](https://github.com/mikeleppane/robotframework-robocop/commit/07aea82e8bfa07adbdea545d9d2ecacbd0411210))
* unused-variable if first declared as argument and used in the loop ([#978](https://github.com/mikeleppane/robotframework-robocop/issues/978)) ([75f5556](https://github.com/mikeleppane/robotframework-robocop/commit/75f55566d81032fc76a9b70160b55a5167fa91b0))
* unused-variable with variables in [Setup], [Teardown] and [Timeout] ([#1063](https://github.com/mikeleppane/robotframework-robocop/issues/1063)) ([dfad472](https://github.com/mikeleppane/robotframework-robocop/commit/dfad4721de25d50c6dc2a9e65d072aecc05ff7f5))


### Documentation

* Add caching documentation ([#1572](https://github.com/mikeleppane/robotframework-robocop/issues/1572)) ([5d941e8](https://github.com/mikeleppane/robotframework-robocop/commit/5d941e849f5ac84a8208b1d21ccdf861006b4cbc))
* Add deprecated_names section to rules list in docs ([#1529](https://github.com/mikeleppane/robotframework-robocop/issues/1529)) ([c8f6ddf](https://github.com/mikeleppane/robotframework-robocop/commit/c8f6ddfc86b17af2d6914ec3979ff5c2c656dbc7))
* add megalinter integration page ([#1558](https://github.com/mikeleppane/robotframework-robocop/issues/1558)) ([efb2672](https://github.com/mikeleppane/robotframework-robocop/commit/efb2672286fbec56b889d0a7af61d8314935b304))
* improve changelog for 7.0.0 ([#1563](https://github.com/mikeleppane/robotframework-robocop/issues/1563)) ([97f429b](https://github.com/mikeleppane/robotframework-robocop/commit/97f429b6afd15e9f5d116307eaf9ffc8a8025504))
