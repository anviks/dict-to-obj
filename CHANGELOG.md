# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).


## [Unreleased]

### Added
- Initial release with the `dict_to_object` function, enabling conversion of dictionaries to objects with type hints.
- Type safety checks for nested collections and custom class attributes.
- Support for handling and validating `Literal` types.
- Error handling for mismatched types, unsupported types (e.g., `Union`, `Optional`), and invalid literal values.
