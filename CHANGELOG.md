# Change Log

All notable changes to this project will be documented in this file.
Format of this file follows [these](http://keepachangelog.com/) guidelines.
This project adheres to [Semantic Versioning](http://semver.org/).

## [%RELEASE_VERSION%] - [%RELEASE_DATE%]

### Added

* Nothing

### Changed

* Nothing

### Removed

* Nothing

## [1.0.2] - [2020-02-22]

### Added

* Nothing

### Changed

* mock 3.0.5 -> 4.0.1
* dev-env 0.6.5 -> 0.6.7
* centralized specification of postgres version # in ```clair_cicd/__init.py```
* postgres 9.5.2 -> 12.1

### Removed

* Nothing

## [1.0.1] - [2020-02-02]

### Added

* add markdown lint in CI pipeline

### Changed

* dev-env v0.6.3 -> v0.6.5

### Removed

* Nothing

## [1.0.0] - [2020-01-16]

### Added

* Nothing

### Changed

* Nothing

### Removed

* Nothing

## [0.5.0] - [2019-12-29]

### Added

* [Circle CI](https://circleci.com/) builds docker images for master branch
  every Monday, Wednesday and Friday at ~03:00 UTC

### Changed

* clair v2.0.6 -> v2.1.2
* flake8 3.7.5 -> 3.7.6
* jsonschema 2.6.0 -> 3.0.1
* dev-env 0.5.14 -> 0.6.3
* [Travis CI](https://travis-ci.org/) -> [Circle CI](https://circleci.com/)

### Removed

* removed ```kill-and-remove-all-docker-containers.sh``` since that command is now available from ```dev-env```

## [0.4.0] - [2018-09-29]

### Added

* Nothing

### Changed

* pep8 -> pycodestyle
* clair v2.0.1 -> v2.0.6

### Removed

* Nothing

## [0.3.0] - [2017-09-22]

### Added

* Nothing

### Changed

* Clair 1.2.6 -> 2.0.1

### Removed

* Nothing

## [0.2.0] - [2017-09-19]

### Added

* ...

### Changed

* Now using Clair 1.2.6
* added ```-np``` (no docker image pull) command line option to ```assess-image-risk.sh```

### Removed

* ...

## [0.1.0] - [2015-05-14]

* initial release
