# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [1.1.40](https://github.com/thi-ng/umbrella/compare/@thi.ng/iges@1.1.39...@thi.ng/iges@1.1.40) (2020-07-17)

**Note:** Version bump only for package @thi.ng/iges





## [1.1.39](https://github.com/thi-ng/umbrella/compare/@thi.ng/iges@1.1.38...@thi.ng/iges@1.1.39) (2020-07-08)

**Note:** Version bump only for package @thi.ng/iges





## [1.1.38](https://github.com/thi-ng/umbrella/compare/@thi.ng/iges@1.1.37...@thi.ng/iges@1.1.38) (2020-07-08)

**Note:** Version bump only for package @thi.ng/iges





## [1.1.37](https://github.com/thi-ng/umbrella/compare/@thi.ng/iges@1.1.36...@thi.ng/iges@1.1.37) (2020-07-04)

**Note:** Version bump only for package @thi.ng/iges





## [1.1.36](https://github.com/thi-ng/umbrella/compare/@thi.ng/iges@1.1.35...@thi.ng/iges@1.1.36) (2020-07-02)

**Note:** Version bump only for package @thi.ng/iges





## [1.1.35](https://github.com/thi-ng/umbrella/compare/@thi.ng/iges@1.1.34...@thi.ng/iges@1.1.35) (2020-06-20)

**Note:** Version bump only for package @thi.ng/iges





## [1.1.34](https://github.com/thi-ng/umbrella/compare/@thi.ng/iges@1.1.33...@thi.ng/iges@1.1.34) (2020-06-14)

**Note:** Version bump only for package @thi.ng/iges





## [1.1.33](https://github.com/thi-ng/umbrella/compare/@thi.ng/iges@1.1.32...@thi.ng/iges@1.1.33) (2020-06-01)

**Note:** Version bump only for package @thi.ng/iges





## [1.1.32](https://github.com/thi-ng/umbrella/compare/@thi.ng/iges@1.1.31...@thi.ng/iges@1.1.32) (2020-06-01)

**Note:** Version bump only for package @thi.ng/iges





## [1.1.31](https://github.com/thi-ng/umbrella/compare/@thi.ng/iges@1.1.30...@thi.ng/iges@1.1.31) (2020-05-29)

**Note:** Version bump only for package @thi.ng/iges





# [1.1.0](https://github.com/thi-ng/umbrella/compare/@thi.ng/iges@1.0.15...@thi.ng/iges@1.1.0) (2019-04-15)

### Features

* **iges:** add boolean tree, csg box & cylinder entities ([b1db275](https://github.com/thi-ng/umbrella/commit/b1db275))
* **iges:** add new entities, options, extract addEntity, update enums ([43426e5](https://github.com/thi-ng/umbrella/commit/43426e5))

## [1.0.14](https://github.com/thi-ng/umbrella/compare/@thi.ng/iges@1.0.13...@thi.ng/iges@1.0.14) (2019-04-02)

### Bug Fixes

* **iges:** TS3.4 type inference ([34eab59](https://github.com/thi-ng/umbrella/commit/34eab59))

# [1.0.0](https://github.com/thi-ng/umbrella/compare/@thi.ng/iges@0.2.30...@thi.ng/iges@1.0.0) (2019-01-21)

### Build System

* update package build scripts & outputs, imports in ~50 packages ([b54b703](https://github.com/thi-ng/umbrella/commit/b54b703))

### BREAKING CHANGES

* enabled multi-outputs (ES6 modules, CJS, UMD)

- build scripts now first build ES6 modules in package root, then call
  `scripts/bundle-module` to build minified CJS & UMD bundles in `/lib`
- all imports MUST be updated to only refer to package level
  (not individual files anymore). tree shaking in user land will get rid of
  all unused imported symbols.

<a name="0.2.5"></a>
## [0.2.5](https://github.com/thi-ng/umbrella/compare/@thi.ng/iges@0.2.4...@thi.ng/iges@0.2.5) (2018-08-24)

### Bug Fixes

* **iges:** regression to due transducers update ([78d0a84](https://github.com/thi-ng/umbrella/commit/78d0a84))

<a name="0.2.0"></a>
# [0.2.0](https://github.com/thi-ng/umbrella/compare/@thi.ng/iges@0.1.4...@thi.ng/iges@0.2.0) (2018-08-01)

### Features

* **iges:** add PolylineMode enum, update addPolyline2d() ([f7a084a](https://github.com/thi-ng/umbrella/commit/f7a084a))

<a name="0.1.0"></a>
# 0.1.0 (2018-07-12)

### Features

* **iges:** re-import & update IGES exporter (via MBP2010) ([7f1b2d4](https://github.com/thi-ng/umbrella/commit/7f1b2d4))
