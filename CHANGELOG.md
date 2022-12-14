# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.3.0-testd]
### Uncategorized
- add publishConfig to package.json

## [0.3.0-testc]
### Changed
- move package to @ethjs-staging namespace

## [0.3.0-testb]
### Changed
- wip: ci: use forked action-npm-publish action

## [0.3.0-testa]
### Changed
- 0.3.0-testa

## [0.3.0-test9]
### Changed
- 0.3.0-test9

## [0.3.0-test8]
### Changed
- update repo url

## [0.3.0-test7]
### Changed
- 0.3.0-test7

## [0.3.0-test6]
### Changed
- fixup package-lock.json
- fixup custom gh action

## [0.3.0-test5]
### Changed
- changelog

## [0.3.0-test4]
### Changed
- 0.3.0-test4

## [0.3.0-test3]
### Changed
- fixup changelog
- wip ci: use action allowing changelog with dashes in version
- devDeps: cross-env@1.0.7->7.0.3

## [0.3.0-test2]
### Changed
- Renamed to `@metamask/ethjs-rpc`
- Fixed and removed broken devDependencies
- Require minimum nodejs v8.17, npm v6
- Repository location changed
## Internal
- CI migrated from Travis to Github Actions
- `npm test-travis` is now `npm test:coverage`
- Removed coveralls
- .nvm rc v8->v12

## [0.2.0]
### Changed
- added promises
  - Fixed major callback / promise issue thanks to Kumavis!! (i.e. unhandled promise rejection swollowing errors)

## [0.1.7]
### Changed
- Added promise support (why did I not do this before..)

## [0.1.6]
### Changed
- fix RPC error handling for geth nodes

## [0.1.5]
### Changed
- package json fix

## [0.1.3]
### Changed
- Handle 405 errors better from the provider

## [0.1.2]
### Changed
- Louder errors

## [0.1.1]
### Changed
- handle errors better
  - Better error handling

## [0.1.0]
### Changed
- ethjs-rpc
  - Basic testing
  - Basic docs
  - License
  - linting
  - basic exports

[Unreleased]: https://github.com/legobeat/ethjs-rpc/compare/v0.3.0-testd...HEAD
[0.3.0-testd]: https://github.com/legobeat/ethjs-rpc/compare/v0.3.0-testc...v0.3.0-testd
[0.3.0-testc]: https://github.com/legobeat/ethjs-rpc/compare/v0.3.0-testb...v0.3.0-testc
[0.3.0-testb]: https://github.com/legobeat/ethjs-rpc/compare/v0.3.0-testa...v0.3.0-testb
[0.3.0-testa]: https://github.com/legobeat/ethjs-rpc/compare/v0.3.0-test9...v0.3.0-testa
[0.3.0-test9]: https://github.com/legobeat/ethjs-rpc/compare/v0.3.0-test8...v0.3.0-test9
[0.3.0-test8]: https://github.com/legobeat/ethjs-rpc/compare/v0.3.0-test7...v0.3.0-test8
[0.3.0-test7]: https://github.com/legobeat/ethjs-rpc/compare/v0.3.0-test6...v0.3.0-test7
[0.3.0-test6]: https://github.com/legobeat/ethjs-rpc/compare/v0.3.0-test5...v0.3.0-test6
[0.3.0-test5]: https://github.com/legobeat/ethjs-rpc/compare/v0.3.0-test4...v0.3.0-test5
[0.3.0-test4]: https://github.com/legobeat/ethjs-rpc/compare/v0.3.0-test3...v0.3.0-test4
[0.3.0-test3]: https://github.com/legobeat/ethjs-rpc/compare/v0.3.0-test2...v0.3.0-test3
[0.3.0-test2]: https://github.com/legobeat/ethjs-rpc/compare/v0.2.0...v0.3.0-test2
[0.2.0]: https://github.com/legobeat/ethjs-rpc/compare/v0.1.7...v0.2.0
[0.1.7]: https://github.com/legobeat/ethjs-rpc/compare/v0.1.6...v0.1.7
[0.1.6]: https://github.com/legobeat/ethjs-rpc/compare/v0.1.5...v0.1.6
[0.1.5]: https://github.com/legobeat/ethjs-rpc/compare/v0.1.3...v0.1.5
[0.1.3]: https://github.com/legobeat/ethjs-rpc/compare/v0.1.2...v0.1.3
[0.1.2]: https://github.com/legobeat/ethjs-rpc/compare/v0.1.1...v0.1.2
[0.1.1]: https://github.com/legobeat/ethjs-rpc/compare/v0.1.0...v0.1.1
[0.1.0]: https://github.com/legobeat/ethjs-rpc/releases/tag/v0.1.0
