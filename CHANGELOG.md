# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.2.1] - 2026-03-18

### Fixed

- Updated Python version in GitHub Action workflow (per pip error)

## [0.2.0] - 2026-03-18

### Fixed

- No longer trims unannotated (i.e., domain-less) genes from gene clusters if they surpass the specified probability threshold

### Changed

- Relaxed default secretion system probability threshold to 0.4 based on LOTO + test set results

## [0.1.1] - 2025-08-23

### Fixed

- Fixed MD5 checksum for HMM

## [0.1.0] - 2025-08-23

### Added

- Initial release.

