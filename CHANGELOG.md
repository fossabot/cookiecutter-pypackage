# Changelog

All notable changes to this project will be documented in this file.

This project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html). See [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) for commit guidelines.

<!--next-version-placeholder-->

## v0.3.2 (2021-09-09)
### Fix
* **main:** Remove invalid `type-check` testenv from `tox.ini` ([`591e270`](https://github.com/billsioros/cookiecutter-pypackage/commit/591e27041393c123440de756d5140dc363943de2))
* **main:** Test commands via `poetry` on test suite ([`92cc32b`](https://github.com/billsioros/cookiecutter-pypackage/commit/92cc32ba961523409d16836b0162def299f5abda))
* **main:** Assert `result.exception` is None before proceeding ([`f3a103e`](https://github.com/billsioros/cookiecutter-pypackage/commit/f3a103eb676dabf0aa5b4ae79bbd9e9ec1537aa2))
* **main:** `PosixPath` attribute errors ([`e9a1458`](https://github.com/billsioros/cookiecutter-pypackage/commit/e9a145889217327c83176391b6b6e844e3f39166))
* **template:** Generate license locally ([`6b1de5b`](https://github.com/billsioros/cookiecutter-pypackage/commit/6b1de5b92432118f19f32b8791c741b3f9527444))
* **main:** Invalid `pathlib.Path` usage ([`d1df22b`](https://github.com/billsioros/cookiecutter-pypackage/commit/d1df22bc04ca9be18d477d3421d39262fe4f496c))

**[See all commits in this version](https://github.com/billsioros/cookiecutter-pypackage/compare/v0.3.1...v0.3.2)**

## v0.3.1 (2021-09-07)
### Fix
* Get rid of `DeprecationWarning` error(s) ([`f231ce4`](https://github.com/billsioros/cookiecutter-pypackage/commit/f231ce4b51fd0d722c356fc8dbde89185c403fe7))
* Generate license regardless of `skip_setup` ([`b49fa86`](https://github.com/billsioros/cookiecutter-pypackage/commit/b49fa865c59441b1c072dc0d3eee8c1a5689bfaf))

### Documentation
* **main:** Remove `all-contributors` section ([`0a09992`](https://github.com/billsioros/cookiecutter-pypackage/commit/0a099923bf4e40d1f286102840d46350c97ff394))

**[See all commits in this version](https://github.com/billsioros/cookiecutter-pypackage/compare/v0.3.0...v0.3.1)**

## v0.3.0 (2021-09-07)
### Feature
* **main:** Include tests ([`47657e0`](https://github.com/billsioros/cookiecutter-pypackage/commit/47657e0f7b8d5536438e567d21009ec24350b3b8))

### Documentation
* **template:** Uppercase `license` in URLs ([`76a38eb`](https://github.com/billsioros/cookiecutter-pypackage/commit/76a38eb28c8541399c5da9e6e2bac81f483ce367))
* **main:** Remove `codecov` badge ([`261f944`](https://github.com/billsioros/cookiecutter-pypackage/commit/261f944941e1f745f787991c9e514c4d65c4ccf9))
* **template:** Update `buymeacoffee` badge href ([`e1645a3`](https://github.com/billsioros/cookiecutter-pypackage/commit/e1645a33ec08ae3cd16b6948a02a5e78fea29606))

**[See all commits in this version](https://github.com/billsioros/cookiecutter-pypackage/compare/v0.2.1...v0.3.0)**

## v0.2.1 (2021-09-06)
### Fix
* Set `skip_setup` to `True` when creating a PR ([`b2c028f`](https://github.com/billsioros/cookiecutter-pypackage/commit/b2c028fc180aed70aafda2a7fde6a10c63b33ad5))

**[See all commits in this version](https://github.com/billsioros/cookiecutter-pypackage/compare/v0.2.0...v0.2.1)**

## v0.2.0 (2021-09-06)
### Feature
* **main:** Add `validate_project_name` validator ([`eb535a9`](https://github.com/billsioros/cookiecutter-pypackage/commit/eb535a99bd8aba2d8f13391436188318fb61cf1e))
* Add `generate_license` task ([`365e0e0`](https://github.com/billsioros/cookiecutter-pypackage/commit/365e0e05448424d1ff438d2eb6c156bbe2b2955a))
* **main:** Add cookiecutter pre/post gen `hooks` ([`c1aeac8`](https://github.com/billsioros/cookiecutter-pypackage/commit/c1aeac84eca4098bab0a083e651a4a3bf893474a))

### Fix
* **main:** `skip_setup` when creating a pull request ([`108ef3f`](https://github.com/billsioros/cookiecutter-pypackage/commit/108ef3f1d296f389c03ea57bb90edecdc8c169bc))

### Documentation
* **template:** Add `renovate` and `buymeacoffee` badges ([`de2c7cd`](https://github.com/billsioros/cookiecutter-pypackage/commit/de2c7cd6d3d131b8cd67c382867f4da040730c8f))
* **template:** Add custom license url ([`1f7deba`](https://github.com/billsioros/cookiecutter-pypackage/commit/1f7deba0d6003cd520d24925d13b32f09cb2196c))
* **template:** Add basic module documentation ([`bd61f81`](https://github.com/billsioros/cookiecutter-pypackage/commit/bd61f81530ba02844c5ba825a508bd85b1d6cf04))

**[See all commits in this version](https://github.com/billsioros/cookiecutter-pypackage/compare/v0.1.3...v0.2.0)**

## v0.1.3 (2021-09-01)
### Fix
* **template:** `black` & `isort` failing due to missing newline ([`86981f1`](https://github.com/billsioros/cookiecutter-pypackage/commit/86981f15e74395d505b853fb334e94efd54ab678))

**[See all commits in this version](https://github.com/billsioros/cookiecutter-pypackage/compare/v0.1.2...v0.1.3)**

## v0.1.2 (2021-08-28)
### Fix
* Remove `.git` from `github_repository` input variable ([`41cc778`](https://github.com/billsioros/cookiecutter-pypackage/commit/41cc778c1325637692d7b65fbe3fc2122d5c5535))

**[See all commits in this version](https://github.com/billsioros/cookiecutter-pypackage/compare/v0.1.1...v0.1.2)**

## v0.1.1 (2021-08-28)
### Fix
* **main:** Unable to process command `set-output` ([`101e234`](https://github.com/billsioros/cookiecutter-pypackage/commit/101e234d2003ca46e436ad504ee14707546bfa76))

**[See all commits in this version](https://github.com/billsioros/cookiecutter-pypackage/compare/v0.1.0...v0.1.1)**

## v0.1.0 (2021-08-27)
### Feature
* Add the `github_repository` input variable ([`dbf23f4`](https://github.com/billsioros/cookiecutter-pypackage/commit/dbf23f4e1a271f09ca0f895c390407aee52ff9e2))

**[See all commits in this version](https://github.com/billsioros/cookiecutter-pypackage/compare/v0.0.10...v0.1.0)**

## v0.0.10 (2021-08-27)
### Fix
* **template:** `mypy does not apply to this repository` ([`f8623e6`](https://github.com/billsioros/cookiecutter-pypackage/commit/f8623e6a2acb27a6e8205025ef24f173b054d52f))

**[See all commits in this version](https://github.com/billsioros/cookiecutter-pypackage/compare/v0.0.9...v0.0.10)**

## v0.0.9 (2021-08-27)
### Fix
* **main:** Create empty `dist` folder on ci ([`48ca83a`](https://github.com/billsioros/cookiecutter-pypackage/commit/48ca83af46a5ab3fa176121dbf8b07b89ce846af))

**[See all commits in this version](https://github.com/billsioros/cookiecutter-pypackage/compare/v0.0.8...v0.0.9)**

## v0.0.8 (2021-08-27)
### Fix
* **template:** `mypy does not apply to this repository` ([`08aca7d`](https://github.com/billsioros/cookiecutter-pypackage/commit/08aca7d612f2bed89cc387bbc3e491902c7256d3))

**[See all commits in this version](https://github.com/billsioros/cookiecutter-pypackage/compare/v0.0.7...v0.0.8)**

## v0.0.7 (2021-08-27)
### Fix
* **template:** `flakehell` & `mypy` errors ([`84bda24`](https://github.com/billsioros/cookiecutter-pypackage/commit/84bda247d36bc509205d6d02aee0b9a0d16ff836))

**[See all commits in this version](https://github.com/billsioros/cookiecutter-pypackage/compare/v0.0.6...v0.0.7)**

## v0.0.6 (2021-08-27)
### Fix
* **global:** `mypy` and `flakehell` invocation errors ([`fbdc7ae`](https://github.com/billsioros/cookiecutter-pypackage/commit/fbdc7aec0eb5283c443434da069513da1b403c04))

**[See all commits in this version](https://github.com/billsioros/cookiecutter-pypackage/compare/v0.0.5...v0.0.6)**

## v0.0.5 (2021-08-27)
### Fix
* **template:** Correct coverage path ([`ab58ce5`](https://github.com/billsioros/cookiecutter-pypackage/commit/ab58ce5b28542bfe63284547df15db0c03a48c8e))

**[See all commits in this version](https://github.com/billsioros/cookiecutter-pypackage/compare/v0.0.4...v0.0.5)**

## v0.0.4 (2021-08-27)
### Fix
* **template:** Utilize `package_name` variable ([`2ce52cf`](https://github.com/billsioros/cookiecutter-pypackage/commit/2ce52cf6ae7774dbf2c1519be7bc433b32555eef))

**[See all commits in this version](https://github.com/billsioros/cookiecutter-pypackage/compare/v0.0.3...v0.0.4)**

## v0.0.3 (2021-08-26)
### Fix
* **template:** Follow the `src` standard layout ([`8f7927b`](https://github.com/billsioros/cookiecutter-pypackage/commit/8f7927bc7cd24e605f0930d36719e4fef26affb9))

**[See all commits in this version](https://github.com/billsioros/cookiecutter-pypackage/compare/v0.0.2...v0.0.3)**

## v0.0.2 (2021-08-24)
### Fix
* **main:** `skip_install` by default ([`44e1e5d`](https://github.com/billsioros/cookiecutter-pypackage/commit/44e1e5d12e261aae4d4dd6720eba678b5ce4479a))

### Documentation
* **template:** Move `Credits` to the end ([`c4ea9d5`](https://github.com/billsioros/cookiecutter-pypackage/commit/c4ea9d58c6ad6e8f47c295bca45bc8bbe6156770))
* **template:** Change badge style to `flat` ([`476977a`](https://github.com/billsioros/cookiecutter-pypackage/commit/476977a668b558715d5951cd39c8e46be2e84fc5))
* **template:** Change title ([`765b262`](https://github.com/billsioros/cookiecutter-pypackage/commit/765b262dcfb99bbabad4ae7d84dc1d35520fe5ca))
* **main:** Change title ([`d421ee3`](https://github.com/billsioros/cookiecutter-pypackage/commit/d421ee38d1274e1f30717ebbcd0c248a5e458816))
* **template:** Change `Gitpod` badge ([`6902d68`](https://github.com/billsioros/cookiecutter-pypackage/commit/6902d6818c3e478f78636146483c86866f611527))
* **main:** Center align title ([`f313476`](https://github.com/billsioros/cookiecutter-pypackage/commit/f313476af4e8ca20ea8c365785c111ca717762ab))

**[See all commits in this version](https://github.com/billsioros/cookiecutter-pypackage/compare/v0.0.1...v0.0.2)**

## v0.0.1 (2021-08-20)
### Fix
* **main:** Docs not rendering correctly ([`997a87d`](https://github.com/billsioros/cookiecutter-pypackage/commit/997a87da42b689cb77a2657d7bf283aaf933462d))
* **cookiecutter:** Docs not rendering correctly ([`fbf5d34`](https://github.com/billsioros/cookiecutter-pypackage/commit/fbf5d34ee491a0b8d42a491269ad0f88cc7eec4b))
* Correct context errors ([`4118ac5`](https://github.com/billsioros/cookiecutter-pypackage/commit/4118ac56e8b9fa2a1851d586e536d9a3b81d6a47))

### Documentation
* **template:** Keep `LICENSE` date up-to-date ([`12a54dc`](https://github.com/billsioros/cookiecutter-pypackage/commit/12a54dc2344bd83197e05a89d406d530c96562af))
* **template:** Enhance sub-`README`s ([`4d38605`](https://github.com/billsioros/cookiecutter-pypackage/commit/4d38605cceade715f8a5d5861df54562c8f08d53))
* **template:** Remove `SPOTIFY` section ([`3479c9b`](https://github.com/billsioros/cookiecutter-pypackage/commit/3479c9b01e15287416634ce2173b9fd1f75fdbdf))
* **main:** Change `mkdocs.site_description` ([`f70f7bc`](https://github.com/billsioros/cookiecutter-pypackage/commit/f70f7bc61c1781bd41823c05d97d0af6fe05f7c3))
* **main:** Remove `SPOTIFY` sections ([`148bd71`](https://github.com/billsioros/cookiecutter-pypackage/commit/148bd71efbdc9fc9ef6e2aa2d5196a4b9db54f4c))
* **main:** Correct github discussions url ([`a499e1e`](https://github.com/billsioros/cookiecutter-pypackage/commit/a499e1ec2a0ea1768714937729e82aeb78b39c65))
* Add `Quickstart` section ([`1d5890a`](https://github.com/billsioros/cookiecutter-pypackage/commit/1d5890a416d4753cf2b0d851df1cb0ff0c9d9d69))
* Add credits ([`9a1d718`](https://github.com/billsioros/cookiecutter-pypackage/commit/9a1d718b8bc423aa4ba531fa6e9d0318086070a2))

**[See all commits in this version](https://github.com/billsioros/cookiecutter-pypackage/compare/v0.0.0...v0.0.1)**
