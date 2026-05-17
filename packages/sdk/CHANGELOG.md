# zerithdb-sdk

## [0.1.0](https://github.com/Kapil6996/ZerithDB/compare/zerithdb-sdk-v0.0.1...zerithdb-sdk-v0.1.0) (2026-05-17)


### Features

* add centralized Logger utility with level support ([#440](https://github.com/Kapil6996/ZerithDB/issues/440)) ([0be4a05](https://github.com/Kapil6996/ZerithDB/commit/0be4a0593a87860d203746cded639f28ac8762fa))
* add polling transport fallback ([8c9ad5d](https://github.com/Kapil6996/ZerithDB/commit/8c9ad5d38ecd873bd9878ebcb3d4056dbccdf0df))
* **devtools:** memory usage visualizer for IndexedDB and WebRTC ([#511](https://github.com/Kapil6996/ZerithDB/issues/511)) ([febd74e](https://github.com/Kapil6996/ZerithDB/commit/febd74e395ee2e598a063d9dbad0f779e4a2c3fe))
* **network:** add graceful HTTP long-polling fallback for signaling transport ([e3ff346](https://github.com/Kapil6996/ZerithDB/commit/e3ff346eabc971c55742b70693dbae4b617748aa))
* production launch — web app, HF signaling, Python SDK, CLI ([7c655a1](https://github.com/Kapil6996/ZerithDB/commit/7c655a140c2ed34cefbcf50486e9418db2bc21f0))
* **web:** add dark mode theme toggle ([df01d38](https://github.com/Kapil6996/ZerithDB/commit/df01d38bac38e3df7d3d3ec52e8cfe841e355cff))


### Bug Fixes

* remove lint and test scripts from stub packages ([37bece9](https://github.com/Kapil6996/ZerithDB/commit/37bece9af8e97798541f74393a946e803e9e5178))
* resolve 10 bugs across sync, network, db, react, sdk, and cli packages ([#469](https://github.com/Kapil6996/ZerithDB/issues/469)) ([e357900](https://github.com/Kapil6996/ZerithDB/commit/e357900cbab5b38879c0c3b36123e3d2dc2ea8b6))
* resolve all merge conflicts with upstream/main ([313ab38](https://github.com/Kapil6996/ZerithDB/commit/313ab38e0510c41117b01dcb87abc1aef06ec3e8))
* resolve merge conflicts with upstream/main ([f449ebd](https://github.com/Kapil6996/ZerithDB/commit/f449ebd68f3f7caacaa04021d10eea4930050230))
* **sdk:** handle missing IndexedDB gracefully ([3b1ac9d](https://github.com/Kapil6996/ZerithDB/commit/3b1ac9dc3c6dc5a84aee67dfc5ea5196cc393dc8))
* **sdk:** handle missing IndexedDB gracefully ([fedbaf2](https://github.com/Kapil6996/ZerithDB/commit/fedbaf2ec2b69adf75638803efc3790ae73f532d))
* **sdk:** resolve conflicts and improve indexeddb check ([de3df7f](https://github.com/Kapil6996/ZerithDB/commit/de3df7fda130d34ac5bc6c68edabea596c9ce74a))
* **sdk:** validate appId in createApp() ([#593](https://github.com/Kapil6996/ZerithDB/issues/593)) ([e9b1c88](https://github.com/Kapil6996/ZerithDB/commit/e9b1c88ccd097717916fca97a7facc4baf0251b6))
* stabilize monorepo build, fix types and missing layouts ([43bbc78](https://github.com/Kapil6996/ZerithDB/commit/43bbc78dfe4ec204fdc1afba29bdfaf9ee93174b))

## 0.2.0

### Minor Changes

- 4f1cee0: Initial Beta Release of ZerithDB ecosystem! Features include CRDT sync, local-first
  WebRTC networking, React hooks, CLI, and more.

### Patch Changes

- Updated dependencies [4f1cee0]
  - zerithdb-core@0.2.0
  - zerithdb-db@0.2.0
  - zerithdb-sync@0.2.0
  - zerithdb-network@0.2.0
  - zerithdb-auth@0.2.0
