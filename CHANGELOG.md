# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [6.0.0]
### Added
- Add section to trigger wallet_watchAsset ([#222](git+https://github.com/MetaMask/test-dapp/pull/222))

### Changed
- **BREAKING:** Update minimum Node.js version to v16 ([#225](git+https://github.com/MetaMask/test-dapp/pull/225))

## [5.7.0]
### Added
- Add input field for setting custom decimals on ERC20 deploy ([#219](git+https://github.com/MetaMask/test-dapp/pull/219))

### Changed
- Update ERC20 Token contract with non-hardcoded decimals and Permit support ([#220](git+https://github.com/MetaMask/test-dapp/pull/220))

## [5.6.0]
### Added
- Add Set approval for all and Revoke button to the ERC1155 token section ([#215](https://github.com/MetaMask/test-dapp/pull/215))
- Permit Signature first part ([#217](https://github.com/MetaMask/test-dapp/pull/217))

## [5.5.0]
### Added
- Add ERC1155 token section with Batch Minting and Batch Transfers ([#212](https://github.com/MetaMask/test-dapp/pull/212))

## [5.4.0]
### Added
- Add a Multisig section to test Sending ETH to Multisig Wallets ([#209](https://github.com/MetaMask/test-dapp/pull/209))

## [5.3.0]
### Added
- Add a Sign In With Ethereum (SIWE) section to test signing messages that conform to [EIP-4361 spec](https://eips.ethereum.org/EIPS/eip-4361) ([#164](https://github.com/MetaMask/test-dapp/pull/164))

## [5.2.1]
### Added
- Add button to revoke NFT allowances ([#187](git+https://github.com/MetaMask/test-dapp/pull/187))

## [5.2.0]
### Added
- Add NFT contract interaction buttons ([#181](git+https://github.com/MetaMask/test-dapp/pull/181))
- Allow specifying already existing contract address ([#180](git+https://github.com/MetaMask/test-dapp/pull/180))

## [5.1.1]
### Fixed
- Fix RPC info for local Ganache instance ([#178](git+https://github.com/MetaMask/test-dapp/pull/178))

## [5.1.0]
### Added
- Use local Ganache instance for `wallet_addEthereumChain` instead of XDAI ([#174](git+https://github.com/MetaMask/test-dapp/pull/174))

### Fixed
- Fix event used for accessing provider ([#163](git+https://github.com/MetaMask/test-dapp/pull/163))
- fix: replace networkChanged with chainChanged ([#162](git+https://github.com/MetaMask/test-dapp/pull/162))
- wait for the transaction to be mined ([#138](git+https://github.com/MetaMask/test-dapp/pull/138))

## [5.0.0]
### Added
- Add buttons to send transaction and deploy contract that will fail([#139](git+https://github.com/MetaMask/test-dapp/pull/139))
- add deploy and mint buttons for collectibles flow ([#136](git+https://github.com/MetaMask/test-dapp/pull/136))
- Add warning when using Test Dapp on Mainnet ([#134](git+https://github.com/MetaMask/test-dapp/pull/134))
- Add form to send transaction with parameters([#132](git+https://github.com/MetaMask/test-dapp/pull/132))
- Add button to send EIP1559 transaction ([#117](git+https://github.com/MetaMask/test-dapp/pull/117))
- Add button to suggest switching Ethereum chains([#102](git+https://github.com/MetaMask/test-dapp/pull/102))
- Add button to call watch-asset ([#112](git+https://github.com/MetaMask/test-dapp/pull/112))
- Add button to suggest adding Ethereum chain ([#92](git+https://github.com/MetaMask/test-dapp/pull/92))

### Fixed
- Remove known hacked address from send flow. ([#129](git+https://github.com/MetaMask/test-dapp/pull/129))
- Fix decimal unit error in send token flow ([#131](git+https://github.com/MetaMask/test-dapp/pull/131))
- Fix signTypedData_v3 message ([#133](git+https://github.com/MetaMask/test-dapp/pull/133))
- Fix repository standardization issues ([#118](git+https://github.com/MetaMask/test-dapp/pull/118))
- Fix addEthereumChain button disable logic ([#93](git+https://github.com/MetaMask/test-dapp/pull/93))

[Unreleased]: git+https://github.com/MetaMask/test-dapp/compare/v5.7.0...HEAD
[5.7.0]: git+https://github.com/MetaMask/test-dapp/compare/v5.6.0...v5.7.0
[5.6.0]: git+https://github.com/MetaMask/test-dapp/compare/v5.5.0...v5.6.0
[5.5.0]: git+https://github.com/MetaMask/test-dapp/compare/v5.4.0...v5.5.0
[5.4.0]: git+https://github.com/MetaMask/test-dapp/compare/v5.3.0...v5.4.0
[5.3.0]: git+https://github.com/MetaMask/test-dapp/compare/v5.2.1...v5.3.0
[5.2.1]: git+https://github.com/MetaMask/test-dapp/compare/v5.2.0...v5.2.1
[5.2.0]: git+https://github.com/MetaMask/test-dapp/compare/v5.1.1...v5.2.0
[5.1.1]: git+https://github.com/MetaMask/test-dapp/compare/v5.1.0...v5.1.1
[5.1.0]: git+https://github.com/MetaMask/test-dapp/compare/v5.0.0...v5.1.0
[5.0.0]: git+https://github.com/MetaMask/test-dapp/releases/tag/v5.0.0
