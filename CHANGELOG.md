# Changelog

## 0.5.0 (2017-08-15)

* Forward compatibility: react/event-loop 1.0 and 0.5, react/stream 0.7.2 and 1.0, and Événement 3.0
  (#38 and #44 by @WyriHaximus, and #46 by @clue)
* Windows compatibility: Documentate that windows isn't supported in 0.5 unless used from within WSL
  (#41 and #47 by @WyriHaximus)
* Documentation: Termination examples
  (#42 by @clue)
* BC: Throw LogicException in Process instanciating when on Windows or when proc_open is missing (was `RuntimeException`)
  (#49 by @mdrost)

## 0.4.3 (2017-03-14)

* Ease getting started by improving documentation and adding examples
  (#33 and #34 by @clue)

* First class support for PHP 5.3 through PHP 7.1 and HHVM
  (#29 by @clue and #32 by @WyriHaximus)

## 0.4.2 (2017-03-10)

* Feature: Forward compatibility with Stream v0.5
  (#26 by @clue)

* Improve test suite by removing AppVeyor and adding PHPUnit to `require-dev`
  (#27 and #28 by @clue)

## 0.4.1 (2016-08-01)

* Standalone component
* Test against PHP 7 and HHVM, report test coverage, AppVeyor tests
* Wait for stdout and stderr to close before watching for process exit
  (#18 by @mbonneau)

## 0.4.0 (2014-02-02)

* Feature: Added ChildProcess to run async child processes within the event loop (@jmikola)
