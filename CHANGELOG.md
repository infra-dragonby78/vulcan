# Changelog

## 1.0.0 (2025-10-19)


### ⚠ BREAKING CHANGES

* use results on fs module ([#191](https://github.com/infra-dragonby78/vulcan/issues/191))
* use custom types for Results and Error, and use error functions ([#189](https://github.com/infra-dragonby78/vulcan/issues/189))
* remove Results from json setters ([#182](https://github.com/infra-dragonby78/vulcan/issues/182))
* add results to commands ([#179](https://github.com/infra-dragonby78/vulcan/issues/179))

### Features

* add `captureReverts` to `Watcher` ([0419165](https://github.com/infra-dragonby78/vulcan/commit/041916523380e6aae2203475a371d04560c80724))
* add `fileExists` ([f64586f](https://github.com/infra-dragonby78/vulcan/commit/f64586f73c7b22ecb9f3a36d4a367ca975455b95))
* add `firstCall` and `lastCall` ([d35275e](https://github.com/infra-dragonby78/vulcan/commit/d35275eb3b52bf860a3207f9a5027e6d2390a00a))
* add `firstCall` and `lastCall` to `Vulcan` ([f421cc6](https://github.com/infra-dragonby78/vulcan/commit/f421cc61a88de978521405445f2d81edf0ed28d5))
* add `reset` to `Watcher` ([b0b1c93](https://github.com/infra-dragonby78/vulcan/commit/b0b1c938c26f3212cc297386b041b6d79f562772))
* add `stopWatch` to `Vulcan` ([5958f3f](https://github.com/infra-dragonby78/vulcan/commit/5958f3fcd57daa5f3c499a738d87728acee540f8))
* Add `toString` method to commands ([6398e44](https://github.com/infra-dragonby78/vulcan/commit/6398e4450bda1878622bdaf3f4a36af1401981b4))
* add abbreviations ([bbdf0d1](https://github.com/infra-dragonby78/vulcan/commit/bbdf0d1735dbb8c53db4a67bd1fd04b12bd85900))
* add basic types to pointer casting ([#198](https://github.com/infra-dragonby78/vulcan/issues/198)) ([8fc756a](https://github.com/infra-dragonby78/vulcan/commit/8fc756a1a802cb3fa4685a0e0d237b5355b01dc0))
* add createAddress function ([a0364aa](https://github.com/infra-dragonby78/vulcan/commit/a0364aab9b385863424c3258ecf79fb5f6d95ced))
* add disableCaptureReverts ([a0f5971](https://github.com/infra-dragonby78/vulcan/commit/a0f5971ba2a521cb99aacfa21aec891e3d299f76))
* add function to calculate deployment addresses ([3476166](https://github.com/infra-dragonby78/vulcan/commit/3476166ad6cc73a9745943da4af7dfdda6437a59))
* add function to create empty command ([80a9d64](https://github.com/infra-dragonby78/vulcan/commit/80a9d641e81d19cdfadd379e3765a78276b84141))
* add function to parse format string ([e65c00c](https://github.com/infra-dragonby78/vulcan/commit/e65c00c4828a839dc546e5d046e2c8aaae1b4204))
* add functions to update token balances ([eca9f3f](https://github.com/infra-dragonby78/vulcan/commit/eca9f3fa509299d366dc13870a548a44cf130a9d))
* add gas module ([0399009](https://github.com/infra-dragonby78/vulcan/commit/0399009ca28b3132021f79d5b2ebd075913ab74e))
* add message to expect utilities ([#231](https://github.com/infra-dragonby78/vulcan/issues/231)) ([f582d66](https://github.com/infra-dragonby78/vulcan/commit/f582d665533bf8af67383c377d0eaa5e33d6d2fb))
* add missing forge-std functions ([88f4660](https://github.com/infra-dragonby78/vulcan/commit/88f4660d9a0d22ff11cb0bb888be7f8c90406aff))
* add placeholder struct ([10c028d](https://github.com/infra-dragonby78/vulcan/commit/10c028de658b5ccdf0c917151ded5ff00d3de7cb))
* add results to commands ([#179](https://github.com/infra-dragonby78/vulcan/issues/179)) ([33a9eaa](https://github.com/infra-dragonby78/vulcan/commit/33a9eaa04ff402f8fa23ee9eedfc57ef55074d4b))
* add semver module ([#204](https://github.com/infra-dragonby78/vulcan/issues/204)) ([5e0fc85](https://github.com/infra-dragonby78/vulcan/commit/5e0fc8574733eb6478cbf4ec48b0d69688b72bfa))
* add toHaveRevertedWith ([0f59978](https://github.com/infra-dragonby78/vulcan/commit/0f5997850af7fbf3f5aa51db680193cb6b48ca27))
* adds the `setGrasPrice` method without Context ([0374790](https://github.com/infra-dragonby78/vulcan/commit/037479066da69c2f22accb1222b6a8b393ec1070))
* adds the `setPrevrandao` method without context ([9e88db2](https://github.com/infra-dragonby78/vulcan/commit/9e88db2ce3bc494d0f2d4e672d5f73e62008e0ea))
* config module ([2dc01aa](https://github.com/infra-dragonby78/vulcan/commit/2dc01aa687599c8f95280a45c9dcf72aed12e351))
* export Command struct from script.sol ([d9980a3](https://github.com/infra-dragonby78/vulcan/commit/d9980a3391f4ed9631ae523c092023abd3b01148))
* extend address to have calls ([20f9072](https://github.com/infra-dragonby78/vulcan/commit/20f90725571b4f7a143b5fcae526424f58713b1a))
* improved json validation using Results ([#178](https://github.com/infra-dragonby78/vulcan/issues/178)) ([0da5329](https://github.com/infra-dragonby78/vulcan/commit/0da5329136c30369757fd0db4dfb110a55a8aa91))
* install forge-std@v1.7.6 ([c92f971](https://github.com/infra-dragonby78/vulcan/commit/c92f97112e72eb891784f5fc8e18c9b05dc72d95))
* new project structure ([#220](https://github.com/infra-dragonby78/vulcan/issues/220)) ([685bd68](https://github.com/infra-dragonby78/vulcan/commit/685bd68579908f5661e4d6c193d913ef9e57fd05))
* refactor structure ([7f4fc4c](https://github.com/infra-dragonby78/vulcan/commit/7f4fc4c7582030aa3bc557ae996b5a85cdc04ea7))
* remove Results from json setters ([#182](https://github.com/infra-dragonby78/vulcan/issues/182)) ([4a0980f](https://github.com/infra-dragonby78/vulcan/commit/4a0980f35e253342fa29ec0387468738c1b171e1))
* replace struct storage with mapping ([b154360](https://github.com/infra-dragonby78/vulcan/commit/b154360d82d55972aa99730f962a9676c23a77ef))
* request module ([#174](https://github.com/infra-dragonby78/vulcan/issues/174)) ([d7e628f](https://github.com/infra-dragonby78/vulcan/commit/d7e628f73a3c15ae887ae1595314622230b1d462))
* rpc module ([#236](https://github.com/infra-dragonby78/vulcan/issues/236)) ([ea4f4cc](https://github.com/infra-dragonby78/vulcan/commit/ea4f4ccd1e36c42a2ee6733f2f20e0c15df8ff2b))
* store all call results ([98d6a6a](https://github.com/infra-dragonby78/vulcan/commit/98d6a6a48a1fe2455fc6c1fd1d08cc86b6881934))
* string to json ([#238](https://github.com/infra-dragonby78/vulcan/issues/238)) ([5e65215](https://github.com/infra-dragonby78/vulcan/commit/5e65215448ad9333bbb3ddd2089cde3f2a363e89))
* update forge-std ([#240](https://github.com/infra-dragonby78/vulcan/issues/240)) ([03997aa](https://github.com/infra-dragonby78/vulcan/commit/03997aadc0fde3563e6d631b589f308284e61437))
* update forge-std to v1.7.3 ([a3dfd06](https://github.com/infra-dragonby78/vulcan/commit/a3dfd069e40200df9af940120e4f921245dced19))
* update Vulcan.watch to return watcher ([cfbb4d1](https://github.com/infra-dragonby78/vulcan/commit/cfbb4d14d6397e1650f6b8c06935af3d083e5085))
* use `serializeJson` cheatcode ([#196](https://github.com/infra-dragonby78/vulcan/issues/196)) ([359c1bd](https://github.com/infra-dragonby78/vulcan/commit/359c1bd950dd38dc35ce97908bb9df8614663ef3))
* use custom types for Results and Error, and use error functions ([#189](https://github.com/infra-dragonby78/vulcan/issues/189)) ([d3b23d4](https://github.com/infra-dragonby78/vulcan/commit/d3b23d4c14332112596520de6c86a334fcf72c57))
* use forge-std@705263c ([#195](https://github.com/infra-dragonby78/vulcan/issues/195)) ([bacef6c](https://github.com/infra-dragonby78/vulcan/commit/bacef6ce2d56a2a59bdfe8b42826f76fe16bb165))
* use results on fs module ([#191](https://github.com/infra-dragonby78/vulcan/issues/191)) ([ff4e811](https://github.com/infra-dragonby78/vulcan/commit/ff4e811c34ce099b61d91f2e14bcb59e11ed4322))
* watchers namespace ([b287aa0](https://github.com/infra-dragonby78/vulcan/commit/b287aa051fc3da47f6a8015ceb95d7e45b828ba0))
* wrapped address ([5adbe17](https://github.com/infra-dragonby78/vulcan/commit/5adbe17416339280edea44d37c7f4756ba9c9fdc))


### Bug Fixes

* adapt to new forge-std Vm to remove warnings ([4e2d92d](https://github.com/infra-dragonby78/vulcan/commit/4e2d92d9db6e9dfbd537239fbe6390c00d55e5c5))
* add events to watchers docs ([bd42d21](https://github.com/infra-dragonby78/vulcan/commit/bd42d21bb9e7d13e958f0ad759a82d9068356c6a))
* add missing imports on script.sol ([#212](https://github.com/infra-dragonby78/vulcan/issues/212)) ([2cc7b95](https://github.com/infra-dragonby78/vulcan/commit/2cc7b9519a5556a9156e12fd8a588fdb0420d187))
* fix `firstCall` and `lastCall` on `Vulcan` ([8d799a5](https://github.com/infra-dragonby78/vulcan/commit/8d799a511732cda870ea57a9592c0366d300e6bf))
* fix cast abi-encode command ([#226](https://github.com/infra-dragonby78/vulcan/issues/226)) ([11e62a5](https://github.com/infra-dragonby78/vulcan/commit/11e62a57ee30a5f7c3720a6c9cd7792f1d3e376c))
* fix decimal format ([9e4ab75](https://github.com/infra-dragonby78/vulcan/commit/9e4ab7506f8137408b571ac1564ae645fba40fbb))
* fix disableCaptureReverts ([bc7dcd1](https://github.com/infra-dragonby78/vulcan/commit/bc7dcd104eaf4d2498295ebc31e2f98f88a41da2))
* fix docs ([fcae224](https://github.com/infra-dragonby78/vulcan/commit/fcae224bcb39b86eeb5c069dd51316703fedae4d))
* fix docstring ([af87691](https://github.com/infra-dragonby78/vulcan/commit/af8769130c3c4423267a683a335477906ef010aa))
* fix docstring ([3f6bb3e](https://github.com/infra-dragonby78/vulcan/commit/3f6bb3e7ac7d469c38fedb591aaa38d17d218eba))
* fix docstring ([6bff42f](https://github.com/infra-dragonby78/vulcan/commit/6bff42fab6a2153e40e06dca8cad54286fe765bb))
* fix docstrings ([c6533ee](https://github.com/infra-dragonby78/vulcan/commit/c6533ee97f50915ced54142cbba070cd87225f5e))
* fix expect logs ([4c362a0](https://github.com/infra-dragonby78/vulcan/commit/4c362a06670ac0b1a76cffabefd457b7f1f625db))
* fix expect revert tests ([ea704c5](https://github.com/infra-dragonby78/vulcan/commit/ea704c535ed20122cbc2a34641417fb5cf51fa5e))
* fix file exists ([#228](https://github.com/infra-dragonby78/vulcan/issues/228)) ([c07dd48](https://github.com/infra-dragonby78/vulcan/commit/c07dd48feb4cb310406e0c33ea04d8a59818cd5e))
* fix import ([94bc483](https://github.com/infra-dragonby78/vulcan/commit/94bc483770a296341296485f6ee3b76d45bcd6bc))
* fix indentation ([246766a](https://github.com/infra-dragonby78/vulcan/commit/246766a68f63ce0ca811eb4b8205b53e0772a3f5))
* fix loop ([b99586d](https://github.com/infra-dragonby78/vulcan/commit/b99586d7f453bbc559eb11b6551b7e09dacc0fcb))
* fix merge ([e1de89a](https://github.com/infra-dragonby78/vulcan/commit/e1de89a93ae74dc6815190173c55c91dcd4482cb))
* fix return natspect documentation ([de6c54e](https://github.com/infra-dragonby78/vulcan/commit/de6c54ef424e75882012e44114fe3a56b8f74b90))
* fix stack too deep error ([22de084](https://github.com/infra-dragonby78/vulcan/commit/22de0845f0029147666f0d6a82f63a9f62475143))
* fix start and end ([f765e69](https://github.com/infra-dragonby78/vulcan/commit/f765e69fce19ab6b00a8bd28ae48543ac102f297))
* fix warning ([f7a0cd2](https://github.com/infra-dragonby78/vulcan/commit/f7a0cd27d69c20991b9500f46e90efb45bd940e6))
* remove duplicated check ([1f537e8](https://github.com/infra-dragonby78/vulcan/commit/1f537e8415a9de2e18acfeec9b63a80c9c44eaa7))
* remove isStaticCall example ([7282987](https://github.com/infra-dragonby78/vulcan/commit/7282987e0b5ff13aca0347ca488284767978cee7))
* remove selfdestruct ([a8d304a](https://github.com/infra-dragonby78/vulcan/commit/a8d304a277957104067bf2888fd1f1e5a0f14d6f))
* remove some warnings ([140e5c7](https://github.com/infra-dragonby78/vulcan/commit/140e5c71070866eaacc1dedd3292f9a1728ab575))
* remove warnings ([1c2c429](https://github.com/infra-dragonby78/vulcan/commit/1c2c429e3e225114c6f91604eef1142d4b50f9ef))
* remove warnings ([f7502ee](https://github.com/infra-dragonby78/vulcan/commit/f7502ee082232f6cbc8619a10f81c715b42bd3c0))
* set watcher code to empty on stop ([b575ad2](https://github.com/infra-dragonby78/vulcan/commit/b575ad26b17fa6e0b814d67516f1ae7a1d62c20b))
* shorter comments ([1fadecc](https://github.com/infra-dragonby78/vulcan/commit/1fadecccdd58ffd8376b6a698db4629ef1c62276))
* swap write/read ([aaaa778](https://github.com/infra-dragonby78/vulcan/commit/aaaa7788884a0dd310654168b9131ad2479677e0))
* tabs ([024e179](https://github.com/infra-dragonby78/vulcan/commit/024e179892a4c63749f7a7a6bebc852f89feed48))
* typo ([506996a](https://github.com/infra-dragonby78/vulcan/commit/506996a9472e71acc804d6660624bdd9e1acaf85))
* update code examples ([4e342f5](https://github.com/infra-dragonby78/vulcan/commit/4e342f576bd2192d911dda5287f7389dfa8fb899))
* update forge-std ([#214](https://github.com/infra-dragonby78/vulcan/issues/214)) ([c8ded50](https://github.com/infra-dragonby78/vulcan/commit/c8ded5049af3d948b960661381828393fc3ea88a))
* update import ([6d7c306](https://github.com/infra-dragonby78/vulcan/commit/6d7c306820e370cfb2990a79cd6009e339911fbf))
* use an address &gt;= 10 for setCode test ([fbc726d](https://github.com/infra-dragonby78/vulcan/commit/fbc726d516502a397b955a9b88f2f1a5843c7fea))
* use forge@v1.6.1 ([#210](https://github.com/infra-dragonby78/vulcan/issues/210)) ([a233b48](https://github.com/infra-dragonby78/vulcan/commit/a233b481c12e90c18859ae36be7170cabecb0dad))
* use shorter comments on accounts ([1818f58](https://github.com/infra-dragonby78/vulcan/commit/1818f585d7f353cf51a3bcaaa0d75832b7d35a8c))
* use try/catch on `stopPrank` ([cfcc1c5](https://github.com/infra-dragonby78/vulcan/commit/cfcc1c563e159b54f1605c11114d097068eb670b))

## [0.4.7](https://github.com/nomoixyz/vulcan/compare/v0.4.6...v0.4.7) (2024-02-23)


### Features

* install forge-std@v1.7.6 ([6a102f5](https://github.com/nomoixyz/vulcan/commit/6a102f5f99c11f923e70cf40be1c70dc50953cb9))
* string to json ([#238](https://github.com/nomoixyz/vulcan/issues/238)) ([f67740f](https://github.com/nomoixyz/vulcan/commit/f67740f8a9c846a543aebf29433ad69c3f0ff337))
* update forge-std ([#240](https://github.com/nomoixyz/vulcan/issues/240)) ([943b0d3](https://github.com/nomoixyz/vulcan/commit/943b0d33b0111caf18fae3594f1ca89e925bac58))

## [0.4.6](https://github.com/nomoixyz/vulcan/compare/v0.4.5...v0.4.6) (2023-11-27)


### Features

* rpc module ([#236](https://github.com/nomoixyz/vulcan/issues/236)) ([d02a2ac](https://github.com/nomoixyz/vulcan/commit/d02a2ac5cb8bf3d64e014d8a55ab2f475712c65b))
* update forge-std to v1.7.3 ([95ce186](https://github.com/nomoixyz/vulcan/commit/95ce1863037a91a7c8db5f9d631ecc625243f4c9))

## [0.4.5](https://github.com/nomoixyz/vulcan/compare/v0.4.4...v0.4.5) (2023-11-07)


### Features

* add message to expect utilities ([#231](https://github.com/nomoixyz/vulcan/issues/231)) ([7e0754a](https://github.com/nomoixyz/vulcan/commit/7e0754a8c6e5e21852895d5dd5981b4a794f0b9b))

## [0.4.4](https://github.com/nomoixyz/vulcan/compare/v0.4.3...v0.4.4) (2023-11-07)


### Bug Fixes

* fix file exists ([#228](https://github.com/nomoixyz/vulcan/issues/228)) ([c02feb1](https://github.com/nomoixyz/vulcan/commit/c02feb19aa34449376f52805663414aefafdc06a))

## [0.4.3](https://github.com/nomoixyz/vulcan/compare/v0.4.2...v0.4.3) (2023-10-26)


### Features

* new project structure ([#220](https://github.com/nomoixyz/vulcan/issues/220)) ([2d45c4c](https://github.com/nomoixyz/vulcan/commit/2d45c4c9b5072f218514997e6e656d3c2a10262e))


### Bug Fixes

* fix cast abi-encode command ([#226](https://github.com/nomoixyz/vulcan/issues/226)) ([b340aaf](https://github.com/nomoixyz/vulcan/commit/b340aafad4b2efcdb4d0c983ee6d02c79c1c1dea))

## [0.4.2](https://github.com/nomoixyz/vulcan/compare/v0.4.1...v0.4.2) (2023-10-10)


### Bug Fixes

* update forge-std ([#214](https://github.com/nomoixyz/vulcan/issues/214)) ([8e3fb60](https://github.com/nomoixyz/vulcan/commit/8e3fb600b34b8ece7e2ff43b2f59ce01919ad611))

## [0.4.1](https://github.com/nomoixyz/vulcan/compare/v0.4.0...v0.4.1) (2023-10-03)


### Bug Fixes

* add missing imports on script.sol ([#212](https://github.com/nomoixyz/vulcan/issues/212)) ([294c9d9](https://github.com/nomoixyz/vulcan/commit/294c9d9079b8d0045bbe2b33e7021665c6e0fe53))
* use forge@v1.6.1 ([#210](https://github.com/nomoixyz/vulcan/issues/210)) ([bda8bf0](https://github.com/nomoixyz/vulcan/commit/bda8bf0df6daf609ec03bae7ebbaed099438a396))

## [0.4.0](https://github.com/nomoixyz/vulcan/compare/v0.3.1...v0.4.0) (2023-10-02)


### ⚠ BREAKING CHANGES

* use results on fs module ([#191](https://github.com/nomoixyz/vulcan/issues/191))
* use custom types for Results and Error, and use error functions ([#189](https://github.com/nomoixyz/vulcan/issues/189))
* remove Results from json setters ([#182](https://github.com/nomoixyz/vulcan/issues/182))
* add results to commands ([#179](https://github.com/nomoixyz/vulcan/issues/179))

### Features

* add basic types to pointer casting ([#198](https://github.com/nomoixyz/vulcan/issues/198)) ([5f96f7b](https://github.com/nomoixyz/vulcan/commit/5f96f7b254c12684e579666a7a05f8bce7a3afce))
* add results to commands ([#179](https://github.com/nomoixyz/vulcan/issues/179)) ([9770c9e](https://github.com/nomoixyz/vulcan/commit/9770c9ef2f58c638a4d25c33487cee5bf11ce103))
* add semver module ([#204](https://github.com/nomoixyz/vulcan/issues/204)) ([b4a687b](https://github.com/nomoixyz/vulcan/commit/b4a687b1fd2d6d355e11bf4581ef1cc7fb2bec27))
* improved json validation using Results ([#178](https://github.com/nomoixyz/vulcan/issues/178)) ([50b1d14](https://github.com/nomoixyz/vulcan/commit/50b1d14439866ac1cf76a4be959b5631184c88aa))
* remove Results from json setters ([#182](https://github.com/nomoixyz/vulcan/issues/182)) ([6a601ae](https://github.com/nomoixyz/vulcan/commit/6a601ae623a3aa6c84b42270636c2d46ef630ba6))
* request module ([#174](https://github.com/nomoixyz/vulcan/issues/174)) ([63b58b4](https://github.com/nomoixyz/vulcan/commit/63b58b4803d50ad62e131ba344046bb054adb52f))
* use `serializeJson` cheatcode ([#196](https://github.com/nomoixyz/vulcan/issues/196)) ([6a90b1b](https://github.com/nomoixyz/vulcan/commit/6a90b1bea3a14b87c59ddf8edc2721d463b43d22))
* use custom types for Results and Error, and use error functions ([#189](https://github.com/nomoixyz/vulcan/issues/189)) ([4e69e1c](https://github.com/nomoixyz/vulcan/commit/4e69e1cd7f9beadcfead37fafc0d0ea5ee37599f))
* use forge-std@705263c ([#195](https://github.com/nomoixyz/vulcan/issues/195)) ([392d99e](https://github.com/nomoixyz/vulcan/commit/392d99e4525c642cae1da577e274326fcefa4de2))
* use results on fs module ([#191](https://github.com/nomoixyz/vulcan/issues/191)) ([f2998a1](https://github.com/nomoixyz/vulcan/commit/f2998a1821132d9fbb8fda8ef807de61d6dc0bf3))

## [0.3.1](https://github.com/nomoixyz/vulcan/compare/v0.3.0...v0.3.1) (2023-09-01)


### Bug Fixes

* adapt to new forge-std Vm to remove warnings ([e83ebd4](https://github.com/nomoixyz/vulcan/commit/e83ebd403e1e46d3cbf684343e967478bf0a8e29))

## [0.3.0](https://github.com/nomoixyz/vulcan/compare/v0.2.0...v0.3.0) (2023-09-01)


### Features

* add function to create empty command ([2c31886](https://github.com/nomoixyz/vulcan/commit/2c31886075fae5a5177410739309ff38ed834f2a))
* export Command struct from script.sol ([c88883a](https://github.com/nomoixyz/vulcan/commit/c88883a402ccfae6aa2d0de674936ba22e3d3514))


### Bug Fixes

* fix return natspect documentation ([5da4ad1](https://github.com/nomoixyz/vulcan/commit/5da4ad14fbe07b35d29260fe2cb97ffb2cb95de3))
* tabs ([1d4c0b9](https://github.com/nomoixyz/vulcan/commit/1d4c0b9d350445825d84198c7b242f5e432ffb39))
* update code examples ([953d661](https://github.com/nomoixyz/vulcan/commit/953d661e1a84e84b9a40b8f8178980ea32d0ef96))
