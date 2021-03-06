# Change Log
All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased][unreleased]
### Added
- Matplotlib support
- Quite a bit of basic docstrings

### Changed
- Filenames should now be specified to the `generate_pdf`/`generate_tex`
  methods of document. If this is not done the `default_filename` attribute
  will be used.

### Fixed
- Fix a lot of bugs in the `escape_latex` function

## [0.6.1] - 11-01-2015
### Added
- Travis tests

### Fixed
- Bug in VectorName


## [0.6.0] - 07-01-2015
### Added
- Figure class
- Command and Parameter classes
- `with` statement support


## [0.5.0] - 02-06-2014
### Added
- Python 2.7 support


## [0.4.2] - 18-03-2014
### Added
- More table types


## [0.4.1] - 29-01-2014
### Added
- Partial experimental support for multicol/multirow

### Fixed
- Fix package delegation with duplicate packages

[unreleased]: https://github.com/JelteF/PyLaTeX/compare/v0.6.1...HEAD
[v0.6.1]: https://github.com/JelteF/PyLaTeX/compare/v0.6...v0.6.1
[v0.6]: https://github.com/JelteF/PyLaTeX/compare/v0.5...v0.6
[v0.5]: https://github.com/JelteF/PyLaTeX/compare/v0.4.2...v0.5
[v0.4.2]: https://github.com/JelteF/PyLaTeX/compare/v0.4.1...v0.4.2
[v0.4.1]: https://github.com/JelteF/PyLaTeX/compare/68ddef6bc43a5dff42105c3a38068d87d99d049f...v0.4.1
