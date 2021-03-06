# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# [3.3.0](https://github.com/webiny/webiny-js/compare/@webiny/app-page-builder@3.3.0-next.1...@webiny/app-page-builder@3.3.0) (2020-04-23)


### Bug Fixes

* add "fullUrl" field ([04807c9](https://github.com/webiny/webiny-js/commit/04807c9c7c7f6af3c0ad56fc820a277c7840efb2))
* use "fullUrl" instead of "url" ([2f60d03](https://github.com/webiny/webiny-js/commit/2f60d03fa64b88f1c43e8cdc0b725915c9c0deea))





# [3.3.0-next.1](https://github.com/webiny/webiny-js/compare/@webiny/app-page-builder@3.3.0-next.0...@webiny/app-page-builder@3.3.0-next.1) (2020-04-23)


### Bug Fixes

* add parseInt to the render plugin as well ([5ce1078](https://github.com/webiny/webiny-js/commit/5ce1078d2b0a4f8d4025605b45e16a53d5a9233f))





# [3.3.0-next.0](https://github.com/webiny/webiny-js/compare/@webiny/app-page-builder@3.2.4...@webiny/app-page-builder@3.3.0-next.0) (2020-04-23)


### Bug Fixes

* "onChange" callback passed to "renderDialog" must save data as well ([e17d3ff](https://github.com/webiny/webiny-js/commit/e17d3ff7d563d72f32992f2d96be568859c2233a))
* 🐛  Add icons as a dependency to renderGrid useCallback ([47f1ad9](https://github.com/webiny/webiny-js/commit/47f1ad9fea86427b477ed50452a8e7ef7782d383))
* make sure the sort direction value is an integer ([1cb852b](https://github.com/webiny/webiny-js/commit/1cb852bdf1f7acf08fe048e2f003421d340b68b4))
* prevent "onChange" if there's a plugin that's active ([000b503](https://github.com/webiny/webiny-js/commit/000b503343777cc25c243f2d88bf2b2edeeddde4))


### Features

* enable passing a callback to "SlateEditor" component's "onChange" function ([d38a0c0](https://github.com/webiny/webiny-js/commit/d38a0c03e5dc709ba80d72b82d9a16852b89cfdf))





## [3.2.4](https://github.com/webiny/webiny-js/compare/@webiny/app-page-builder@3.2.4-next.0...@webiny/app-page-builder@3.2.4) (2020-04-16)

**Note:** Version bump only for package @webiny/app-page-builder





## [3.2.4-next.0](https://github.com/webiny/webiny-js/compare/@webiny/app-page-builder@3.2.3...@webiny/app-page-builder@3.2.4-next.0) (2020-04-16)


### Bug Fixes

* correct import and function name ([7daf3b6](https://github.com/webiny/webiny-js/commit/7daf3b6aab9c22bc1999f68832d8d1e5c36b74c3))
* correct import and function name ([b442f89](https://github.com/webiny/webiny-js/commit/b442f8902e2671e88c7902b0c166768904c77312))
* remove addTimestamp option ([d5edf51](https://github.com/webiny/webiny-js/commit/d5edf51b97c8e570fa57ec85a60114d45eea31f6))





## [3.2.3](https://github.com/webiny/webiny-js/compare/@webiny/app-page-builder@3.2.2...@webiny/app-page-builder@3.2.3) (2020-04-14)


### Bug Fixes

* add "preview" boolean field ([dace12e](https://github.com/webiny/webiny-js/commit/dace12eb1bb346068f0542e7c8a23b4088cefcdf))
* set "addTimestamp" to true ([bac52b7](https://github.com/webiny/webiny-js/commit/bac52b79c957770d0229cb88f7f4fb8abdda8a8e))
* set "preview" to true if fetching the page by "id" ([cbf9986](https://github.com/webiny/webiny-js/commit/cbf9986900480d951992a34855ab6e414ed065a2))





## [3.2.2](https://github.com/webiny/webiny-js/compare/@webiny/app-page-builder@3.2.1...@webiny/app-page-builder@3.2.2) (2020-04-13)


### Bug Fixes

* change "pb-page-element" to "pb-editor-page-element" ([#788](https://github.com/webiny/webiny-js/issues/788)) ([6b5a09b](https://github.com/webiny/webiny-js/commit/6b5a09b8118fd540eb98047d2aaf0b2c00e3712c)), closes [#787](https://github.com/webiny/webiny-js/issues/787)





## [3.2.1](https://github.com/webiny/webiny-js/compare/@webiny/app-page-builder@3.2.1-next.0...@webiny/app-page-builder@3.2.1) (2020-04-03)

**Note:** Version bump only for package @webiny/app-page-builder





## [3.2.1-next.0](https://github.com/webiny/webiny-js/compare/@webiny/app-page-builder@3.2.0...@webiny/app-page-builder@3.2.1-next.0) (2020-04-03)


### Bug Fixes

* add missing TS types ([93ef1ef](https://github.com/webiny/webiny-js/commit/93ef1ef7bf52cde5a3d860c190d7c0880ab3e807))





# [3.2.0](https://github.com/webiny/webiny-js/compare/@webiny/app-page-builder@3.2.0-next.0...@webiny/app-page-builder@3.2.0) (2020-03-09)

**Note:** Version bump only for package @webiny/app-page-builder





# [3.2.0-next.0](https://github.com/webiny/webiny-js/compare/@webiny/app-page-builder@3.1.6...@webiny/app-page-builder@3.2.0-next.0) (2020-03-09)


### Bug Fixes

* CDN cache is now invalidated properly upon updating Page Builder settings ([#746](https://github.com/webiny/webiny-js/issues/746)) ([f686fc0](https://github.com/webiny/webiny-js/commit/f686fc06c747081473baac35e22941945b6351db)), closes [#727](https://github.com/webiny/webiny-js/issues/727)
* don't apply CSS class to typography selector items ([1c2e022](https://github.com/webiny/webiny-js/commit/1c2e0222cd8ddad20a6bffeb8936b056338347de))
* ensure passed "link" is string before proceeding ([#744](https://github.com/webiny/webiny-js/issues/744)) ([931b0bb](https://github.com/webiny/webiny-js/commit/931b0bb4e66412d00f565cea51a3cb0dadab5f39))


### Features

* improved scopes selection auto-complete component([#743](https://github.com/webiny/webiny-js/issues/743)) ([f3acbc5](https://github.com/webiny/webiny-js/commit/f3acbc5aa467ac3d70649628bfbe68727345487e)), closes [#729](https://github.com/webiny/webiny-js/issues/729)





## [3.1.6](https://github.com/webiny/webiny-js/compare/@webiny/app-page-builder@3.1.5...@webiny/app-page-builder@3.1.6) (2020-03-03)


### Bug Fixes

* do not use fragments inside of the Helmet component ([85aaebe](https://github.com/webiny/webiny-js/commit/85aaebe5fa2fbce0849e554be6a2ace5d10a3aa9))





## [3.1.5](https://github.com/webiny/webiny-js/compare/@webiny/app-page-builder@3.1.5-next.0...@webiny/app-page-builder@3.1.5) (2020-03-01)

**Note:** Version bump only for package @webiny/app-page-builder





## [3.1.5-next.0](https://github.com/webiny/webiny-js/compare/@webiny/app-page-builder@3.1.4...@webiny/app-page-builder@3.1.5-next.0) (2020-03-01)


### Bug Fixes

* handle PB Element errors during render ([#726](https://github.com/webiny/webiny-js/issues/726)) ([43fec78](https://github.com/webiny/webiny-js/commit/43fec78b8970e54ba9cb68c6901a92b9eb4870eb))
* improve error message of deploy-apps command([#732](https://github.com/webiny/webiny-js/issues/732)) ([f696517](https://github.com/webiny/webiny-js/commit/f69651758832a68acce92650da58cd6505735ec2))
* tags search & "Pages List" menu item site rendering ([#734](https://github.com/webiny/webiny-js/issues/734)) ([2f39e7a](https://github.com/webiny/webiny-js/commit/2f39e7a5a7bb0915e9bfcd460007108a69a1accd)), closes [#731](https://github.com/webiny/webiny-js/issues/731)





## [3.1.4](https://github.com/webiny/webiny-js/compare/@webiny/app-page-builder@3.1.4-next.1...@webiny/app-page-builder@3.1.4) (2020-02-24)

**Note:** Version bump only for package @webiny/app-page-builder





## [3.1.4-next.1](https://github.com/webiny/webiny-js/compare/@webiny/app-page-builder@3.1.4-next.0...@webiny/app-page-builder@3.1.4-next.1) (2020-02-24)


### Bug Fixes

* add missing variables ([d40cd56](https://github.com/webiny/webiny-js/commit/d40cd5664bf5a14199ae32c672f9ac2765c6e354))





## [3.1.4-next.0](https://github.com/webiny/webiny-js/compare/@webiny/app-page-builder@3.1.3...@webiny/app-page-builder@3.1.4-next.0) (2020-02-23)


### Bug Fixes

* improve handling of internal/external links ([#724](https://github.com/webiny/webiny-js/issues/724)) ([ddb8f8a](https://github.com/webiny/webiny-js/commit/ddb8f8a73e6109508bb69610923806e7b225431f)), closes [#719](https://github.com/webiny/webiny-js/issues/719)
* **page-builder:** simplify usage and improve performance when loading with pages ([91c12c8](https://github.com/webiny/webiny-js/commit/91c12c8dfbdfe2adef809b556ab2eee40eb3a2ca))





## [3.1.3](https://github.com/webiny/webiny-js/compare/@webiny/app-page-builder@3.1.2...@webiny/app-page-builder@3.1.3) (2020-02-14)


### Bug Fixes

* restore slate v0.42 onKeyDown plugin signature ([#718](https://github.com/webiny/webiny-js/issues/718)) ([357e36c](https://github.com/webiny/webiny-js/commit/357e36ca82140237316a264bad8a5708f995d7ee))
* synchronize pageList component name with element plugin ([#717](https://github.com/webiny/webiny-js/issues/717)) ([87f8bf8](https://github.com/webiny/webiny-js/commit/87f8bf85b08cc97766c52d420d4ad7a7236d9b3e))





## [3.1.2](https://github.com/webiny/webiny-js/compare/@webiny/app-page-builder@3.1.2-next.0...@webiny/app-page-builder@3.1.2) (2020-02-12)

**Note:** Version bump only for package @webiny/app-page-builder





## [3.1.2-next.0](https://github.com/webiny/webiny-js/compare/@webiny/app-page-builder@3.1.1...@webiny/app-page-builder@3.1.2-next.0) (2020-02-11)

**Note:** Version bump only for package @webiny/app-page-builder





## [3.1.1](https://github.com/webiny/webiny-js/compare/@webiny/app-page-builder@3.1.1-next.0...@webiny/app-page-builder@3.1.1) (2020-02-07)

**Note:** Version bump only for package @webiny/app-page-builder





## [3.1.1-next.0](https://github.com/webiny/webiny-js/compare/@webiny/app-page-builder@3.1.0...@webiny/app-page-builder@3.1.1-next.0) (2020-02-07)

**Note:** Version bump only for package @webiny/app-page-builder





# [3.1.0](https://github.com/webiny/webiny-js/compare/@webiny/app-page-builder@3.1.0-next.0...@webiny/app-page-builder@3.1.0) (2020-02-06)


### Bug Fixes

* minor docs addition ([62f9d81](https://github.com/webiny/webiny-js/commit/62f9d8112c9f82af120c61e64f3c8bbd56b24088))





# [3.1.0-next.0](https://github.com/webiny/webiny-js/compare/@webiny/app-page-builder@3.0.1...@webiny/app-page-builder@3.1.0-next.0) (2020-02-05)


### Bug Fixes

* handle external links and fix initial page links. ([920b125](https://github.com/webiny/webiny-js/commit/920b1251ef5a61b996b8e6b6f05b829fd00950d7))
* if PB wasn't installed, show an appropriate error message ([#692](https://github.com/webiny/webiny-js/issues/692)) ([b1d858c](https://github.com/webiny/webiny-js/commit/b1d858c45c76953d05dd32e416c6e7b355fed36c)), closes [#676](https://github.com/webiny/webiny-js/issues/676)
* refetch forms in page builder element ([#694](https://github.com/webiny/webiny-js/issues/694)) ([4ee88f5](https://github.com/webiny/webiny-js/commit/4ee88f5f56704ff6eaf71d0624ecc7ea872c3a20)), closes [#678](https://github.com/webiny/webiny-js/issues/678)


### Features

* Clicking outside the 'Get Started Guide' modal now exits the guide ([#680](https://github.com/webiny/webiny-js/issues/680)) ([2395a4f](https://github.com/webiny/webiny-js/commit/2395a4f6050b047bbbea85400c1e73249f0fc5d8))





## [3.0.1](https://github.com/webiny/webiny-js/compare/@webiny/app-page-builder@3.0.0...@webiny/app-page-builder@3.0.1) (2020-01-27)


### Bug Fixes

* editor plugin types and TS types location. ([031f064](https://github.com/webiny/webiny-js/commit/031f0644c52fa2bd1f7095f0b80818c549d7672d))





# [3.0.0](https://github.com/webiny/webiny-js/compare/@webiny/app-page-builder@2.0.3...@webiny/app-page-builder@3.0.0) (2020-01-27)


### Features

* TypeScript && improved SSR mechanisms ([#677](https://github.com/webiny/webiny-js/issues/677)) ([3da0566](https://github.com/webiny/webiny-js/commit/3da0566f29e1d46df0e7c357be0b42bdaa4c7d2b))





## [2.0.4-next.3](https://github.com/webiny/webiny-js/compare/@webiny/app-page-builder@2.0.4-next.2...@webiny/app-page-builder@2.0.4-next.3) (2020-01-27)

**Note:** Version bump only for package @webiny/app-page-builder





## [2.0.4-next.2](https://github.com/webiny/webiny-js/compare/@webiny/app-page-builder@2.0.4-next.1...@webiny/app-page-builder@2.0.4-next.2) (2020-01-27)

**Note:** Version bump only for package @webiny/app-page-builder





## [2.0.4-next.1](https://github.com/webiny/webiny-js/compare/@webiny/app-page-builder@2.0.4-next.0...@webiny/app-page-builder@2.0.4-next.1) (2020-01-27)


### Bug Fixes

* name of the plugin ([3360182](https://github.com/webiny/webiny-js/commit/33601824e094749782fb3e49da68d173945673ff))





## [2.0.4-next.0](https://github.com/webiny/webiny-js/compare/@webiny/app-page-builder@2.0.3...@webiny/app-page-builder@2.0.4-next.0) (2020-01-24)

**Note:** Version bump only for package @webiny/app-page-builder





## [2.0.3](https://github.com/webiny/webiny-js/compare/@webiny/app-page-builder@2.0.3-next.2...@webiny/app-page-builder@2.0.3) (2019-12-04)

**Note:** Version bump only for package @webiny/app-page-builder





## [2.0.3-next.2](https://github.com/webiny/webiny-js/compare/@webiny/app-page-builder@2.0.3-next.1...@webiny/app-page-builder@2.0.3-next.2) (2019-12-04)

**Note:** Version bump only for package @webiny/app-page-builder





## [2.0.3-next.1](https://github.com/webiny/webiny-js/compare/@webiny/app-page-builder@2.0.3-next.0...@webiny/app-page-builder@2.0.3-next.1) (2019-12-04)

**Note:** Version bump only for package @webiny/app-page-builder





## [2.0.3-next.0](https://github.com/webiny/webiny-js/compare/@webiny/app-page-builder@2.0.2...@webiny/app-page-builder@2.0.3-next.0) (2019-12-04)


### Bug Fixes

* page builder settings sliders ([#631](https://github.com/webiny/webiny-js/issues/631)) ([fb3b52d](https://github.com/webiny/webiny-js/commit/fb3b52d20105b1ae34dcdc7554057c75cc747cc4))
* reset ref on unmount ([e9fcbb3](https://github.com/webiny/webiny-js/commit/e9fcbb313cec44cf8ea950f23b435bdfa100e311))
* show drag helper with a short delay and fade-in effect ([c711ac5](https://github.com/webiny/webiny-js/commit/c711ac5b44fd55aa87a848d8bbacb9b8bc338b38))





## [2.0.2](https://github.com/webiny/webiny-js/compare/@webiny/app-page-builder@2.0.1...@webiny/app-page-builder@2.0.2) (2019-11-08)

**Note:** Version bump only for package @webiny/app-page-builder





## [2.0.1](https://github.com/webiny/webiny-js/compare/@webiny/app-page-builder@2.0.0...@webiny/app-page-builder@2.0.1) (2019-11-03)


### Bug Fixes

* UI bugs in revisions list ([#588](https://github.com/webiny/webiny-js/issues/588)) ([ca19431](https://github.com/webiny/webiny-js/commit/ca194319e9614f302cc4c658919a9d7562817726))





# [2.0.0](https://github.com/webiny/webiny-js/compare/@webiny/app-page-builder@0.1.15...@webiny/app-page-builder@2.0.0) (2019-10-29)

**Note:** Version bump only for package @webiny/app-page-builder





## [0.1.15](https://github.com/webiny/webiny-js/compare/@webiny/app-page-builder@0.1.14...@webiny/app-page-builder@0.1.15) (2019-10-29)

**Note:** Version bump only for package @webiny/app-page-builder





## [0.1.14](https://github.com/webiny/webiny-js/compare/@webiny/app-page-builder@0.1.13...@webiny/app-page-builder@0.1.14) (2019-10-29)


### Bug Fixes

* add awaitRefetchQueries to revision handler. ([155c20c](https://github.com/webiny/webiny-js/commit/155c20c))
* add progress loaders and better messaging. ([f40132f](https://github.com/webiny/webiny-js/commit/f40132f))
* disable deletion of root revision. ([0495e26](https://github.com/webiny/webiny-js/commit/0495e26))
* improve circular progress labels ([cafa344](https://github.com/webiny/webiny-js/commit/cafa344))
* pass native React ref. ([d88b7d4](https://github.com/webiny/webiny-js/commit/d88b7d4))
* print N/A if page author can't be loaded. ([7b34940](https://github.com/webiny/webiny-js/commit/7b34940))
* refresh block list and assign the correct block category on save. ([cadc4c7](https://github.com/webiny/webiny-js/commit/cadc4c7))
* rename gql query to match usages. ([4ac8beb](https://github.com/webiny/webiny-js/commit/4ac8beb))
* rename variables to fix name clash in form views. ([108586d](https://github.com/webiny/webiny-js/commit/108586d))
* send new reference to showConfirmation to useHandler. ([cd92acc](https://github.com/webiny/webiny-js/commit/cd92acc))
* update query names and load 100 categories for "CreatePage" dialog. ([643097f](https://github.com/webiny/webiny-js/commit/643097f))
* when installation error is caught, do not call onInstalled callback. ([f63d918](https://github.com/webiny/webiny-js/commit/f63d918))





## [0.1.13](https://github.com/webiny/webiny-js/compare/@webiny/app-page-builder@0.1.12...@webiny/app-page-builder@0.1.13) (2019-10-24)

**Note:** Version bump only for package @webiny/app-page-builder





## [0.1.12](https://github.com/webiny/webiny-js/compare/@webiny/app-page-builder@0.1.11...@webiny/app-page-builder@0.1.12) (2019-10-23)

**Note:** Version bump only for package @webiny/app-page-builder





## [0.1.11](https://github.com/webiny/webiny-js/compare/@webiny/app-page-builder@0.1.10...@webiny/app-page-builder@0.1.11) (2019-10-21)

**Note:** Version bump only for package @webiny/app-page-builder





## [0.1.10](https://github.com/webiny/webiny-js/compare/@webiny/app-page-builder@0.1.9...@webiny/app-page-builder@0.1.10) (2019-10-21)


### Bug Fixes

* add loading overlay on save elements/blocks dialog ([e9f1e5b](https://github.com/webiny/webiny-js/commit/e9f1e5ba2368dd3a87f5a3774305e6be96337854))
* clicking on "Overwrite", deselecting it and submitting the form produces errors ([4856113](https://github.com/webiny/webiny-js/commit/48561136186c1ff740dd100bda1aa229a746915f))
* name of image-list (mosaic) plugin ([c0543a7](https://github.com/webiny/webiny-js/commit/c0543a737a7cb1e434479d0dae3e997e6f35afd7))
* save image via files service once upload is complete ([d0a29c1](https://github.com/webiny/webiny-js/commit/d0a29c123a92161a5c9194dedd1c81af5a56852b))
* saved elements section ([893c677](https://github.com/webiny/webiny-js/commit/893c677d26261698286f9799a63bb65eaf9cc029))





## [0.1.9](https://github.com/webiny/webiny-js/compare/@webiny/app-page-builder@0.1.8...@webiny/app-page-builder@0.1.9) (2019-10-17)

**Note:** Version bump only for package @webiny/app-page-builder





## [0.1.8](https://github.com/webiny/webiny-js/compare/@webiny/app-page-builder@0.1.7...@webiny/app-page-builder@0.1.8) (2019-10-17)


### Bug Fixes

* get rid of weird dragging overlay ([4955155](https://github.com/webiny/webiny-js/commit/4955155))





## [0.1.7](https://github.com/webiny/webiny-js/compare/@webiny/app-page-builder@0.1.6...@webiny/app-page-builder@0.1.7) (2019-10-16)


### Bug Fixes

* temporary disable the slider page-builder element ([8eb6c0b](https://github.com/webiny/webiny-js/commit/8eb6c0b1cff79f7f7b8da41b3ac8960f97f49c42))





## [0.1.6](https://github.com/webiny/webiny-js/compare/@webiny/app-page-builder@0.1.5...@webiny/app-page-builder@0.1.6) (2019-10-14)


### Bug Fixes

* add missing dependency ([f32fce5](https://github.com/webiny/webiny-js/commit/f32fce5da50efb3e090dd1ebea57c4a4d4528d23))





## [0.1.5](https://github.com/webiny/webiny-js/compare/@webiny/app-page-builder@0.1.4...@webiny/app-page-builder@0.1.5) (2019-10-14)


### Bug Fixes

* synced dependencies across all packages ([#567](https://github.com/webiny/webiny-js/issues/567)) ([38eda54](https://github.com/webiny/webiny-js/commit/38eda547bead6e8a2c46875730bbcd8f1227e475))





## [0.1.4](https://github.com/webiny/webiny-js/compare/@webiny/app-page-builder@0.1.3...@webiny/app-page-builder@0.1.4) (2019-10-11)


### Bug Fixes

* update dependencies ([2def479](https://github.com/webiny/webiny-js/commit/2def479886ed356e7981b7be61b957edcc87f887))





<a name="0.1.3"></a>
## [0.1.3](https://github.com/webiny/webiny-js/compare/@webiny/app-page-builder@0.1.2...@webiny/app-page-builder@0.1.3) (2019-10-11)

**Note:** Version bump only for package @webiny/app-page-builder





# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [0.1.2](https://github.com/webiny/webiny-js/compare/@webiny/app-page-builder@0.1.1...@webiny/app-page-builder@0.1.2) (2019-10-10)

**Note:** Version bump only for package @webiny/app-page-builder





## [0.1.1](https://github.com/webiny/webiny-js/compare/@webiny/app-page-builder@0.1.0...@webiny/app-page-builder@0.1.1) (2019-10-06)

**Note:** Version bump only for package @webiny/app-page-builder
