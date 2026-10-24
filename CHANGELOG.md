# Changelog

## [0.3.0](https://github.com/hasansezertasan/copier-scoop-bucket/compare/v0.2.1...v0.3.0) (2026-10-24)


### 🚀 Features

* add a back reference to the template in the generated README ([#64](https://github.com/hasansezertasan/copier-scoop-bucket/issues/64)) ([6eda7a6](https://github.com/hasansezertasan/copier-scoop-bucket/commit/6eda7a69c98718d4e2e987f2228eb2829383d12f))
* leave the cobo-managed gitignore and lockfile to the generated repository ([#67](https://github.com/hasansezertasan/copier-scoop-bucket/issues/67)) ([35ffc84](https://github.com/hasansezertasan/copier-scoop-bucket/commit/35ffc84766bc990ccc83c130adf5f334d78f00b9))


### 📝 Documentation

* put the template back reference under a Credits heading ([#66](https://github.com/hasansezertasan/copier-scoop-bucket/issues/66)) ([8a2c3ef](https://github.com/hasansezertasan/copier-scoop-bucket/commit/8a2c3efc319027226c44253a2395105ea536158b))
* tell adopters to remove the lockfile with the ignore file ([#68](https://github.com/hasansezertasan/copier-scoop-bucket/issues/68)) ([13714fb](https://github.com/hasansezertasan/copier-scoop-bucket/commit/13714fbd538bf3bb5d0400c777e324eceb124965))

## [0.2.1](https://github.com/hasansezertasan/copier-scoop-bucket/compare/v0.2.0...v0.2.1) (2026-10-23)


### 🐛 Bug Fixes

* state the Python 3.11 floor of the generated pyupgrade hook ([#62](https://github.com/hasansezertasan/copier-scoop-bucket/issues/62)) ([a885747](https://github.com/hasansezertasan/copier-scoop-bucket/commit/a885747fd28e66fff5c8e79c585b14d41c1fce72))

## [0.2.0](https://github.com/hasansezertasan/copier-scoop-bucket/compare/v0.1.3...v0.2.0) (2026-10-20)


### 🚀 Features

* **update_manifests:** honour checkver.regex and strip an uppercase V from GitHub tags ([#57](https://github.com/hasansezertasan/copier-scoop-bucket/issues/57)) ([f4958ea](https://github.com/hasansezertasan/copier-scoop-bucket/commit/f4958ea1d49d17a0b726cfe073d34fe26f33c1e1)), closes [#56](https://github.com/hasansezertasan/copier-scoop-bucket/issues/56)

## [0.1.3](https://github.com/hasansezertasan/copier-scoop-bucket/compare/v0.1.2...v0.1.3) (2026-10-19)


### 📝 Documentation

* document adopting the template in an existing bucket ([#54](https://github.com/hasansezertasan/copier-scoop-bucket/issues/54)) ([5163ec6](https://github.com/hasansezertasan/copier-scoop-bucket/commit/5163ec6956329eceabeae816aae943b60c5c52e3))

## [0.1.2](https://github.com/hasansezertasan/copier-scoop-bucket/compare/v0.1.1...v0.1.2) (2026-10-18)


### 🐛 Bug Fixes

* record a full git URL as _src_path so Renovate can track template updates ([#49](https://github.com/hasansezertasan/copier-scoop-bucket/issues/49)) ([345e693](https://github.com/hasansezertasan/copier-scoop-bucket/commit/345e69324b259b2a79ca3b3a3c07d171ac921db5))

## [0.1.1](https://github.com/hasansezertasan/copier-scoop-bucket/compare/v0.1.0...v0.1.1) (2026-10-18)


### 🐛 Bug Fixes

* disable blank issues ([#40](https://github.com/hasansezertasan/copier-scoop-bucket/issues/40)) ([646ca8f](https://github.com/hasansezertasan/copier-scoop-bucket/commit/646ca8fbca34ee6e2b454e35c2baeb470bae6952))


### 📝 Documentation

* sync Cobo pin and ADR drift from homebrew-tap comparison ([#46](https://github.com/hasansezertasan/copier-scoop-bucket/issues/46)) ([c3d9dbb](https://github.com/hasansezertasan/copier-scoop-bucket/commit/c3d9dbb4115e43fc39d96bc77cf90fbccaa98d3d))
* sync homebrew-tap follow-up drift ([#45](https://github.com/hasansezertasan/copier-scoop-bucket/issues/45)) ([030d11d](https://github.com/hasansezertasan/copier-scoop-bucket/commit/030d11de5dd390b74337f29ebbc99dfe095e375d))
* sync remaining drift from homebrew-tap comparison ([#43](https://github.com/hasansezertasan/copier-scoop-bucket/issues/43)) ([96aac31](https://github.com/hasansezertasan/copier-scoop-bucket/commit/96aac312f134ee7b46450bdf0c0aa010ad418e58))
* sync template with homebrew-tap comparison ([#42](https://github.com/hasansezertasan/copier-scoop-bucket/issues/42)) ([c5fc3a3](https://github.com/hasansezertasan/copier-scoop-bucket/commit/c5fc3a35fdae623b0979ad17e324dcb6d3ccfa11))

## 0.1.0 (2026-10-15)


### ⚠ BREAKING CHANGES

* move the manifest scaffolder into scoop-bucket-skills ([#28](https://github.com/hasansezertasan/copier-scoop-bucket/issues/28))
* convert to a Copier template and move agent skills out ([#27](https://github.com/hasansezertasan/copier-scoop-bucket/issues/27))

### 🚀 Features

* convert to a Copier template and move agent skills out ([#27](https://github.com/hasansezertasan/copier-scoop-bucket/issues/27)) ([638b51a](https://github.com/hasansezertasan/copier-scoop-bucket/commit/638b51ada84c0f1fd6e7d24e3082b02830ffe544))
* move the manifest scaffolder into scoop-bucket-skills ([#28](https://github.com/hasansezertasan/copier-scoop-bucket/issues/28)) ([7a069ee](https://github.com/hasansezertasan/copier-scoop-bucket/commit/7a069eeffd59bd62896d334da100b49e97855fd8))


### 📝 Documentation

* keep default workflow permissions read-only ([#30](https://github.com/hasansezertasan/copier-scoop-bucket/issues/30)) ([fcc017c](https://github.com/hasansezertasan/copier-scoop-bucket/commit/fcc017cd5f82b2f6e1aa91b871e1875956cbead0))
* shorten the agent prompt to point at the installation page ([#35](https://github.com/hasansezertasan/copier-scoop-bucket/issues/35)) ([fa2c3ec](https://github.com/hasansezertasan/copier-scoop-bucket/commit/fa2c3eca5c416aae3b41fe1263a1378271d48148))
* shorten the scaffolder section to a pointer ([#32](https://github.com/hasansezertasan/copier-scoop-bucket/issues/32)) ([ea5a1dd](https://github.com/hasansezertasan/copier-scoop-bucket/commit/ea5a1ddcd3382d2e2137a917f1ecb4b6573fac2f))
* split the README into agent and human setup ([#34](https://github.com/hasansezertasan/copier-scoop-bucket/issues/34)) ([651cd65](https://github.com/hasansezertasan/copier-scoop-bucket/commit/651cd6532e39c9cf5406f5b836f7e9160c90764e))


### 👷 CI

* version the template with release-please ([#31](https://github.com/hasansezertasan/copier-scoop-bucket/issues/31)) ([e396ae4](https://github.com/hasansezertasan/copier-scoop-bucket/commit/e396ae498b325abf9b9dc2edc157d157d1307dd4))
