# Change Log

## [0.2.8](https://github.com/inaka/erlang-github/tree/0.2.8) (2016-07-22)
[Full Changelog](https://github.com/inaka/erlang-github/compare/0.2.7...0.2.8)

**Closed issues:**

- Add support for getting languages by repo [\#112](https://github.com/inaka/erlang-github/issues/112)

**Merged pull requests:**

- \[Fix \#112\] Add support for getting languages by repository [\#113](https://github.com/inaka/erlang-github/pull/113) ([harenson](https://github.com/harenson))

## [0.2.7](https://github.com/inaka/erlang-github/tree/0.2.7) (2016-06-14)
[Full Changelog](https://github.com/inaka/erlang-github/compare/0.2.6...0.2.7)

**Fixed bugs:**

- create\_team not working [\#110](https://github.com/inaka/erlang-github/pull/110) ([elbrujohalcon](https://github.com/elbrujohalcon))

**Merged pull requests:**

- Version bump to 0.2.7 [\#111](https://github.com/inaka/erlang-github/pull/111) ([elbrujohalcon](https://github.com/elbrujohalcon))

## [0.2.6](https://github.com/inaka/erlang-github/tree/0.2.6) (2016-05-17)
[Full Changelog](https://github.com/inaka/erlang-github/compare/0.2.5...0.2.6)

**Merged pull requests:**

- Version Bump to 0.2.6 [\#109](https://github.com/inaka/erlang-github/pull/109) ([elbrujohalcon](https://github.com/elbrujohalcon))
- Add `jiffy` to the applications list [\#108](https://github.com/inaka/erlang-github/pull/108) ([alemata](https://github.com/alemata))

## [0.2.5](https://github.com/inaka/erlang-github/tree/0.2.5) (2016-05-09)
[Full Changelog](https://github.com/inaka/erlang-github/compare/0.2.4...0.2.5)

**Fixed bugs:**

- Rebar config script has old dependencies [\#106](https://github.com/inaka/erlang-github/pull/106) ([alemata](https://github.com/alemata))

**Merged pull requests:**

- Version Bump to 0.2.5 [\#107](https://github.com/inaka/erlang-github/pull/107) ([elbrujohalcon](https://github.com/elbrujohalcon))

## [0.2.4](https://github.com/inaka/erlang-github/tree/0.2.4) (2016-05-04)
[Full Changelog](https://github.com/inaka/erlang-github/compare/0.2.3...0.2.4)

**Fixed bugs:**

- When running events without credentials, not all outputs are handled [\#105](https://github.com/inaka/erlang-github/pull/105) ([elbrujohalcon](https://github.com/elbrujohalcon))
- Hackney expects uris to be binaries [\#101](https://github.com/inaka/erlang-github/pull/101) ([elbrujohalcon](https://github.com/elbrujohalcon))

**Closed issues:**

- Version Bump to 0.2.3 [\#99](https://github.com/inaka/erlang-github/issues/99)

**Merged pull requests:**

- \[\#103\] fix hackney issue in suite [\#104](https://github.com/inaka/erlang-github/pull/104) ([Euen](https://github.com/Euen))
- Use hackney:request instead of hackney:send\_request [\#103](https://github.com/inaka/erlang-github/pull/103) ([elbrujohalcon](https://github.com/elbrujohalcon))
- Version Bump to 0.2.4 [\#102](https://github.com/inaka/erlang-github/pull/102) ([elbrujohalcon](https://github.com/elbrujohalcon))

## [0.2.3](https://github.com/inaka/erlang-github/tree/0.2.3) (2016-04-18)
[Full Changelog](https://github.com/inaka/erlang-github/compare/0.2.2...0.2.3)

**Closed issues:**

- Replace shotgun with hackney library [\#97](https://github.com/inaka/erlang-github/issues/97)

**Merged pull requests:**

- \[\#99\] Version Bump to 0.2.3 [\#100](https://github.com/inaka/erlang-github/pull/100) ([davecaos](https://github.com/davecaos))
- \[\#97\] replaced shotgun with hackney dependency [\#98](https://github.com/inaka/erlang-github/pull/98) ([davecaos](https://github.com/davecaos))

## [0.2.2](https://github.com/inaka/erlang-github/tree/0.2.2) (2016-04-06)
[Full Changelog](https://github.com/inaka/erlang-github/compare/0.1.19...0.2.2)

**Fixed bugs:**

- Failing when listing organization repositories [\#95](https://github.com/inaka/erlang-github/issues/95)

**Closed issues:**

- Update repo and make it ready for hex.pm [\#90](https://github.com/inaka/erlang-github/issues/90)
- Update type to fix gadget login [\#89](https://github.com/inaka/erlang-github/issues/89)
- Add TargetURL parameter in egithub\_webhook:event [\#85](https://github.com/inaka/erlang-github/issues/85)
- Requirements [\#82](https://github.com/inaka/erlang-github/issues/82)
- Hex.pm Package [\#61](https://github.com/inaka/erlang-github/issues/61)

**Merged pull requests:**

- \[Fix \#95\] Add per\_page param when listing organization repositories [\#96](https://github.com/inaka/erlang-github/pull/96) ([harenson](https://github.com/harenson))
- \[Fix \#85\] Transform Header list to map and fix tests [\#94](https://github.com/inaka/erlang-github/pull/94) ([Euen](https://github.com/Euen))
- \[Fix \#85\] fix fail parameter in egithub\_webhook:specify\_status/5 [\#93](https://github.com/inaka/erlang-github/pull/93) ([Euen](https://github.com/Euen))
- Fix bug in getting issues [\#92](https://github.com/inaka/erlang-github/pull/92) ([tgrk](https://github.com/tgrk))
- \[Fix \#90\] Update dependencies; Update erlang.mk; Add ruleset to elvis config [\#91](https://github.com/inaka/erlang-github/pull/91) ([harenson](https://github.com/harenson))
- Fix egithub tests [\#88](https://github.com/inaka/erlang-github/pull/88) ([Euen](https://github.com/Euen))
- \[Fix \#85\] Add TargetUrl and dialyzer [\#87](https://github.com/inaka/erlang-github/pull/87) ([Euen](https://github.com/Euen))
- Fix build for rebar2 [\#84](https://github.com/inaka/erlang-github/pull/84) ([tgrk](https://github.com/tgrk))
- Add support for creating and listing issues [\#83](https://github.com/inaka/erlang-github/pull/83) ([tgrk](https://github.com/tgrk))
- Update shotgun dep to 0.2.2 [\#81](https://github.com/inaka/erlang-github/pull/81) ([elbrujohalcon](https://github.com/elbrujohalcon))
- Version bump to 0.2.1 [\#80](https://github.com/inaka/erlang-github/pull/80) ([cabol](https://github.com/cabol))
- Switch build tools to erlang.mk and republish to hex.pm [\#79](https://github.com/inaka/erlang-github/pull/79) ([elbrujohalcon](https://github.com/elbrujohalcon))
- Replace ibrowse by shotgun [\#60](https://github.com/inaka/erlang-github/pull/60) ([elbrujohalcon](https://github.com/elbrujohalcon))

## [0.1.19](https://github.com/inaka/erlang-github/tree/0.1.19) (2016-01-05)
[Full Changelog](https://github.com/inaka/erlang-github/compare/0.1.18...0.1.19)

**Fixed bugs:**

- Looks like the project doesn't compile on Linux [\#73](https://github.com/inaka/erlang-github/issues/73)

**Closed issues:**

- Bump version to 0.1.19 [\#77](https://github.com/inaka/erlang-github/issues/77)
- rename egithub\_webhook:handle\_pull\_request/3 [\#75](https://github.com/inaka/erlang-github/issues/75)

**Merged pull requests:**

- \[Fix \#77\] Bump version to 0.1.19 [\#78](https://github.com/inaka/erlang-github/pull/78) ([harenson](https://github.com/harenson))
- \[Fix \#75\] Rename egithub\_webhook:handle\_pull\_request/3 [\#76](https://github.com/inaka/erlang-github/pull/76) ([harenson](https://github.com/harenson))

## [0.1.18](https://github.com/inaka/erlang-github/tree/0.1.18) (2016-01-04)
[Full Changelog](https://github.com/inaka/erlang-github/compare/0.1.16...0.1.18)

**Closed issues:**

- Version Bump to 0.1.17 [\#71](https://github.com/inaka/erlang-github/issues/71)

**Merged pull requests:**

- Version Bump to 0.1.18 [\#74](https://github.com/inaka/erlang-github/pull/74) ([elbrujohalcon](https://github.com/elbrujohalcon))
- \[\#71\] Version Bump 0.1.17 [\#72](https://github.com/inaka/erlang-github/pull/72) ([davecaos](https://github.com/davecaos))
- \[\#61\] Upload to hex.pm [\#69](https://github.com/inaka/erlang-github/pull/69) ([davecaos](https://github.com/davecaos))
- Get the project up-to-date [\#63](https://github.com/inaka/erlang-github/pull/63) ([elbrujohalcon](https://github.com/elbrujohalcon))

## [0.1.16](https://github.com/inaka/erlang-github/tree/0.1.16) (2015-11-23)
[Full Changelog](https://github.com/inaka/erlang-github/compare/0.1.15...0.1.16)

**Fixed bugs:**

- Tests are not running [\#66](https://github.com/inaka/erlang-github/issues/66)
- Move sync to SHELL\_DEPS [\#62](https://github.com/inaka/erlang-github/issues/62)

**Closed issues:**

- Bump Version to 0.1.16 [\#65](https://github.com/inaka/erlang-github/issues/65)
- Fulfill the open-source checklist [\#4](https://github.com/inaka/erlang-github/issues/4)

**Merged pull requests:**

- \[Fix \#65\] Bump version to 0.1.16 [\#68](https://github.com/inaka/erlang-github/pull/68) ([harenson](https://github.com/harenson))
- \[Fix \#66\] Fix tests [\#67](https://github.com/inaka/erlang-github/pull/67) ([harenson](https://github.com/harenson))
- \[Fix \#62\] Move sync to SHELL\_DEPS [\#64](https://github.com/inaka/erlang-github/pull/64) ([harenson](https://github.com/harenson))
- \[\#4\] Remove test.config since it is not actually used [\#59](https://github.com/inaka/erlang-github/pull/59) ([jfacorro](https://github.com/jfacorro))
- \[\#4\] Tests [\#58](https://github.com/inaka/erlang-github/pull/58) ([jfacorro](https://github.com/jfacorro))
- \[\#4\] Links to examples [\#57](https://github.com/inaka/erlang-github/pull/57) ([jfacorro](https://github.com/jfacorro))
- \[\#4\] Readme and docstrings [\#56](https://github.com/inaka/erlang-github/pull/56) ([jfacorro](https://github.com/jfacorro))
- Use https protocol for git dependencies [\#55](https://github.com/inaka/erlang-github/pull/55) ([guilleiguaran](https://github.com/guilleiguaran))

## [0.1.15](https://github.com/inaka/erlang-github/tree/0.1.15) (2015-06-18)
[Full Changelog](https://github.com/inaka/erlang-github/compare/0.1.14...0.1.15)

**Closed issues:**

- Version Bump to 0.1.15 [\#53](https://github.com/inaka/erlang-github/issues/53)
- Remove Jiffy dependency from egithub.app.src source file [\#51](https://github.com/inaka/erlang-github/issues/51)
- Version Bump 0.1.14 [\#48](https://github.com/inaka/erlang-github/issues/48)

**Merged pull requests:**

- \[\#53\] Version Bump to 0.1.15 [\#54](https://github.com/inaka/erlang-github/pull/54) ([davecaos](https://github.com/davecaos))
- \[\#51\] Removing jiffy from egithub.app.src [\#52](https://github.com/inaka/erlang-github/pull/52) ([davecaos](https://github.com/davecaos))
- Updated license [\#50](https://github.com/inaka/erlang-github/pull/50) ([spike886](https://github.com/spike886))

## [0.1.14](https://github.com/inaka/erlang-github/tree/0.1.14) (2015-06-11)
[Full Changelog](https://github.com/inaka/erlang-github/compare/0.1.13...0.1.14)

**Closed issues:**

- Set stack erlang:get\_stacktrace\(\) to search error in events [\#46](https://github.com/inaka/erlang-github/issues/46)

**Merged pull requests:**

- \[\#48\] Version bump 0.1.14 [\#49](https://github.com/inaka/erlang-github/pull/49) ([davecaos](https://github.com/davecaos))
- \[\#46\] Add erlang:get\_stacktrace\(\) to search errors in event\(\) call [\#47](https://github.com/inaka/erlang-github/pull/47) ([davecaos](https://github.com/davecaos))
- Update LICENSE [\#45](https://github.com/inaka/erlang-github/pull/45) ([andresinaka](https://github.com/andresinaka))
- \[\#42\] Updated change log [\#44](https://github.com/inaka/erlang-github/pull/44) ([davecaos](https://github.com/davecaos))

## [0.1.13](https://github.com/inaka/erlang-github/tree/0.1.13) (2015-04-23)
[Full Changelog](https://github.com/inaka/erlang-github/compare/0.1.12...0.1.13)

**Closed issues:**

- Restrict github status api descriptions to 140 characters [\#42](https://github.com/inaka/erlang-github/issues/42)
- Update dependencies [\#41](https://github.com/inaka/erlang-github/issues/41)

**Merged pull requests:**

- \[\#42\] Add fix for error 422 \[The message submitted is longer that the ma... [\#43](https://github.com/inaka/erlang-github/pull/43) ([davecaos](https://github.com/davecaos))

## [0.1.12](https://github.com/inaka/erlang-github/tree/0.1.12) (2015-04-08)
[Full Changelog](https://github.com/inaka/erlang-github/compare/0.1.11...0.1.12)

**Closed issues:**

- Update CHANGELOG.md [\#36](https://github.com/inaka/erlang-github/issues/36)

**Merged pull requests:**

- REAL Version Bump [\#40](https://github.com/inaka/erlang-github/pull/40) ([elbrujohalcon](https://github.com/elbrujohalcon))
- Version Bump [\#39](https://github.com/inaka/erlang-github/pull/39) ([elbrujohalcon](https://github.com/elbrujohalcon))
- Add status support to egithub\_webhook [\#38](https://github.com/inaka/erlang-github/pull/38) ([elbrujohalcon](https://github.com/elbrujohalcon))
- \[Close \#34\] add function to get user email [\#37](https://github.com/inaka/erlang-github/pull/37) ([Euen](https://github.com/Euen))

## [0.1.11](https://github.com/inaka/erlang-github/tree/0.1.11) (2015-03-30)
[Full Changelog](https://github.com/inaka/erlang-github/compare/0.1.10...0.1.11)

**Implemented enhancements:**

- Add request to get user emails [\#34](https://github.com/inaka/erlang-github/issues/34)

**Merged pull requests:**

- \[Close \#34\] add function to get user email [\#35](https://github.com/inaka/erlang-github/pull/35) ([Euen](https://github.com/Euen))

## [0.1.10](https://github.com/inaka/erlang-github/tree/0.1.10) (2015-03-23)
[Full Changelog](https://github.com/inaka/erlang-github/compare/0.1.9...0.1.10)

**Merged pull requests:**

- Support for Github Status API [\#33](https://github.com/inaka/erlang-github/pull/33) ([elbrujohalcon](https://github.com/elbrujohalcon))

## [0.1.9](https://github.com/inaka/erlang-github/tree/0.1.9) (2015-03-09)
[Full Changelog](https://github.com/inaka/erlang-github/compare/0.1.8...0.1.9)

**Implemented enhancements:**

- Add API call to get a users organisation's membership [\#30](https://github.com/inaka/erlang-github/issues/30)

**Fixed bugs:**

- xref is not working [\#29](https://github.com/inaka/erlang-github/issues/29)

**Merged pull requests:**

- \[\#30\] Bumped version. [\#32](https://github.com/inaka/erlang-github/pull/32) ([jfacorro](https://github.com/jfacorro))
- \[Closes \#30\] User organisation membership. [\#31](https://github.com/inaka/erlang-github/pull/31) ([jfacorro](https://github.com/jfacorro))

## [0.1.8](https://github.com/inaka/erlang-github/tree/0.1.8) (2015-03-04)
[Full Changelog](https://github.com/inaka/erlang-github/compare/0.1.7...0.1.8)

**Merged pull requests:**

- Version Bump [\#28](https://github.com/inaka/erlang-github/pull/28) ([elbrujohalcon](https://github.com/elbrujohalcon))
- Handle github rate limits [\#27](https://github.com/inaka/erlang-github/pull/27) ([elbrujohalcon](https://github.com/elbrujohalcon))

## [0.1.7](https://github.com/inaka/erlang-github/tree/0.1.7) (2015-02-18)
[Full Changelog](https://github.com/inaka/erlang-github/compare/0.1.6...0.1.7)

**Implemented enhancements:**

- Handle comments with position 0 as global issue comments  [\#25](https://github.com/inaka/erlang-github/issues/25)
- Add a function for creating comments in issues [\#23](https://github.com/inaka/erlang-github/issues/23)

**Merged pull requests:**

- \[Closes \#25\] Handle messages with position 0 as global issue comments. [\#26](https://github.com/inaka/erlang-github/pull/26) ([jfacorro](https://github.com/jfacorro))

## [0.1.6](https://github.com/inaka/erlang-github/tree/0.1.6) (2015-02-13)
[Full Changelog](https://github.com/inaka/erlang-github/compare/0.1.5...0.1.6)

**Merged pull requests:**

- \[\#23\] Added issue comment creation and list API calls. [\#24](https://github.com/inaka/erlang-github/pull/24) ([jfacorro](https://github.com/jfacorro))

## [0.1.5](https://github.com/inaka/erlang-github/tree/0.1.5) (2015-01-14)
[Full Changelog](https://github.com/inaka/erlang-github/compare/0.1.4...0.1.5)

**Merged pull requests:**

- Bump Version to 0.1.5 [\#22](https://github.com/inaka/erlang-github/pull/22) ([elbrujohalcon](https://github.com/elbrujohalcon))

## [0.1.4](https://github.com/inaka/erlang-github/tree/0.1.4) (2015-01-12)
[Full Changelog](https://github.com/inaka/erlang-github/compare/0.1.3...0.1.4)

**Fixed bugs:**

- Typo in type name "messge" instead of "message"  [\#17](https://github.com/inaka/erlang-github/issues/17)
- Fix types in egithub\_webhook [\#20](https://github.com/inaka/erlang-github/pull/20) ([elbrujohalcon](https://github.com/elbrujohalcon))

**Merged pull requests:**

- egithub\_webhook: Provide the whole repo structure, not just the name for the callback [\#19](https://github.com/inaka/erlang-github/pull/19) ([elbrujohalcon](https://github.com/elbrujohalcon))
- \[Closes \#17\] Fix typo. [\#18](https://github.com/inaka/erlang-github/pull/18) ([jfacorro](https://github.com/jfacorro))
- Create a new behaviour: egithub\_webhook [\#16](https://github.com/inaka/erlang-github/pull/16) ([elbrujohalcon](https://github.com/elbrujohalcon))

## [0.1.3](https://github.com/inaka/erlang-github/tree/0.1.3) (2014-11-13)
[Full Changelog](https://github.com/inaka/erlang-github/compare/0.1.2...0.1.3)

**Implemented enhancements:**

- Create a behaviour that allows using other library than jiffy  [\#12](https://github.com/inaka/erlang-github/issues/12)

**Fixed bugs:**

- Wrong order of arguments when checking application:get\_env/2 [\#14](https://github.com/inaka/erlang-github/issues/14)

**Merged pull requests:**

- \[Closes \#14\] Fixed bug. [\#15](https://github.com/inaka/erlang-github/pull/15) ([jfacorro](https://github.com/jfacorro))

## [0.1.2](https://github.com/inaka/erlang-github/tree/0.1.2) (2014-11-13)
[Full Changelog](https://github.com/inaka/erlang-github/compare/0.1.1...0.1.2)

**Implemented enhancements:**

- \[\#12\] egithub\_json behavior [\#13](https://github.com/inaka/erlang-github/pull/13) ([jfacorro](https://github.com/jfacorro))

**Fixed bugs:**

- Wrong credentials tuple being created for basic authentication  [\#6](https://github.com/inaka/erlang-github/issues/6)

## [0.1.1](https://github.com/inaka/erlang-github/tree/0.1.1) (2014-10-16)
[Full Changelog](https://github.com/inaka/erlang-github/compare/0.1.0...0.1.1)

**Fixed bugs:**

- Handle non 404 errors when checking team membership [\#10](https://github.com/inaka/erlang-github/issues/10)
- Wrong api URI for get team membership [\#8](https://github.com/inaka/erlang-github/issues/8)

**Merged pull requests:**

- \[Fixes \#10\] Handle errors that are not 404 [\#11](https://github.com/inaka/erlang-github/pull/11) ([jfacorro](https://github.com/jfacorro))
- \[Fixes \#8\] Corrected uri [\#9](https://github.com/inaka/erlang-github/pull/9) ([jfacorro](https://github.com/jfacorro))

## [0.1.0](https://github.com/inaka/erlang-github/tree/0.1.0) (2014-09-26)
**Closed issues:**

- Basic project structure [\#2](https://github.com/inaka/erlang-github/issues/2)
- Implement GitHub API v3 [\#1](https://github.com/inaka/erlang-github/issues/1)

**Merged pull requests:**

- \[\#6\] Fix basic auth credential. [\#7](https://github.com/inaka/erlang-github/pull/7) ([jfacorro](https://github.com/jfacorro))
- \[Closes \#1\] Github API v3 [\#5](https://github.com/inaka/erlang-github/pull/5) ([jfacorro](https://github.com/jfacorro))
- \[Closes \#2\] Initial project structure. [\#3](https://github.com/inaka/erlang-github/pull/3) ([jfacorro](https://github.com/jfacorro))



\* *This Change Log was automatically generated by [github_changelog_generator](https://github.com/skywinder/Github-Changelog-Generator)*