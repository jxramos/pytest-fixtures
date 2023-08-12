# Change Log

## [0.3.1]

* Fixed issue with duplicate args sent to pytest, thanks [jxramos](https://github.com/jxramos)

## [0.3.0]

* Set experimental flag for multi-root workspaces to be on by default

## [0.2.9]

* Added experimental flag to support better fixture detection in multi-root workspaces.

## [0.2.8]

* Fixed an issue introduced in 0.2.7

## [0.2.7]

* Added a new setting to add additional decorators to recognize when scanning for fixtures

## [0.2.6]

* Added typing suggestions for fixtures, thanks [thu2004](https://github.com/thu2004)
* Fixed issue where longer test functions were not being recognized

## [0.2.5]

* Added configuration for extra arguments to pytest --fixtures, thanks [thu2004](https://github.com/thu2004)

## [0.2.4]

* Fixed recognition of files ending in `_test`, thanks [sbeal](https://github.com/sbeal)

## [0.2.3]

* New: added new setting to disable refreshing fixtures on file change, and instead caching when requesting suggestions.
* New: cache fixtures for the workspace

Thanks [ItamarShDev](https://github.com/ItamarShDev) for both.

## [0.2.2]

* Fixed performance issue on saving python test files, fixtures no longer are scanned for on save
* Registered command to scan for fixtures

## [0.2.1]

* Support async methods, thanks [DATek](https://github.com/DAtek)

## [0.2.0]

* Use a new method to detect if the cursor is within a compatible function.

## [0.1.19]

* Fix regression from using deprecated `pythonPath`

## [0.1.18]

* Use workspace folder as rootDir if available

## [0.1.17]

* Trim rootdir to avoid invalid paths
* Use absolute paths when recognized

## [0.1.16]

* Use the rootdir from the pytest output to determine the fixture location if available

## [0.1.15]

* Additional regex improvements
* Added exception handling in case definition support fails

## [0.1.14]

* Fix bad regex

## [0.1.13]

* Fix regressions with module scope and docstrings

## [0.1.12]

* Fixed bug with parsing caused by pytest --color settings, thanks https://github.com/andriykohut

## [0.1.11]

### New - Go To Definition Support - Thanks https://github.com/DavideCanton

* Go to definition support is now enabled for fixtures. Press F12 to go to the definiton of the currently hovered fixture parameter.

## [0.1.10]

* Add a better demo

## [0.1.9]

* Provide support for fixtures using fixtures

## [0.1.8]

* Updated README

## [0.1.7]

* Add check for custom pytest path

## [0.1.6]

* Bumping version to test workflow

## [0.1.5]

* Fix newline issue with parameters on windows

## [0.1.4]

* Add icon
* Support more characters in fixture name

## [0.1.3]

* Check on file save rather than change to avoid resource hogging.

## [0.1.0]

* Initial release
