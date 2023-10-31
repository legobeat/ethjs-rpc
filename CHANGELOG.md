# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.4.0]
### Uncategorized
- npm v5 compat: rename prepublish script to prepare
- chore: fix remaining repo links to point to https://github.com/MetaMask/ethjs-rpc
- npm audit fix; npm dedupe
- devDeps: babel-*@6 -> @babel/*@^7
- devDeps: json-loader@0.5.4->^0.5.7
- devdeps: webpack@2.1.0-beta.15->^3.12.0
- 0.3.0
- ci: specify npm-publish env for publish-release action
- bump nvmrc v10->v12
- ci: use actions allowing changelog with dashes in version
- move package to @metamask namespace
- update repo url
- add publishConfig to package.json
- ci: action-npm-publish@v2->v1.1.0
- devDeps: cross-env@1.0.7->6.0.3
- update changelog

## [0.3.0]
### Changed
- Renamed to `@metamask/ethjs-rpc`
- Fixed and removed broken devDependencies
- Require minimum nodejs v8.17, npm v6
- Repository location changed
- CI migrated from Travis to Github Actions
- `npm test-travis` is now `npm test:coverage`
- Removed coveralls

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

## [0.1.4]
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

[Unreleased]: https://github.com/legobeat/ethjs-rpc/compare/v0.4.0...HEAD
[0.4.0]: https://github.com/legobeat/ethjs-rpc/compare/v0.3.0...v0.4.0
[0.3.0]: https://github.com/legobeat/ethjs-rpc/compare/v0.2.0...v0.3.0
[0.2.0]: https://github.com/legobeat/ethjs-rpc/compare/v0.1.7...v0.2.0
[0.1.7]: https://github.com/legobeat/ethjs-rpc/compare/v0.1.6...v0.1.7
[0.1.6]: https://github.com/legobeat/ethjs-rpc/compare/v0.1.5...v0.1.6
[0.1.5]: https://github.com/legobeat/ethjs-rpc/compare/v0.1.4...v0.1.5
[0.1.4]: https://github.com/legobeat/ethjs-rpc/compare/v0.1.2...v0.1.4
[0.1.2]: https://github.com/legobeat/ethjs-rpc/compare/v0.1.1...v0.1.2
[0.1.1]: https://github.com/legobeat/ethjs-rpc/compare/v0.1.0...v0.1.1
[0.1.0]: https://github.com/legobeat/ethjs-rpc/releases/tag/v0.1.0
