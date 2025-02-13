# [2.2.0](https://github.com/danielwaltz/vite-plugin-graphql-codegen/compare/v2.1.1...v2.2.0) (2022-08-25)


### Features

* make commonjs the default with esm definitions ([df9e437](https://github.com/danielwaltz/vite-plugin-graphql-codegen/commit/df9e4374bf318ff4b9beddd76e0271820de3078d))

## [2.1.1](https://github.com/danielwaltz/vite-plugin-graphql-codegen/compare/v2.1.0...v2.1.1) (2022-08-25)


### Bug Fixes

* fix package exports path ([d519d15](https://github.com/danielwaltz/vite-plugin-graphql-codegen/commit/d519d156f999613a3b128ee68270fb9ee880994e))

# [2.1.0](https://github.com/danielwaltz/vite-plugin-graphql-codegen/compare/v2.0.1...v2.1.0) (2022-08-25)


### Bug Fixes

* Changes package.json to module ([386a875](https://github.com/danielwaltz/vite-plugin-graphql-codegen/commit/386a875c4703f0c32daf139365567ae1d071e32a))


### Features

* Adds schema to the isGraphQLDocument check ([76ae403](https://github.com/danielwaltz/vite-plugin-graphql-codegen/commit/76ae403afe58e02f315aa4141af7c93d44a75032))

## [2.0.1](https://github.com/danielwaltz/vite-plugin-graphql-codegen/compare/v2.0.0...v2.0.1) (2022-08-24)


### Bug Fixes

* add default export for commonjs ([c93263f](https://github.com/danielwaltz/vite-plugin-graphql-codegen/commit/c93263f118a249f8fc9f3f9bb0ea3d4bf02d2e0e)), closes [#4](https://github.com/danielwaltz/vite-plugin-graphql-codegen/issues/4)
* remove gap in debug log output ([a75a820](https://github.com/danielwaltz/vite-plugin-graphql-codegen/commit/a75a820e1daa376396466b1618085fdf047f7d87))

# [2.0.0](https://github.com/danielwaltz/vite-plugin-graphql-codegen/compare/v1.8.3...v2.0.0) (2022-08-11)


### Features

* update debug log output to match vite 3 ([c33bba7](https://github.com/danielwaltz/vite-plugin-graphql-codegen/commit/c33bba7e351ecb1fc09f015e949d539b3c804f26))
* use vite dev server restart function ([b413156](https://github.com/danielwaltz/vite-plugin-graphql-codegen/commit/b4131565f28a785a460b1c19385e9cd41d1252fb))


### BREAKING CHANGES

* Requires vite version 2.7 or greater

## [1.8.3](https://github.com/danielwaltz/vite-plugin-graphql-codegen/compare/v1.8.2...v1.8.3) (2022-08-11)


### Bug Fixes

* switch to npm and refresh packages ([be95d72](https://github.com/danielwaltz/vite-plugin-graphql-codegen/commit/be95d72e51c7eb907bab31ed08671ad0ac451c9c))

## [1.8.2](https://github.com/danielwaltz/vite-plugin-graphql-codegen/compare/v1.8.1...v1.8.2) (2022-08-11)


### Bug Fixes

* configure semantic release to release dist ([cfc1954](https://github.com/danielwaltz/vite-plugin-graphql-codegen/commit/cfc195413cfedf4e06ebcf0a84590d3e2610e27e))

## [1.8.1](https://github.com/danielwaltz/vite-plugin-graphql-codegen/compare/v1.8.0...v1.8.1) (2022-08-10)


### Bug Fixes

* normalize file paths before comparisons ([b855f0a](https://github.com/danielwaltz/vite-plugin-graphql-codegen/commit/b855f0a886505ef801dae6c05c258ea58e4e2a90))

# [1.8.0](https://github.com/danielwaltz/vite-plugin-graphql-codegen/compare/v1.7.0...v1.8.0) (2022-07-13)


### Features

* support vite 3 ([c881720](https://github.com/danielwaltz/vite-plugin-graphql-codegen/commit/c88172034685037a2d9dc2afc1ccbaa4fa03f621))

# [1.7.0](https://github.com/danielwaltz/vite-plugin-graphql-codegen/compare/v1.6.0...v1.7.0) (2022-06-10)


### Features

* support overriding config in certain modes ([97fce30](https://github.com/danielwaltz/vite-plugin-graphql-codegen/commit/97fce30fc87fdc388ce008d47760c773ba602990))

# [1.6.0](https://github.com/danielwaltz/vite-plugin-graphql-codegen/compare/v1.5.2...v1.6.0) (2022-03-18)


### Features

* Support passing manual codegen config ([e86079b](https://github.com/danielwaltz/vite-plugin-graphql-codegen/commit/e86079bce751acfa8e5b1b0f3565a7cc3f4b2514)), closes [#3](https://github.com/danielwaltz/vite-plugin-graphql-codegen/issues/3)

## [1.5.2](https://github.com/danielwaltz/vite-plugin-graphql-codegen/compare/v1.5.1...v1.5.2) (2022-02-23)


### Bug Fixes

* Make graphql a dev dependency ([e88edb1](https://github.com/danielwaltz/vite-plugin-graphql-codegen/commit/e88edb11a4042c5637c36493633e806e9f5ee919))

## [1.5.1](https://github.com/danielwaltz/vite-plugin-graphql-codegen/compare/v1.5.0...v1.5.1) (2022-02-23)


### Bug Fixes

* Fix graphql dependency ([aeb9b59](https://github.com/danielwaltz/vite-plugin-graphql-codegen/commit/aeb9b59da2e83822a71d0f827d0219eeedd295f8))

# [1.5.0](https://github.com/danielwaltz/vite-plugin-graphql-codegen/compare/v1.4.0...v1.5.0) (2022-02-10)


### Features

* Add option to override codegen config file path ([ddf9c54](https://github.com/danielwaltz/vite-plugin-graphql-codegen/commit/ddf9c5402c4d626d2e1761cd98d692c6cbda5efe)), closes [#1](https://github.com/danielwaltz/vite-plugin-graphql-codegen/issues/1)

# [1.4.0](https://github.com/danielwaltz/vite-plugin-graphql-codegen/compare/v1.3.0...v1.4.0) (2022-02-09)


### Features

* Add a debug option to aid in troubleshooting ([092398d](https://github.com/danielwaltz/vite-plugin-graphql-codegen/commit/092398db4e4a35eefc03f564f35ceb9cc7e8ffa8))

# [1.3.0](https://github.com/danielwaltz/vite-plugin-graphql-codegen/compare/v1.2.0...v1.3.0) (2022-02-01)


### Features

* Support disabling codegen in certain modes ([9c546a7](https://github.com/danielwaltz/vite-plugin-graphql-codegen/commit/9c546a799664df7877e980b3daf8353d8498fd9a))
* Support overwriting codegen config options ([4224cec](https://github.com/danielwaltz/vite-plugin-graphql-codegen/commit/4224cec993f6f7a9ca76dff4a677b9c42bb8586d))

# [1.2.0](https://github.com/danielwaltz/vite-plugin-graphql-codegen/compare/v1.1.1...v1.2.0) (2022-02-01)


### Features

* Restart vite when codegen config file changes ([24b0d0e](https://github.com/danielwaltz/vite-plugin-graphql-codegen/commit/24b0d0e6e4b1d22f40a79fd6b9e6fa5c223feba7))

## [1.1.1](https://github.com/danielwaltz/vite-plugin-graphql-codegen/compare/v1.1.0...v1.1.1) (2021-08-28)


### Bug Fixes

* Add fallback extension to preset config ([7e6b862](https://github.com/danielwaltz/vite-plugin-graphql-codegen/commit/7e6b86298640a37522c85a3d36eca8d72cab516a))
* Make documents matcher work with multiple files ([a047a37](https://github.com/danielwaltz/vite-plugin-graphql-codegen/commit/a047a3782e735eb769fc58d9e4ef7c551d338b23))

# [1.1.0](https://github.com/danielwaltz/vite-plugin-graphql-codegen/compare/v1.0.1...v1.1.0) (2021-08-28)


### Features

* Add support for near operation file preset ([18b1227](https://github.com/danielwaltz/vite-plugin-graphql-codegen/commit/18b12279629e3874edd3c691bfdede73a0a60ca4))

## [1.0.1](https://github.com/danielwaltz/vite-plugin-graphql-codegen/compare/v1.0.0...v1.0.1) (2021-08-28)


### Bug Fixes

* Add try catch on generate to keep vite running ([94e4a9b](https://github.com/danielwaltz/vite-plugin-graphql-codegen/commit/94e4a9b68460a2f3517310545b695d22ad5ad81f))
