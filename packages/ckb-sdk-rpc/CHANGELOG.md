# Changelog

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# [0.12.0](https://github.com/nervosnetwork/ckb-sdk-js/compare/v0.11.0...v0.12.0) (2019-05-18)


### Bug Fixes

* **rpc:** fix get live cell rpc ([dffcc55](https://github.com/nervosnetwork/ckb-sdk-js/commit/dffcc55))
* **rpc:** fix the return type of getCellsByLockHash from cellByLockHash to cellIncludingOutPoint ([f648f56](https://github.com/nervosnetwork/ckb-sdk-js/commit/f648f56))


### Features

* **rpc:** add get epoch by number rpc ([d1141dd](https://github.com/nervosnetwork/ckb-sdk-js/commit/d1141dd))
* **rpc:** add get peers rpc ([f67eee6](https://github.com/nervosnetwork/ckb-sdk-js/commit/f67eee6))
* **rpc:** add get tx pool info rpc ([203dcde](https://github.com/nervosnetwork/ckb-sdk-js/commit/203dcde))
* **rpc:** add one new rpc and remove two rpc ([21c4ac4](https://github.com/nervosnetwork/ckb-sdk-js/commit/21c4ac4))
* **rpc:** add rpc of get blockchain info and get peers state ([9f7d20c](https://github.com/nervosnetwork/ckb-sdk-js/commit/9f7d20c))
* **rpc:** add rpc of getCurrentEpoch ([9e631db](https://github.com/nervosnetwork/ckb-sdk-js/commit/9e631db))
* **rpc:** export formatter as helpers in rpc module ([160aa1c](https://github.com/nervosnetwork/ckb-sdk-js/commit/160aa1c))
* **rpc:** generalize outpoint ([2a41797](https://github.com/nervosnetwork/ckb-sdk-js/commit/2a41797))
* **rpc:** update staging in tx pool info to proposed ([a4f4192](https://github.com/nervosnetwork/ckb-sdk-js/commit/a4f4192))
* **types:** rename the proposals_root field in block header to proposals_hash ([b2db527](https://github.com/nervosnetwork/ckb-sdk-js/commit/b2db527))


### BREAKING CHANGES

* **types:** update type of outpoint
* **types:** rename the proposals_root field in block header to proposals_hash





# [0.11.0](https://github.com/nervosnetwork/ckb-sdk-js/compare/v0.10.0...v0.11.0) (2019-05-14)


### Features

* **rpc:** feat(rpc): update rpc interface formatter according to new api ([c0a631](https://github.com/nervosnetwork/ckb-sdk-js/pull/135/commits/c0a631))





# [0.10.0](https://github.com/nervosnetwork/ckb-sdk-js/compare/v0.9.0...v0.10.0) (2019-05-06)


### Features

* **types:** add field of validSince in cell input of a transaction ([54770fc](https://github.com/nervosnetwork/ckb-sdk-js/commit/54770fc))
* **types:** update ckb-types ([e6af3b5](https://github.com/nervosnetwork/ckb-sdk-js/commit/e6af3b5))


### BREAKING CHANGES

* **types:** replace type of u64 with type of string in ckb-types, remove version field from script interface
* **types:** rpc interface updated, add field of validSince in cell input of a transaction





## [0.9.1](https://github.com/nervosnetwork/ckb-sdk-js/compare/v0.9.0...v0.9.1) (2019-04-24)

**Note:** Version bump only for package @nervosnetwork/ckb-sdk-rpc





# [0.9.0](https://github.com/nervosnetwork/ckb-sdk-js/compare/v0.8.0...v0.9.0) (2019-04-22)


### Features

* **rpc:** add segrated witnesses ([bc8339f](https://github.com/nervosnetwork/ckb-sdk-js/commit/bc8339f))
* **types:** update types of script, cell input, cell output ([ee405bb](https://github.com/nervosnetwork/ckb-sdk-js/commit/ee405bb))
* **types:** remove cellbase id from block header, remove cellbase from uncle block ([de9f50d](https://github.com/nervosnetwork/ckb-sdk-js/commit/de9f50d))


### BREAKING CHANGES

* **types:** block header and uncle block in rpc updated
* **types:** script model updated





# [0.8.0](https://github.com/nervosnetwork/ckb-sdk-js/compare/v0.7.0...v0.8.0) (2019-04-08)


# [0.7.0](https://github.com/nervosnetwork/ckb-sdk-js/compare/v0.0.1-alpha.3...v0.7.0) (2019-03-25)

**Note:** Version bump only for package @nervosnetwork/ckb-sdk-rpc
