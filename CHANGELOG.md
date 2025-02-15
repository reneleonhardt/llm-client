# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.7.0] - 2024-04-01

### Added

- Vision support for OpenAI, Azure and Anthropic(Claude)

## [0.6.2] - 2024-03-08

### Added

- Support for You Pro modes

## [0.6.1] - 2024-03-06

### Fixed

- Anthropic Claude completion error handling

## [0.6.0] - 2024-03-06

### Added

- Anthropic Claude client

### Fixed

- `IndexOutOfBoundsException` for Azure completions

## [0.5.0] - 2024-02-23

### Added

- Access to EventSource on message callbacks (breaking change)

## [0.4.3] - 2024-02-09

### Changed

- Ollama stop parameter type

## [0.4.2] - 2024-02-06

### Changed

- Restore OpenAI legacy models to ensure backward compatibility

## [0.4.1] - 2024-02-06

### Changed

- GPT-3.5 Turbo model description

## [0.4.0] - 2024-02-06

### Added

- Ollama API client
- Changelog

### Changed

- Upgrade OpenAI chat models: **gpt-4-0125-preview**, **gpt-3.5-turbo-0125**

[0.7.0]: https://github.com/carlrobertoh/llm-client/compare/0179d0c1e1d4281fe6d93bf84a23ca6714931500...HEAD
[0.6.2]: https://github.com/carlrobertoh/llm-client/compare/57039edbe25796bca08bd6cce2a92a02160607e9...0179d0c1e1d4281fe6d93bf84a23ca6714931500
[0.6.1]: https://github.com/carlrobertoh/llm-client/compare/f7791cbf92af7fe8b8b6a0226cdc3d3f8bf56f14...57039edbe25796bca08bd6cce2a92a02160607e9
[0.6.0]: https://github.com/carlrobertoh/llm-client/compare/3831d02c7ac0bd932dfad844605f3bd41d709d2b...f7791cbf92af7fe8b8b6a0226cdc3d3f8bf56f14
[0.5.0]: https://github.com/carlrobertoh/llm-client/compare/50f636ef1796286ca259ad9d3fc0000ae180687e...3831d02c7ac0bd932dfad844605f3bd41d709d2b
[0.4.3]: https://github.com/carlrobertoh/llm-client/compare/ae03125494754cf220eb9e3908d3be61bb2f9fe9..50f636ef1796286ca259ad9d3fc0000ae180687e
[0.4.2]: https://github.com/carlrobertoh/llm-client/compare/eedae7c6e0eca726620e3f1abb4610eda53cc502..ae03125494754cf220eb9e3908d3be61bb2f9fe9
[0.4.1]: https://github.com/carlrobertoh/llm-client/compare/0c6e33c925ddd01a65ca4692111d12eb0047dfbb..eedae7c6e0eca726620e3f1abb4610eda53cc502
[0.4.0]: https://github.com/carlrobertoh/llm-client/compare/c9d73c08b61a3ee368a163a34f64fd401ee4ce94..0c6e33c925ddd01a65ca4692111d12eb0047dfbb