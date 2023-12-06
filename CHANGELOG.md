# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

<!-- next-header -->
## [5.6.0](https://github.com/OpenPoolProject/stratum/compare/v5.5.4...v5.6.0) (2023-12-06)


### Features

* improve display and debug on session_id - add lots of tests ([6095c8a](https://github.com/OpenPoolProject/stratum/commit/6095c8a2e66baa39ac40522ea6452201e00864aa))
* remove all todos in types and add tests where needed ([b74faa3](https://github.com/OpenPoolProject/stratum/commit/b74faa37d761d7a5eed0b76222540e09985ebe3d))
* update axum to 7.1, hyper to 1, and http to 0.5 ([a7d3dd4](https://github.com/OpenPoolProject/stratum/commit/a7d3dd481e799b54cf6bd60e0551991fd987433e))


### Bug Fixes

* add BSD-3-Clause to allowed licenses in deny.toml ([2ad8b94](https://github.com/OpenPoolProject/stratum/commit/2ad8b948a15bf31e3e84f060b0b5adf9fdf567bf))
* cargo fmt ([b5ca172](https://github.com/OpenPoolProject/stratum/commit/b5ca172fca0f6afc8ac748b34acff7a1ebbf8e53))
* cargo fmt run ([394e172](https://github.com/OpenPoolProject/stratum/commit/394e1722365f036c65b1f886fe0aeb90924c4de0))
* change AddrParseError enum to satisfy clippy lint ([d88cc61](https://github.com/OpenPoolProject/stratum/commit/d88cc613756a36fa25a4a2195e9b2ef8b50d6dea))
* comments on future graceful shutdown ([a1bc76d](https://github.com/OpenPoolProject/stratum/commit/a1bc76d4b4578576355370de47375aaac930b700))
* **deps:** update rust crate async-trait to 0.1.67 ([94dbbb8](https://github.com/OpenPoolProject/stratum/commit/94dbbb86a6f8b166a6037eac4047e3d0459be0e3))
* **deps:** update rust crate async-trait to 0.1.68 ([8e0bd5d](https://github.com/OpenPoolProject/stratum/commit/8e0bd5d8c79d55f99684ede3a40cc8b7fff36e19))
* **deps:** update rust crate async-trait to 0.1.74 ([6ac43b9](https://github.com/OpenPoolProject/stratum/commit/6ac43b953b0558c64d9486c7d18892c664219f76))
* **deps:** update rust crate axum to 0.6.12 ([9b0ef34](https://github.com/OpenPoolProject/stratum/commit/9b0ef34b414b5603b9c0dcd0338d5846e526bfb4))
* **deps:** update rust crate axum to 0.6.14 ([0287ca6](https://github.com/OpenPoolProject/stratum/commit/0287ca649409889e13152e3dca9de39830f962cf))
* **deps:** update rust crate axum to 0.6.15 ([3b631ad](https://github.com/OpenPoolProject/stratum/commit/3b631ad8e8800f33cab8b713aea1d8a7bdbfd861))
* **deps:** update rust crate axum to 0.6.16 ([e078e5c](https://github.com/OpenPoolProject/stratum/commit/e078e5c8245d2b1bc6c76abce4a9221758c214e0))
* **deps:** update rust crate axum to 0.6.17 ([00768c5](https://github.com/OpenPoolProject/stratum/commit/00768c5bc1a25dc97dc2493226e35560a4adb646))
* **deps:** update rust crate bytes to 1.5.0 ([45eccf9](https://github.com/OpenPoolProject/stratum/commit/45eccf9a40731595fabec1e1a2713a15968cf551))
* **deps:** update rust crate dashmap to 5.5.3 ([c9b931a](https://github.com/OpenPoolProject/stratum/commit/c9b931aa2053e2e472401f2072a46641f28ea5ad))
* **deps:** update rust crate futures to 0.3.28 ([4bd9c8a](https://github.com/OpenPoolProject/stratum/commit/4bd9c8ae693134d12564a73f8d9e6db248ed1fc4))
* **deps:** update rust crate futures to 0.3.29 ([6ecd12f](https://github.com/OpenPoolProject/stratum/commit/6ecd12f1762eeb383c0720a318bc2c0e8a5affe7))
* **deps:** update rust crate hyper to 0.14.27 ([7218ad4](https://github.com/OpenPoolProject/stratum/commit/7218ad4d14472feb915570ab41c3b10a9f33a0dc))
* **deps:** update rust crate hyper to 1.0.1 ([090f409](https://github.com/OpenPoolProject/stratum/commit/090f409b101e340e369ebf8d175d55949dc0c860))
* **deps:** update rust crate rlimit to 0.10.1 ([d4309cb](https://github.com/OpenPoolProject/stratum/commit/d4309cb5ce99d78d6e28e76304eb887748a1c8cf))
* **deps:** update rust crate serde_json to 1.0.108 ([8429987](https://github.com/OpenPoolProject/stratum/commit/842998749193e283125d3e7ac88b6f876dab5fa5))
* **deps:** update rust crate serde_json to 1.0.95 ([414b59e](https://github.com/OpenPoolProject/stratum/commit/414b59e6cb3372be4b0453aa3fd523236e72f3e0))
* **deps:** update rust crate serde_json to 1.0.96 ([e5cd040](https://github.com/OpenPoolProject/stratum/commit/e5cd0404f7a628e64f9b10167edee4d67a7538ec))
* **deps:** update rust crate thiserror to 1.0.40 ([94e43f1](https://github.com/OpenPoolProject/stratum/commit/94e43f1c8019f5fabd15722535aefd62f5d9f4b8))
* **deps:** update rust crate thiserror to 1.0.50 ([9e4a67e](https://github.com/OpenPoolProject/stratum/commit/9e4a67e3b45db50847d39a5706638908e898308a))
* **deps:** update rust crate tokio to 1.27.0 ([4c2e3da](https://github.com/OpenPoolProject/stratum/commit/4c2e3daec7a7f21f87e59e288b0d9f4a209509b0))
* **deps:** update rust crate tokio to 1.28.0 ([f20f480](https://github.com/OpenPoolProject/stratum/commit/f20f48076ba9808e11ea11682a6a4e12d1b8679e))
* **deps:** update rust crate tokio to 1.34.0 ([f7924a8](https://github.com/OpenPoolProject/stratum/commit/f7924a8c90652b16d3abba7c55bef6f50dc8bf90))
* **deps:** update rust crate tokio-stream to 0.1.13 ([5bfb255](https://github.com/OpenPoolProject/stratum/commit/5bfb25560ccac7bf9dfede4de8efd53ccfe924c8))
* **deps:** update rust crate tokio-stream to 0.1.14 ([05c06ca](https://github.com/OpenPoolProject/stratum/commit/05c06ca9132a3f0fbf8d2781a0decbbe07b7ab6f))
* **deps:** update rust crate tracing to 0.1.38 ([51adc4f](https://github.com/OpenPoolProject/stratum/commit/51adc4fadddc9f52dd649bc7e6e2207399a8c71a))
* **deps:** update rust crate tracing to 0.1.40 ([f7bd63c](https://github.com/OpenPoolProject/stratum/commit/f7bd63c4b37823cb8ea12ce45f4c55aa0d0b8a4c))
* **deps:** update rust crate uuid to 1.3.1 ([2e06bb7](https://github.com/OpenPoolProject/stratum/commit/2e06bb72d13f3f5016ada728ac3399bafc99fb5c))
* **deps:** update rust crate uuid to 1.6.1 ([754e1d1](https://github.com/OpenPoolProject/stratum/commit/754e1d10390f7368b25dd2794e6d01bfe49e9f81))
* enable coverage(off) attribute ([e1b34be](https://github.com/OpenPoolProject/stratum/commit/e1b34be19f419629ceed43d4af4f3dacf9d44821))
* explicitly add resolver = 2 ([6471b23](https://github.com/OpenPoolProject/stratum/commit/6471b233e0c58df078628913d53356fc6392848c))
* final coverage fix, only enable feature on nightly ([e7741ad](https://github.com/OpenPoolProject/stratum/commit/e7741ad5d5e2bdbd74251115bf09e4b846883abc))
* remove error from addrparse error ([e3a09c0](https://github.com/OpenPoolProject/stratum/commit/e3a09c0a73c09e3db83600309773b5602fdae535))
* round 3 of attempting to fix coverage issues ([557cafb](https://github.com/OpenPoolProject/stratum/commit/557cafb3c59f2e2e978f4ed5d126eff7ba8cfadd))
* switch no_coverage to coverage(off) ([5f4f710](https://github.com/OpenPoolProject/stratum/commit/5f4f7108b913ce8d22d177acb3b83fa61ae158df))
* update coverage_helper to 0.2 ([6f13933](https://github.com/OpenPoolProject/stratum/commit/6f13933d62fa4fb06e4aace15f02f9f422ccabee))
* update MSRV to 1.67.1 (Mainly focused on the feature int_log) ([3bd77a8](https://github.com/OpenPoolProject/stratum/commit/3bd77a89449757176fb302327f0912d54bd2f76e))
* update to the latest clippy lints ([cd68c65](https://github.com/OpenPoolProject/stratum/commit/cd68c65aa1aea1b287962cc60b5ac0497dd113bc))
* use coverage_helper to solve test coverage issue ([c5e0975](https://github.com/OpenPoolProject/stratum/commit/c5e0975dc7b2f34678623015c3b6892bf241e7f7))

## [Unreleased] - ReleaseDate

### Added
- Basic logging in Stratum Server.
- Workflow file for PR Review.
- Initial Support for SetDiffculty and Subscribe.
- Multiple Improvements to Client work handling.

## [0.1.9] - 2020-01-18

### Added
- Basic support for Notify, Submit and Authenticate packets.


<!-- next-url -->
[Unreleased]: https://github.com/UrkelLabs/stratum/compare/v0.1.9...HEAD
[0.1.9]: https://github.com/UrkelLabs/stratum/compare/master...v0.1.9
