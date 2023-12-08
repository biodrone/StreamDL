### [3.1.19](https://github.com/dangeroustech/StreamDL/compare/v3.1.18...v3.1.19) (2023-12-08)


### 🐛 Bug Fixes

* Dockerfile.client to reduce vulnerabilities ([8c22881](https://github.com/dangeroustech/StreamDL/commit/8c228817d38980eaea46d050e69e3bbc11c649cf))

### [3.1.18](https://github.com/dangeroustech/StreamDL/compare/v3.1.17...v3.1.18) (2023-10-26)


### ✍ Chore

* **deps:** bump google.golang.org/grpc from 1.53.0 to 1.56.3 ([d4f6d68](https://github.com/dangeroustech/StreamDL/commit/d4f6d68035235fbc25d4c322691155abe93b47b2))

### [3.1.17](https://github.com/dangeroustech/StreamDL/compare/v3.1.16...v3.1.17) (2023-10-24)

### [3.1.16](https://github.com/dangeroustech/StreamDL/compare/v3.1.15...v3.1.16) (2023-10-24)


### ✍ Chore

* **deps:** bump urllib3 from 2.0.6 to 2.0.7 ([2b96a25](https://github.com/dangeroustech/StreamDL/commit/2b96a254fad16e91961be25b0a663f3bafda8388))

### [3.1.15](https://github.com/dangeroustech/StreamDL/compare/v3.1.14...v3.1.15) (2023-10-17)

### [3.1.14](https://github.com/dangeroustech/StreamDL/compare/v3.1.13...v3.1.14) (2023-10-17)


### ✍ Chore

* update actions deps ([84a7481](https://github.com/dangeroustech/StreamDL/commit/84a748131b86a23ae724b4f51c9b65c5053d5fd2))

### [3.1.13](https://github.com/dangeroustech/StreamDL/compare/v3.1.12...v3.1.13) (2023-10-17)


### ✍ Chore

* **deps-dev:** bump gitpython from 3.1.36 to 3.1.37 ([ae447fe](https://github.com/dangeroustech/StreamDL/commit/ae447fed974a7fa71174c4ae51ba8ff646536e69))
* **deps:** bump golang.org/x/net from 0.8.0 to 0.17.0 ([787478f](https://github.com/dangeroustech/StreamDL/commit/787478f885961be34937446b2cf8f026b05c1643))

### [3.1.12](https://github.com/dangeroustech/StreamDL/compare/v3.1.11...v3.1.12) (2023-10-04)


### ✍ Chore

* **deps:** bump urllib3 from 2.0.4 to 2.0.6 ([13dbac5](https://github.com/dangeroustech/StreamDL/commit/13dbac50b403e2933ada5a9fc5a655659df5efc5))

### [3.1.11](https://github.com/dangeroustech/StreamDL/compare/v3.1.10...v3.1.11) (2023-09-12)


### ✍ Chore

* add todo ([663db81](https://github.com/dangeroustech/StreamDL/commit/663db81248984c46cba86fdb05cbdbef20cf139e))
* bump poetry version to 1.6.1 ([c3ba4d2](https://github.com/dangeroustech/StreamDL/commit/c3ba4d2301daac2b27f6dd5ca7616230870d60a2))
* rename test to be twitch specific ([a66bcda](https://github.com/dangeroustech/StreamDL/commit/a66bcda8e93f85497e8be9e28062f54023a33566))
* update to new ubuntu and python versions ([7169e8d](https://github.com/dangeroustech/StreamDL/commit/7169e8dce335e0aa1eaca356981d3c2238557a28))


### 📚 Documentation

* fix indentation ([cb67e7c](https://github.com/dangeroustech/StreamDL/commit/cb67e7c43b45aafe20cb7a87a9b7909541db40b8))
* update wording around default log level ([5481c39](https://github.com/dangeroustech/StreamDL/commit/5481c39291a89216fd2789715aa9f712a4e75666))


### 🤖 CI/CD

* add docker buildx setup to support caching ([9250619](https://github.com/dangeroustech/StreamDL/commit/925061957f1969e2cfad534100feb14a6d2c162f))
* add explicit run step ([45429f2](https://github.com/dangeroustech/StreamDL/commit/45429f2d2c51efaa8176e50c7ac7e1ca1a27a725))
* add golang testing stage ([8c23f39](https://github.com/dangeroustech/StreamDL/commit/8c23f3962a2416b55b66f656dfb31163835510bf))
* add local server build to test workflow ([af037b8](https://github.com/dangeroustech/StreamDL/commit/af037b883f304988106a0dd8a8c468159de75a51))
* pass env var as a string ([bc3a508](https://github.com/dangeroustech/StreamDL/commit/bc3a5087418500260ca70f50b05303b36e6e287e))
* run docker action inline and background ([4ee4148](https://github.com/dangeroustech/StreamDL/commit/4ee4148e2229c001af8effbaad8abcb9f638d0b2))


### 🐛 Bug Fixes

* correct logging ([919c4ed](https://github.com/dangeroustech/StreamDL/commit/919c4ed0d72d3193ac545300554250b239109e21))
* properly raise errors for PluginNotFound ([faef870](https://github.com/dangeroustech/StreamDL/commit/faef8705434bd757b3f6ba9bcf9e83422203197e))
* test: correct python version ([02bb7f9](https://github.com/dangeroustech/StreamDL/commit/02bb7f901b2bd1e2bf81412cbcc1d05091ce1ecb))
* test: directly run the python? ([07353e2](https://github.com/dangeroustech/StreamDL/commit/07353e2b2c71cbc5c0f904508a64d693118f6016))
* test: install deps ([b56d21e](https://github.com/dangeroustech/StreamDL/commit/b56d21eb95581baf868218c7bf75336d2930a9b5))
* test: typo ([b9ce052](https://github.com/dangeroustech/StreamDL/commit/b9ce0520a57fba7eee3201033dc4f7a4d96f0a2e))


### 🧪 Tests

* actually remember how poetry is used ([bcc4ae7](https://github.com/dangeroustech/StreamDL/commit/bcc4ae7af826f6781a2d0f554de3e4e376d242b3))
* add 404 client test ([de568bd](https://github.com/dangeroustech/StreamDL/commit/de568bd1256aaffa64a5d4bc4f0885002620ce97))
* add comments ([5a2d7c7](https://github.com/dangeroustech/StreamDL/commit/5a2d7c7405547bbd5eda80456ad65f28d1d28a4f))
* add tests for more sites ([ff595a4](https://github.com/dangeroustech/StreamDL/commit/ff595a43b699e85564dbf8c77aa713d1b4c1173c))
* fully deprecate test pid killer ([9f9461e](https://github.com/dangeroustech/StreamDL/commit/9f9461e7a95dc7ac0391faf8fefd242014fd7fe3))
* just run the server inline ([a3e368d](https://github.com/dangeroustech/StreamDL/commit/a3e368d5f4e80faa5602f1a8eb29d883e805c9d6))
* manually govern killing the server ([7de5171](https://github.com/dangeroustech/StreamDL/commit/7de51718d7f6f7957968e4b5db80f34478eee06c))
* remove pid killing logic ([f3e0d3d](https://github.com/dangeroustech/StreamDL/commit/f3e0d3d21ec917924ef32c40d922671f8247eee7))
* simplify testing strategy ([31a4db0](https://github.com/dangeroustech/StreamDL/commit/31a4db0203beaffa8d4a4181ff9330ecfde7379b))

### [3.1.10](https://github.com/dangeroustech/StreamDL/compare/v3.1.9...v3.1.10) (2023-09-09)


### 🐛 Bug Fixes

* migrate release action away from deprecated ([e1503bf](https://github.com/dangeroustech/StreamDL/commit/e1503bfe174f1c9a69c50aa7bfcc62402ac855a0))
* upgrade actions/setup-python to v4 ([e0d2971](https://github.com/dangeroustech/StreamDL/commit/e0d297149962e77e106114ebced2cb114f812267))
* upgrade checkout and setup-node deps ([5aedd65](https://github.com/dangeroustech/StreamDL/commit/5aedd6511663ab32b8850a911c6db68a62f29aaf))

### [3.1.9](https://github.com/dangeroustech/StreamDL/compare/v3.1.8...v3.1.9) (2023-09-09)


### 🐛 Bug Fixes

* Dockerfile.client to reduce vulnerabilities ([d686d83](https://github.com/dangeroustech/StreamDL/commit/d686d835baf1c58a8e6e5eb742a259a0e7df5429))

### [3.1.8](https://github.com/dangeroustech/StreamDL/compare/v3.1.7...v3.1.8) (2023-09-09)


### ✍ Chore

* **deps-dev:** bump gitpython from 3.1.31 to 3.1.35 ([61dde00](https://github.com/dangeroustech/StreamDL/commit/61dde00fb71c25e2838440f74f479fa4f3b13ca1))

### [3.1.7](https://github.com/dangeroustech/StreamDL/compare/v3.1.6...v3.1.7) (2023-09-09)


### 📚 Documentation

* use local reference for example compose file ([3a4136a](https://github.com/dangeroustech/StreamDL/commit/3a4136aac20f33a8ab65718d097dd8c41f7a64be))


### 🐛 Bug Fixes

* correct log level specification ([590e641](https://github.com/dangeroustech/StreamDL/commit/590e64166e65d1570dcc3915109ddc14a521d2d7))
* correct logging implementation ([485f585](https://github.com/dangeroustech/StreamDL/commit/485f585be59b5dc88bb92637bf7566300839d97a))
* migrate to new streamlink options format ([acb8229](https://github.com/dangeroustech/StreamDL/commit/acb8229cc162d67c443074ba3a5c7660f08edf23))

### [3.1.6](https://github.com/dangeroustech/StreamDL/compare/v3.1.5...v3.1.6) (2023-08-05)


### 🐛 Bug Fixes

* Dockerfile.client to reduce vulnerabilities ([c15f8d9](https://github.com/dangeroustech/StreamDL/commit/c15f8d9357995be4571703c09bdc5a25e719e608))


### ✍ Chore

* **deps:** bump certifi from 2022.12.7 to 2023.7.22 ([b7322cb](https://github.com/dangeroustech/StreamDL/commit/b7322cb0974723dc4add4eb5d6fcab8e50051f14))

### [3.1.5](https://github.com/dangeroustech/StreamDL/compare/v3.1.4...v3.1.5) (2023-05-30)


### 🤖 CI/CD

* allow code scan to fail ([5e8026e](https://github.com/dangeroustech/StreamDL/commit/5e8026ecf04e5dc868e85fdb1f750a64f16aade7))
* switch to building on pull request target ([aac8344](https://github.com/dangeroustech/StreamDL/commit/aac834464ec09de35f995291d01806d0250793ec))


### ✍ Chore

* bump various ci tool versions ([e1dcde8](https://github.com/dangeroustech/StreamDL/commit/e1dcde86c7fa69371514996305c0078637380d55))
* **deps:** bump requests from 2.28.2 to 2.31.0 ([149dd80](https://github.com/dangeroustech/StreamDL/commit/149dd802a7f74a53032787d8136e7f3fd998c517))

### [3.1.4](https://github.com/dangeroustech/StreamDL/compare/v3.1.3...v3.1.4) (2023-04-30)


### ✍ Chore

* **deps:** bump google.golang.org/protobuf from 1.29.0 to 1.29.1 ([48570b5](https://github.com/dangeroustech/StreamDL/commit/48570b521e450a91661801ad4022c6ad899ea697))
* update docker login-action to v2 ([80ccd32](https://github.com/dangeroustech/StreamDL/commit/80ccd32dd3df070135ab4e902465371889dc93aa))

### [3.1.3](https://github.com/dangeroustech/StreamDL/compare/v3.1.2...v3.1.3) (2023-03-09)


### 🧪 Tests

* fix: yaml formatting ([37396dd](https://github.com/dangeroustech/StreamDL/commit/37396dd845376bbc2c637844270e99affbc9905d))
* update pr tests ([dd5caa6](https://github.com/dangeroustech/StreamDL/commit/dd5caa6b2a7b8719cfc518d03d758bb480d9d06e))


### 🐛 Bug Fixes

* cannot push and load because reasons ([1fc974c](https://github.com/dangeroustech/StreamDL/commit/1fc974c5aabef2191b5f9688008da821b135dd50))
* go deps update ([c41e54b](https://github.com/dangeroustech/StreamDL/commit/c41e54b56af238a54ee78fb5a554b6843483777a))
* testing manual pprof import ([bc98995](https://github.com/dangeroustech/StreamDL/commit/bc989956295d432c894fdcbb4f3d817327797f0c))
* version pin golang properly ([d4ac670](https://github.com/dangeroustech/StreamDL/commit/d4ac6702ca22835b5f5fb7ee8325230570ab1a99))


### 🤖 CI/CD

* build on issue* PRs ([3fee9cc](https://github.com/dangeroustech/StreamDL/commit/3fee9cc3ea041943bff39fba9a76a55a2daa4255))
* continue on error if there's no code scanning ([b7fe857](https://github.com/dangeroustech/StreamDL/commit/b7fe857ca7d5e61ed3c88c0574a500bc537ee359))
* deprecate arm64 staging builds ([aea3a1c](https://github.com/dangeroustech/StreamDL/commit/aea3a1cdd35e2e5cddcca1a8f9b5cbe16e31bafd))
* fix: base needs to be staging for PRs ([ad8e96a](https://github.com/dangeroustech/StreamDL/commit/ad8e96a3875bad7b3b3e8d4e00a5a0229fa54a30))
* just work, we'll fix the protobuf thing later ([a5d12eb](https://github.com/dangeroustech/StreamDL/commit/a5d12eb2d7fb8403a055c4b7410cb5dd8f936f37))
* load doesn't load... ([6350937](https://github.com/dangeroustech/StreamDL/commit/6350937eaf335e90f6779398ec197c7b6ad461b6))
* remove org flag from local image ([cd050b2](https://github.com/dangeroustech/StreamDL/commit/cd050b26d75247b35b3d0e5b6b277e8abf82e999))

### [3.1.2](https://github.com/dangeroustech/StreamDL/compare/v3.1.1...v3.1.2) (2023-03-09)


### ✍ Chore

* add build-essentials to container ([2d6c7cd](https://github.com/dangeroustech/StreamDL/commit/2d6c7cd9171c9a58df81f739223a5df12e99ab3e))
* bump poetry version in Dockerfile ([ebcfe66](https://github.com/dangeroustech/StreamDL/commit/ebcfe668ad3b7d687872f42c9a3ae7c56818d6d0))
* **deps:** bump certifi from 2022.9.24 to 2022.12.7 ([faf1d22](https://github.com/dangeroustech/StreamDL/commit/faf1d22eb49bd8b24796504be2941412c3bb662b))
* **deps:** bump golang.org/x/net from 0.1.0 to 0.7.0 ([d61d5af](https://github.com/dangeroustech/StreamDL/commit/d61d5afbf0e3267e1d02bea3ac5f30c2d273db6d))
* **deps:** bump golang.org/x/net from 0.1.0 to 0.7.0 ([743f4ad](https://github.com/dangeroustech/StreamDL/commit/743f4adf8876e185c6c134b551ded7038d802ef5))
* **deps:** bump setuptools from 65.3.0 to 65.5.1 ([ca44107](https://github.com/dangeroustech/StreamDL/commit/ca44107ae72b6dc133a0c7cc53fdb3b7c4b7c621))
* fully roll back ffmpeg ([0fe3828](https://github.com/dangeroustech/StreamDL/commit/0fe3828663cd1b002b6e909ded4a29517c5d6856))
* roll back to python 3.10 ([de7fa61](https://github.com/dangeroustech/StreamDL/commit/de7fa61d38bf400b28529734a7d7718b6ddcafe9))
* slightly roll ffmpeg back ([da9b408](https://github.com/dangeroustech/StreamDL/commit/da9b408fbec96a5d3d9c878794a878345821eb1b))
* update .gitignore ([d6d9d8f](https://github.com/dangeroustech/StreamDL/commit/d6d9d8f167e5f894ff065c11436ac8370cc6962a))
* update docker underlying OS ([e73cae3](https://github.com/dangeroustech/StreamDL/commit/e73cae38d64e1f25eb395759437a049fd4bb1c82))
* update ffmpeg version ([fa440c8](https://github.com/dangeroustech/StreamDL/commit/fa440c8b2d799277735161d6dd527f2458507a48))
* update poetry deps ([0869e05](https://github.com/dangeroustech/StreamDL/commit/0869e0525fc897f3691f6bbef27a8068a1b1c2c5))
* upgrade pip ([9fec876](https://github.com/dangeroustech/StreamDL/commit/9fec876e2d1565277092847bec7f453b72fd2378))


### 🐛 Bug Fixes

* better version pinning for golang ([b58850f](https://github.com/dangeroustech/StreamDL/commit/b58850f1f3df7237f00ced0ba956f5eaf7f7970e))
* combine file copies into one layer ([81fd0d2](https://github.com/dangeroustech/StreamDL/commit/81fd0d2345f0a032b93b5963048188e7e3842302))
* hippy hop ([35ddf18](https://github.com/dangeroustech/StreamDL/commit/35ddf18d9d85f4ad316776bccb8200a24dc034e9))
* idk rewind ([8d3cdb1](https://github.com/dangeroustech/StreamDL/commit/8d3cdb14a25a287ca6a0bd9ffd96bf4459810cc8))
* install build-essential ([b42a27b](https://github.com/dangeroustech/StreamDL/commit/b42a27ba365702d51603cac0726ea25c4bfe0b1d))
* pip upgrade breaks things ([40cd5d3](https://github.com/dangeroustech/StreamDL/commit/40cd5d3c1a4e3b813fa5ef2fdc8c534513ca16ce))
* revert ([dc28c5a](https://github.com/dangeroustech/StreamDL/commit/dc28c5a7ab6d223f341436ddeb592f6c4d8d4a18))
* see if adding wheel speeds up build time ([9212df7](https://github.com/dangeroustech/StreamDL/commit/9212df72c6a52f6a43742cd203c7852fe32547b9))
* thicc python ([4201767](https://github.com/dangeroustech/StreamDL/commit/4201767e163ae8186afde31449e2c58e28baed86))
* this builds locally... ([a9a6704](https://github.com/dangeroustech/StreamDL/commit/a9a6704ae752b35bfd0a2a793bf08e4eccee9e6c))
* update go mod ([f9fe66c](https://github.com/dangeroustech/StreamDL/commit/f9fe66c2d118208b2c6571b81b7e88e63b28604e))

### [3.1.1](https://github.com/dangeroustech/StreamDL/compare/v3.1.0...v3.1.1) (2022-10-30)


### 🐛 Bug Fixes

* bump debian version for less vulns ([9b3491b](https://github.com/dangeroustech/StreamDL/commit/9b3491b9c4adc35d1c359a2997fd19946f194137))
* remove vulnerable go1.16 deps ([50e0dbe](https://github.com/dangeroustech/StreamDL/commit/50e0dbe1f1b05b314d883d0a159928148355569f))
* specific staging tag for staging scan ([b131dfe](https://github.com/dangeroustech/StreamDL/commit/b131dfe79332302f6389f9813309ec0fe2907c4e))


### 🤖 CI/CD

* add Snyk scan to master CI ([13f8e7b](https://github.com/dangeroustech/StreamDL/commit/13f8e7be2b9ac6fa52caddb42f1c9cb381ff7dbf))

## [3.1.0](https://github.com/dangeroustech/StreamDL/compare/v3.0.4...v3.1.0) (2022-10-30)


### 🎉 New Features

* sec: add snyk checks to staging ([1ff4e9d](https://github.com/dangeroustech/StreamDL/commit/1ff4e9d64f4ff82b805b826174a701ba4695d6e1))

### [3.0.4](https://github.com/dangeroustech/StreamDL/compare/v3.0.3...v3.0.4) (2022-10-30)

### [3.0.3](https://github.com/dangeroustech/StreamDL/compare/v3.0.2...v3.0.3) (2022-10-09)


### 🐛 Bug Fixes

* no longer using python for client operations ([cdd4da0](https://github.com/dangeroustech/StreamDL/commit/cdd4da06bd394270bfeabcb9fac13c241f902099))
* regen protoc files for protobuf v4 bump ([fd0b282](https://github.com/dangeroustech/StreamDL/commit/fd0b2823fb9f837ca8e69aa974ccbdb311d03487))
* remove --twitch-disable-hosting usage ([7b13fc7](https://github.com/dangeroustech/StreamDL/commit/7b13fc77c9a59579830ca89a24131887fc1f2f55))
* use latest image version in example compose ([b95d1a3](https://github.com/dangeroustech/StreamDL/commit/b95d1a3f2e44177f98bff8aaa6df81ce863c8259))


### ✍ Chore

* fix linting issue ([ee1f607](https://github.com/dangeroustech/StreamDL/commit/ee1f607e0280ee0f58f20cbe58994470ca106b80))
* poetry update ([0b0b330](https://github.com/dangeroustech/StreamDL/commit/0b0b3309fd95646ee3ee71a1d842dc5c9b0f9113))

### [3.0.2](https://github.com/dangeroustech/StreamDL/compare/v3.0.1...v3.0.2) (2022-10-09)


### ✍ Chore

* **deps:** bump protobuf from 3.20.1 to 3.20.2 ([76d2a9d](https://github.com/dangeroustech/StreamDL/commit/76d2a9d26e468db3d8417ce703e75914451a0747))

### [3.0.1](https://github.com/dangeroustech/StreamDL/compare/v3.0.0...v3.0.1) (2022-08-19)


### ✍ Chore

* cleanup deps ([9c679d3](https://github.com/dangeroustech/StreamDL/commit/9c679d3e0ff84c8aa784476720767ec528d54e39))
* deps update ([e5afde3](https://github.com/dangeroustech/StreamDL/commit/e5afde3eda4d739ba63613fc59eafb696b6b31cd))
* file cleanup ([73ef694](https://github.com/dangeroustech/StreamDL/commit/73ef694522cce9802d42bb3e5beaff6b7ef328b5))


### 🐛 Bug Fixes

* correct default tick_time ([924fcb1](https://github.com/dangeroustech/StreamDL/commit/924fcb184fa81ad3a64a3aceb221161302246d29))
* properly parse log_level from env ([650bbdd](https://github.com/dangeroustech/StreamDL/commit/650bbdd3119f99f84823243180125ff0b5a9d1ac))
* update ci to publish fixes ([5de7e6e](https://github.com/dangeroustech/StreamDL/commit/5de7e6e8083df3bfd8cb385721a07c5c3c9c2645))


### 📚 Documentation

* :memo: correct docs around tick_time ([a9d4802](https://github.com/dangeroustech/StreamDL/commit/a9d4802f92788e877f63bd3efb6a2be5b6442acc))
* update badges ([ea8f168](https://github.com/dangeroustech/StreamDL/commit/ea8f1686c66dbef03118743ec9f9a987a840c16c))
* update SECURITY.md ([4a5ab25](https://github.com/dangeroustech/StreamDL/commit/4a5ab25f4dcb642b084d43d40e237ec485926ac8))

## [3.0.0](https://github.com/dangeroustech/StreamDL/compare/v2.3.0...v3.0.0) (2022-08-18)


### ⚠ BREAKING CHANGES

* v3 publication :tada:

### 📚 Documentation

* :sparkles: update docs for v3 ([056eede](https://github.com/dangeroustech/StreamDL/commit/056eede02441d9fa114833af1e33bd3b7db47e36))

## [2.3.0](https://github.com/dangeroustech/StreamDL/compare/v2.2.1...v2.3.0) (2022-08-18)


### 🔥 Style

* plans for refactor ([34e7b80](https://github.com/dangeroustech/StreamDL/commit/34e7b80a84afddb87360915ef443ff2f7dbaf4a0))


### 🎉 New Features

* add proper logging ([139054b](https://github.com/dangeroustech/StreamDL/commit/139054b60850768bdda80b146e5f43f582fc130e))
* add relevant flags ([3da9c2f](https://github.com/dangeroustech/StreamDL/commit/3da9c2f0921d8775538abd43096ffa11898ca486))
* **app:** add protobuf server implementation ([70d0c1b](https://github.com/dangeroustech/StreamDL/commit/70d0c1b3e2fac129e7b754ee14691bc2cf35dbe4))
* **app:** WIP - golang grpc client implementation ([2f2c046](https://github.com/dangeroustech/StreamDL/commit/2f2c0462f008f5aeaa5e62603c404de64fc067f5))
* initial ffmpeg download ([e2d0211](https://github.com/dangeroustech/StreamDL/commit/e2d0211854ce017ad57a868a4fe6591ed622cce8))
* yaml parsing ([47fd5ec](https://github.com/dangeroustech/StreamDL/commit/47fd5ec41224969a1155fab2044b13fee81c80fa))


### ✍ Chore

* add error conditions ([78248cb](https://github.com/dangeroustech/StreamDL/commit/78248cbb7dfc1df25342a95a3260be9737f4a3ed))
* add some logging ([c4ffd88](https://github.com/dangeroustech/StreamDL/commit/c4ffd888db36776dc6377b6e265d585cf789a764))
* better logging ([8b56aa1](https://github.com/dangeroustech/StreamDL/commit/8b56aa12bde0d7a4b07a33bd8a7a7c59bcb6c2e4))
* bump poetry deps ([fb34276](https://github.com/dangeroustech/StreamDL/commit/fb3427678e2578fe23932c9070f9e8528172a14c))
* bump python version for pattern matching ([432a6f8](https://github.com/dangeroustech/StreamDL/commit/432a6f85a7ea7594226a5589046cfc1bc1981e81))
* bump yaml version ([4581d1b](https://github.com/dangeroustech/StreamDL/commit/4581d1bbe65ff1a2dd7d95209386c5ece9462c78))
* bump yaml version to v3 ([e56ccbf](https://github.com/dangeroustech/StreamDL/commit/e56ccbf8974ef048e2460eafc327a54c7b9505f3))
* log type changes ([8792099](https://github.com/dangeroustech/StreamDL/commit/879209978fb09ae6e45c32dbab466e944599cfe3))
* reorganise functions ([591735f](https://github.com/dangeroustech/StreamDL/commit/591735f4c9d0228b022f5a42971be07f8d5d7d45))
* sensible file naming ([c124efa](https://github.com/dangeroustech/StreamDL/commit/c124efa6f5c285ec4217d5e0834d55e0d96c1314))
* upgrade yaml package version ([f4d93c5](https://github.com/dangeroustech/StreamDL/commit/f4d93c5fec4bc66d6a62c60ea85c1d620dffeddf))


### 🐛 Bug Fixes

* add 200 code on success ([5469931](https://github.com/dangeroustech/StreamDL/commit/54699316b7651219a8514f88bd0c755989cafa77))
* correct deprecated option ([8fae1a1](https://github.com/dangeroustech/StreamDL/commit/8fae1a161d60f56f6cfcb3cdf03367dbc384874b))
* correct error flow ([8ae0997](https://github.com/dangeroustech/StreamDL/commit/8ae0997dfbe9ce0bcd3db3e12c0212b77911f418))
* correct example mappings ([5efc7e6](https://github.com/dangeroustech/StreamDL/commit/5efc7e6e965da092464ad1f34bf250e3be833a12))
* correct example yaml keys ([1173aac](https://github.com/dangeroustech/StreamDL/commit/1173aac4e0340f04cbf19436732a180ca28d8ee6))
* every condition besides ctrl c works fine... ([17b45a5](https://github.com/dangeroustech/StreamDL/commit/17b45a5bb46076f2114e8fa254a988f5f4016ed9))
* minor docker retooling ([e82a902](https://github.com/dangeroustech/StreamDL/commit/e82a902c4621d3c7a6bf271ee95432a6188e8432))
* proper gRPC error handling ([952b945](https://github.com/dangeroustech/StreamDL/commit/952b9456d9fdc6849072504270fa2e5032d7a30a))
* pull grpc socket stuff from env ([1800481](https://github.com/dangeroustech/StreamDL/commit/1800481738fde5dd575d8ee3ca93b690feb963bf))
* rename entrypoint scripts ([8d6b460](https://github.com/dangeroustech/StreamDL/commit/8d6b460f1e3a8c6063a9a34d46534a5c0e866335))
* sensible yaml keys ([5df3907](https://github.com/dangeroustech/StreamDL/commit/5df39077164f758153f3a84b2aa2655765a7b23b))
* tidied up docker build ([58f23ef](https://github.com/dangeroustech/StreamDL/commit/58f23ef39aa4b35f5679e60c85a0e4c8a7fd70ea))


### 📚 Documentation

* correct example to pull from dockerhub ([ed028b3](https://github.com/dangeroustech/StreamDL/commit/ed028b369c93800e8f8e5ab5d394b1628bbdb007))
* remove old example dockerfile ([a09ed95](https://github.com/dangeroustech/StreamDL/commit/a09ed95bb2b1b3038383966acc20fcd2f92a1509))
* update example config file ([928116e](https://github.com/dangeroustech/StreamDL/commit/928116ee740cd473e43d5d7b944a48f5027aa2b3))
* update example docker-compose ([53a700f](https://github.com/dangeroustech/StreamDL/commit/53a700f892136b8d33da8d70f44a4ac6046fdf5c))


### 🧪 Tests

* correct file name ([25834cc](https://github.com/dangeroustech/StreamDL/commit/25834cccb26680f4e4e1d984f7ed22b28d3ff18a))
* deprecate python 3.9 ([46b04a0](https://github.com/dangeroustech/StreamDL/commit/46b04a04a8a493ad892249a2ff3b449a9892f35b))
* testing changes ([644e4d0](https://github.com/dangeroustech/StreamDL/commit/644e4d09f87ffac6c89d28f8cf7d6c2f375656d7))


### 🤖 CI/CD

* fix dockerhub typos ([097a5ed](https://github.com/dangeroustech/StreamDL/commit/097a5ed91030e273e72046d6a5c74ff81d58d40c))
* update ci jobs for multi container builds ([d9da9e2](https://github.com/dangeroustech/StreamDL/commit/d9da9e2dea00eba3411b621ad84894d9caceba26))

### [2.2.1](https://github.com/dangeroustech/StreamDL/compare/v2.2.0...v2.2.1) (2022-03-10)


### ✍ Chore

* deps update ([dbb63a1](https://github.com/dangeroustech/StreamDL/commit/dbb63a166435baf7f823479c6211053057a73467))

## [2.2.0](https://github.com/dangeroustech/StreamDL/compare/v2.1.1...v2.2.0) (2022-01-29)


### ✍ Chore

* **app:** import cleaning ([a8cf8be](https://github.com/dangeroustech/StreamDL/commit/a8cf8be82d30ab456990ba43b52fde5623c088ce))
* **deps:** update deps ([d717a6b](https://github.com/dangeroustech/StreamDL/commit/d717a6b0fffdd8fab8eee894471dd01f772958d8))


### 🎉 New Features

* **app:** allow custom ytdl options specification ([bffe8d4](https://github.com/dangeroustech/StreamDL/commit/bffe8d4f4fa06e6beb4ff8c5134ab9605d70c036))


### 🧪 Tests

* **app:** fix broken offline twitch test ([5c82a21](https://github.com/dangeroustech/StreamDL/commit/5c82a2150df8d537ab68d49798ed4e78a1efffb6))

### [2.1.1](https://github.com/dangeroustech/StreamDL/compare/v2.1.0...v2.1.1) (2022-01-29)


### 🐛 Bug Fixes

* **ci:** correct repo checkout for tags ([0dda40b](https://github.com/dangeroustech/StreamDL/commit/0dda40ba7281c1785ef63a13eea9d5a57f4feffd))

## [2.1.0](https://github.com/dangeroustech/StreamDL/compare/v2.0.5...v2.1.0) (2022-01-29)


### 🎉 New Features

* **build:** slim down docker conatiners ([5232609](https://github.com/dangeroustech/StreamDL/commit/5232609d91b639bdd8afbaa9a3fb1777203aa46d)), closes [#219](https://github.com/dangeroustech/StreamDL/issues/219)


### 🐛 Bug Fixes

* **app:** use ffmpeg copy codec ([c4c694a](https://github.com/dangeroustech/StreamDL/commit/c4c694a71088bd2d8aea625e5879613df721c07b))
* **build:** supporting python call without poetry ([2acb76b](https://github.com/dangeroustech/StreamDL/commit/2acb76b266461d077b16af620842123b5cf41183))

### [2.0.5](https://github.com/dangeroustech/StreamDL/compare/v2.0.4...v2.0.5) (2022-01-29)


### ✍ Chore

* add security vuln issue template ([c191016](https://github.com/dangeroustech/StreamDL/commit/c1910166d83f1deefce33e09d1cb0348bc16c5e9))
* clarity around bug template ([cde4b44](https://github.com/dangeroustech/StreamDL/commit/cde4b447ba7ae28a475163ed9ff318338f062ecf))
* update contributing.md ([eb2596d](https://github.com/dangeroustech/StreamDL/commit/eb2596dd5d8b285c85813a666214aba3d7b6ce00))
* update supported versions ([819c6b7](https://github.com/dangeroustech/StreamDL/commit/819c6b70e08036ee19f08f43b822c3600f6aa6ad))

### [2.0.4](https://github.com/dangeroustech/StreamDL/compare/v2.0.3...v2.0.4) (2022-01-29)


### 🤖 CI/CD

* reduce codeql frequency ([9052ab7](https://github.com/dangeroustech/StreamDL/commit/9052ab7345056d5d8effbc000445773468866f07))


### 🐛 Bug Fixes

* **changelog:** add changelog config ([dc5df47](https://github.com/dangeroustech/StreamDL/commit/dc5df4715cc60f6c269ffe8e5b58b58368de4a96))
* install changelog npm package ([ae16b56](https://github.com/dangeroustech/StreamDL/commit/ae16b56227795dfb1b7ef1065317e6f4f764f749))

### [2.0.3](https://github.com/dangeroustech/StreamDL/compare/v2.0.2...v2.0.3) (2022-01-29)


### 🐛 Bug Fixes

* remove unnecessary docker build ([a331f56](https://github.com/dangeroustech/StreamDL/commit/a331f569702a1403f04602d128d81db025af05d9))

### [2.0.2](https://github.com/dangeroustech/StreamDL/compare/v0.1.0...v2.0.2) (2022-01-29)


### ✍ Chore

* proper version bump ([f62706a](https://github.com/dangeroustech/StreamDL/commit/f62706a024fda5ef3c34d7a8ab6efc3f7928b193))


### 🐛 Bug Fixes

* properly order release stuff ([123b00e](https://github.com/dangeroustech/StreamDL/commit/123b00ed5480b20e4bd8b3afc54f83213d832692))
* revert and fix changelog options ([6f2545d](https://github.com/dangeroustech/StreamDL/commit/6f2545d93092458e7a851fe3bdbe7bd84d4c0e14))

## [0.1.0](https://github.com/dangeroustech/StreamDL/compare/v2.0.1...v0.1.0) (2022-01-29)


### 🔥 Style

* first actual run through black ([e023416](https://github.com/dangeroustech/StreamDL/commit/e0234160f3f11b9d4c3b3908d942587a74bbdbdc))
* less lines [skip ci] ([9191e46](https://github.com/dangeroustech/StreamDL/commit/9191e465ef8aace5ed1203fd6aa9fc9e9d5fe848))


### 🏭 Build

* differentiate names [skip ci] ([8fe78f5](https://github.com/dangeroustech/StreamDL/commit/8fe78f5c24b863ad0a7c7f1e39ee40c1db446422))
* split build workflows ([e138f6c](https://github.com/dangeroustech/StreamDL/commit/e138f6c8b96ccd04eebde2c0e88ac81eefa47f9c))
* update dockerfile reference ([03e6fa3](https://github.com/dangeroustech/StreamDL/commit/03e6fa30d2e94718f1479069ab945e5d77b3e9db))


### 🧪 Tests

* correctly import yt-dlp utils ([40cfe57](https://github.com/dangeroustech/StreamDL/commit/40cfe57cb559b4476cc00d4a9622b06b6071ce10))


### 📚 Documentation

* document new -q flag ([8bb36fe](https://github.com/dangeroustech/StreamDL/commit/8bb36fe6e93b7f3b841675839ecd174575e8c530))
* remove old changelog ([d63ace6](https://github.com/dangeroustech/StreamDL/commit/d63ace6550125b87051b7b64e52ed9030a000c85))


### 🐛 Bug Fixes

* add black as dev package for linting ([0408155](https://github.com/dangeroustech/StreamDL/commit/0408155f1481ea33778b7902d3ecb9bf10f6c7ab))
* add ffmpeg install to container build ([37fd89a](https://github.com/dangeroustech/StreamDL/commit/37fd89ab4b5f368cbc6890ab732c3c3a1bae0826))
* allow custom quality specification for twitch ([9808629](https://github.com/dangeroustech/StreamDL/commit/9808629b0463806dd271a5c5dfc3d36724f277a6))
* author and version bump ([8ca63d4](https://github.com/dangeroustech/StreamDL/commit/8ca63d440421d10ae0006e294edbb3de92cff504))
* author slug ([8dbbdc8](https://github.com/dangeroustech/StreamDL/commit/8dbbdc87cfafc4be1661c59c84f731f489d63d74))
* coherent example file naming ([31e4730](https://github.com/dangeroustech/StreamDL/commit/31e4730c954a19c45e08431af80af3dddd875054))
* correct SIG* exit code ([72bcfb0](https://github.com/dangeroustech/StreamDL/commit/72bcfb0bc6c8e44f18889691948e9bf466cbc1cb))
* native streamlink/ffmpeg stream downloading ([ed6a036](https://github.com/dangeroustech/StreamDL/commit/ed6a036feb5a93d0bff84473d7c538c96dc4da94)), closes [#212](https://github.com/dangeroustech/StreamDL/issues/212)
* natively creating twitch dir ([5de7a24](https://github.com/dangeroustech/StreamDL/commit/5de7a244bcead97b9972c07bd975a5fa8c19e9f5))
* rename to sensible workflow names ([92dc257](https://github.com/dangeroustech/StreamDL/commit/92dc2575e7979fc92d3b651185536a361d2e4c91))
* shut ffmpeg up ([ea61f70](https://github.com/dangeroustech/StreamDL/commit/ea61f701925548b7a2720b331e24a75baf3dac7c))
* weird offline stream bug ([18b053d](https://github.com/dangeroustech/StreamDL/commit/18b053da4240574a604c1a173c4705d6525d2360))
* yt-dlp dropped in ([d90a8f2](https://github.com/dangeroustech/StreamDL/commit/d90a8f267fff7d00454b92bfe34959ee3a3a3cd8))


### 🤖 CI/CD

* add ci workflow ([f96e834](https://github.com/dangeroustech/StreamDL/commit/f96e8340cd8466113a2e70e91ad5e4a22ad95faf))
* add docker build as test ([39124f4](https://github.com/dangeroustech/StreamDL/commit/39124f4b26d8c4f8aa22b328ee6d9acda23163dc))
* change release action to write changelog ([d42db21](https://github.com/dangeroustech/StreamDL/commit/d42db21c507ddd3cabdea0b1c7badec4b9d97488))
* check out the repo first ([14f01d9](https://github.com/dangeroustech/StreamDL/commit/14f01d9b19068388c1511e0678d8417a4b0c1f79))
* CI on staging - dependabot [skip ci] ([d0b7f3d](https://github.com/dangeroustech/StreamDL/commit/d0b7f3d49d4eb18f4216e09ef2afa9fd44f2bbf0))
* correct test tag ([be6aad4](https://github.com/dangeroustech/StreamDL/commit/be6aad48cef5651ffd8f59397947b7bad9ffacdf))
* don't release on staging ([4ae58f0](https://github.com/dangeroustech/StreamDL/commit/4ae58f0ba76049ab206cf6090c8ec1b633fffe81))
* revert cargo version ([0a22d54](https://github.com/dangeroustech/StreamDL/commit/0a22d541474741b4a292346f4b24176fa4929633))


### 🎉 New Features

* add proper tag to dockerhub push ([373952a](https://github.com/dangeroustech/StreamDL/commit/373952a4e8802b7e5cbbce1391575008df0f24a4))
* deprecate old arm builds ([f0f2b05](https://github.com/dangeroustech/StreamDL/commit/f0f2b051fc9ddbf930f23327759190d9a8990e09))


### ✍ Chore

* add todo ([7525bab](https://github.com/dangeroustech/StreamDL/commit/7525bab7dde4e89e692993aa06cd691f8486bc49))
* bump deps ([f387a3b](https://github.com/dangeroustech/StreamDL/commit/f387a3b77b8221fceb036397225d434d63469623))
* improve debug log ([90f6208](https://github.com/dangeroustech/StreamDL/commit/90f62085a32feb201ecb0e61dcc358921525c25c))
* **release:** v0.1.0 [skip ci] ([c7680e1](https://github.com/dangeroustech/StreamDL/commit/c7680e134b91a094326cde9e38873831af8f4c32))
* streamlink bump to 3.0.3 ([841260c](https://github.com/dangeroustech/StreamDL/commit/841260c2e4d87daf2ded0cd0051d73b12319c9a7))
* update gitignore ([c153deb](https://github.com/dangeroustech/StreamDL/commit/c153deb6d90239b49fcff16d3b8f65dfe5b40911))

### [1.2.7](https://github.com/dangeroustech/StreamDL/compare/v1.2.6...v1.2.7) (2022-01-18)


### 📚 Documentation

* readme ([714963a](https://github.com/dangeroustech/StreamDL/commit/714963a3356280e80d1b60bed034854632f50e56))
* update README ([a2d14d2](https://github.com/dangeroustech/StreamDL/commit/a2d14d2b1f66b1ce806e706264df4e1e3ad47613))


### 🏭 Build

* add arm deps ([d5bfc0e](https://github.com/dangeroustech/StreamDL/commit/d5bfc0e85862147afff6510f43888dc75809f2b1))
* arm dep fix :crossed_fingers: ([ee119cf](https://github.com/dangeroustech/StreamDL/commit/ee119cfa31d28897bb67724b5a38a7f3e7280010))
* version pinning ([04ef59e](https://github.com/dangeroustech/StreamDL/commit/04ef59eb977edbbe445158923383693d82efdc3f))


### 🤖 CI/CD

* actually clone repo ([a09dec5](https://github.com/dangeroustech/StreamDL/commit/a09dec5690a64d790c9416c13c08dc629bfb4bef))
* add staging build push ([f642de3](https://github.com/dangeroustech/StreamDL/commit/f642de34c2725bf297ef4c8e64a0ad1367573684))
* bump build to python 3.10 ([cf5df09](https://github.com/dangeroustech/StreamDL/commit/cf5df093e8153d628cdb818f4353d0433d9f753c))
* bump poetry version ([f2f80f3](https://github.com/dangeroustech/StreamDL/commit/f2f80f3c2053936f3ab967d894357a67e280414b))
* change schedule ([8e6a9a5](https://github.com/dangeroustech/StreamDL/commit/8e6a9a584ead588fd47c8c44e12064be9fca11ca))
* cleanup ([63c4a34](https://github.com/dangeroustech/StreamDL/commit/63c4a34763d21374ba3901891d15822187d9095f))
* cleanup ([f66d8b0](https://github.com/dangeroustech/StreamDL/commit/f66d8b044e47914c815d5ce318390f815782d11c))
* docker step complete ([b189308](https://github.com/dangeroustech/StreamDL/commit/b189308e92eea04c98928c677bc8570dc385b854))
* existing cleanup ([eab9fdb](https://github.com/dangeroustech/StreamDL/commit/eab9fdbe896463eb21b06aee9ad1318a315afb0d))
* fix clone ([167a556](https://github.com/dangeroustech/StreamDL/commit/167a5568ee2c36099de515789fdb35b436fee7c9))
* name tweaks ([69a631a](https://github.com/dangeroustech/StreamDL/commit/69a631a6321a6bc577156962fb42133fb967d2a4))
* no need for a matrix, only one language ([c8ec413](https://github.com/dangeroustech/StreamDL/commit/c8ec4136b4d231b9ba06e52c6559e129301af323))
* only restrict push stage ([6629905](https://github.com/dangeroustech/StreamDL/commit/662990560efea4f8a1b20fd8dfedbf7af5bcf712))
* reduce image size because cryptograph wheel ([5258860](https://github.com/dangeroustech/StreamDL/commit/525886022b9e2ff014ab07dc1130fdec27b88798))
* remove comments ([984beaf](https://github.com/dangeroustech/StreamDL/commit/984beaf6a307ad27b7f430db512f67040f46ab17))
* seriously ([02087a6](https://github.com/dangeroustech/StreamDL/commit/02087a6cb6af1b701f7e930ecc777fdcbc5d22ae))
* split build steps ([fb35570](https://github.com/dangeroustech/StreamDL/commit/fb35570866c5bd8abbb66b74f15b49034dff0e4d))
* tweak prefixes ([9dd878a](https://github.com/dangeroustech/StreamDL/commit/9dd878a28f35fb8121a9a1f3c71fb77799afec25))
* typo fix ([79d792a](https://github.com/dangeroustech/StreamDL/commit/79d792a773202d7a354feb31d8790aa845497da8))
* update codeql ([b23645b](https://github.com/dangeroustech/StreamDL/commit/b23645b0b66a05c2629e798f35492bf8c9fe2724))
* workflow replicated ([5dbbc38](https://github.com/dangeroustech/StreamDL/commit/5dbbc3823ca87477c1cb7dde3ebf27700cec9a3d))


### 🔥 Style

* add .editorconfig ([5c32e44](https://github.com/dangeroustech/StreamDL/commit/5c32e440f799433ebe9a98128cb648c8bbd67c3a))
* fix yaml ([041b872](https://github.com/dangeroustech/StreamDL/commit/041b87201f05d99519f3f3c3b8aa7112a2b5737b))
* reordering because pentantry ([98217a4](https://github.com/dangeroustech/StreamDL/commit/98217a48fc001c481b85aef345d06c33cd93d97f))
* syntax ([be1d365](https://github.com/dangeroustech/StreamDL/commit/be1d3651e037a2500a0649ba938b162b4097b685))


### ✍ Chore

* add local ignore files ([a0c6e24](https://github.com/dangeroustech/StreamDL/commit/a0c6e24ce510009b23be6ba2f161417c1a1d803d))
* **deps-dev:** bump pylint from 2.9.6 to 2.10.2 ([3d9f7e9](https://github.com/dangeroustech/StreamDL/commit/3d9f7e94ac1a494bc09d2a072ffe038d79318538))
* **deps-dev:** bump pytest from 6.2.4 to 6.2.5 ([1a2fc96](https://github.com/dangeroustech/StreamDL/commit/1a2fc9693032756b0f32f95f516d9fd8cb944248))
* **deps:** bump streamlink from 2.2.0 to 2.4.0 ([420cf9e](https://github.com/dangeroustech/StreamDL/commit/420cf9ea6cf17dfd39f5b7fee7ef536e468a7ec1))
* update readme and badge name ([8ff2cb7](https://github.com/dangeroustech/StreamDL/commit/8ff2cb77221242e032b44a9f4358a34f469978fe))


### 🐛 Bug Fixes

* add versioning to CI ([d7037a0](https://github.com/dangeroustech/StreamDL/commit/d7037a08aa4a960463f529ca9dd3e049665a5536))
* ci: correct push 'if' ([4b38d3f](https://github.com/dangeroustech/StreamDL/commit/4b38d3fd1922420848701c88f0db560d1b5a84f9))
* update deps and bump to python 3.9 ([c6140a7](https://github.com/dangeroustech/StreamDL/commit/c6140a77828bc98e748f029f82a0d87051616a8a))
* whoops ([8e9509d](https://github.com/dangeroustech/StreamDL/commit/8e9509d7414792a0a649c5dc87ee6773554ddd51))

### [1.2.4](https://github.com/dangeroustech/StreamDL/compare/v1.2.3...v1.2.4) (2020-04-16)

### [1.2.1](https://github.com/dangeroustech/StreamDL/compare/v1.2.0...v1.2.1) (2019-11-07)

## [1.1.0](https://github.com/dangeroustech/StreamDL/compare/v1.0.0...v1.1.0) (2019-10-23)

