# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added

- Initial commit.

### Fixed

-  An empty .psm1 file is required if the module manifest contain the
   property `RootModule`. If this does not exist it is not possible to
   run the build task (fails with invalid module manifest).

### Fixed
