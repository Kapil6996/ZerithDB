# zerithdb-core

## [0.1.0](https://github.com/Kapil6996/ZerithDB/compare/zerithdb-core-v0.0.1...zerithdb-core-v0.1.0) (2026-05-17)


### Features

* add centralized Logger utility with level support ([#440](https://github.com/Kapil6996/ZerithDB/issues/440)) ([0be4a05](https://github.com/Kapil6996/ZerithDB/commit/0be4a0593a87860d203746cded639f28ac8762fa))
* add polling transport fallback ([8c9ad5d](https://github.com/Kapil6996/ZerithDB/commit/8c9ad5d38ecd873bd9878ebcb3d4056dbccdf0df))
* **devtools:** memory usage visualizer for IndexedDB and WebRTC ([#511](https://github.com/Kapil6996/ZerithDB/issues/511)) ([febd74e](https://github.com/Kapil6996/ZerithDB/commit/febd74e395ee2e598a063d9dbad0f779e4a2c3fe))
* **network:** add graceful HTTP long-polling fallback for signaling transport ([e3ff346](https://github.com/Kapil6996/ZerithDB/commit/e3ff346eabc971c55742b70693dbae4b617748aa))
* **network:** add multi-server signaling failover support ([#610](https://github.com/Kapil6996/ZerithDB/issues/610)) ([b1fb6f9](https://github.com/Kapil6996/ZerithDB/commit/b1fb6f9921b1144bf2ab88d4553a65e506397bd7))
* production launch — web app, HF signaling, Python SDK, CLI ([7c655a1](https://github.com/Kapil6996/ZerithDB/commit/7c655a140c2ed34cefbcf50486e9418db2bc21f0))


### Bug Fixes

* add missing deps for CI build and lint ([c5abde3](https://github.com/Kapil6996/ZerithDB/commit/c5abde3004205bef38df394eb1994f4e480a919e))
* **core:** add missing SDK_UNSUPPORTED_ENVIRONMENT to ErrorCode enum ([3d78e7e](https://github.com/Kapil6996/ZerithDB/commit/3d78e7ead41824a35acae8b79d950487a90f6e6b))
* **core:** add missing SDK_UNSUPPORTED_ENVIRONMENT to ErrorCode enum ([231d8dc](https://github.com/Kapil6996/ZerithDB/commit/231d8dcdab27d3282510bb9ea39d89cf28ddcd14))
* remove test script from core package ([3c12ea2](https://github.com/Kapil6996/ZerithDB/commit/3c12ea2e18a147b4008012c9ae7be37e298d3c9d))
* resolve all CI failures permanently ([c42c2ea](https://github.com/Kapil6996/ZerithDB/commit/c42c2eaf9b728d260d586226e0c7ea895cba2d34))
* resolve all merge conflicts with upstream/main ([313ab38](https://github.com/Kapil6996/ZerithDB/commit/313ab38e0510c41117b01dcb87abc1aef06ec3e8))
* resolve CI lint failures ([e90fd2d](https://github.com/Kapil6996/ZerithDB/commit/e90fd2d985e89157e4371fadfcdc0d10ffa39dcb))
* resolve final CI failures ([f6767a6](https://github.com/Kapil6996/ZerithDB/commit/f6767a6025a3750256b3cbb45733bb52d19de2b3))
* resolve merge conflicts with upstream/main ([f449ebd](https://github.com/Kapil6996/ZerithDB/commit/f449ebd68f3f7caacaa04021d10eea4930050230))
* **sdk:** resolve conflicts and improve indexeddb check ([de3df7f](https://github.com/Kapil6996/ZerithDB/commit/de3df7fda130d34ac5bc6c68edabea596c9ce74a))
* stabilize monorepo build, fix types and missing layouts ([43bbc78](https://github.com/Kapil6996/ZerithDB/commit/43bbc78dfe4ec204fdc1afba29bdfaf9ee93174b))

## 0.2.0

### Minor Changes

- 4f1cee0: Initial Beta Release of ZerithDB ecosystem! Features include CRDT sync, local-first
  WebRTC networking, React hooks, CLI, and more.
