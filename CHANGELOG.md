## [1.5.2](https://github.com/netless-io/flat/compare/v1.5.1...v1.5.2) (2022-01-13)


### Bug Fixes

* **desktop:** online courseware remote execution vulnerability ([#1290](https://github.com/netless-io/flat/issues/1290)) ([81c18a6](https://github.com/netless-io/flat/commit/81c18a6764a6bc4b7d6f149437a1f13d8e917223))



## [1.5.1](https://github.com/netless-io/flat/compare/v1.5.0...v1.5.1) (2022-01-11)


### Bug Fixes

* **electron:** ui display error when upgrading flat ([#1284](https://github.com/netless-io/flat/issues/1284)) ([9469f6a](https://github.com/netless-io/flat/commit/9469f6a5cbc9bd28a3b75a3793efc08b09eff22d))



# [1.5.0](https://github.com/netless-io/flat/compare/v1.4.0...v1.5.0) (2022-01-11)


### Bug Fixes

* **library:** sync camera on insert image ([#1281](https://github.com/netless-io/flat/issues/1281)) ([3b4e7d8](https://github.com/netless-io/flat/commit/3b4e7d895b858c461722f568d7655a15e01b4521))
* **project:** refresh channel info on reconnect ([#1274](https://github.com/netless-io/flat/issues/1274)) ([8fa0c1f](https://github.com/netless-io/flat/commit/8fa0c1f43b971a864265eef972d7c623106fe7c5))
* **renderer-app:** hot keys invalid in preview file window ([#1264](https://github.com/netless-io/flat/issues/1264)) ([f3f2bef](https://github.com/netless-io/flat/commit/f3f2bef138fa0c8b13027a6b28d7ad310399ca31))


### Features

* **desktop:** support macOS localized ([#1260](https://github.com/netless-io/flat/issues/1260)) ([d6c668a](https://github.com/netless-io/flat/commit/d6c668ab4fdd81b0662beee5b668d0a39604d058))
* **web:** add "open in browser" tip in wechat browser ([#1268](https://github.com/netless-io/flat/issues/1268)) ([76e87c8](https://github.com/netless-io/flat/commit/76e87c8678e34604e922808bbd64b693d865e2e6))



# [1.4.0](https://github.com/netless-io/flat/compare/v1.3.0...v1.4.0) (2021-12-30)


### Bug Fixes

* **ci:** docker push tag typo ([#1186](https://github.com/netless-io/flat/issues/1186)) ([a2ed313](https://github.com/netless-io/flat/commit/a2ed31333867919798ff61a1f3dfeb3416b0f449))
* **desktop:** Apple M1 open and build failed on development  ([#1251](https://github.com/netless-io/flat/issues/1251)) ([70a6ef1](https://github.com/netless-io/flat/commit/70a6ef14569c51d8854a2381bbadb8d7aec6ec94))
* **desktop:** mouse cannot be displayed during screen sharing ([#1199](https://github.com/netless-io/flat/issues/1199)) ([8f46b28](https://github.com/netless-io/flat/commit/8f46b2842d828318c8a21afba29bf256829e7b13))
* **desktop:** not jumping to the login page when the token expires ([#1197](https://github.com/netless-io/flat/issues/1197)) ([cf22c0c](https://github.com/netless-io/flat/commit/cf22c0c43ca8451ae26ce6a615ad1a465921064b))
* **desktop:** refresh crash in any page ([#1246](https://github.com/netless-io/flat/issues/1246)) ([bd02188](https://github.com/netless-io/flat/commit/bd02188c53e0583790c03778bed6f2fd3dc1caa0))
* **desktop:** throw error after refreshing within classroom and device check ([#1248](https://github.com/netless-io/flat/issues/1248)) ([0f29a81](https://github.com/netless-io/flat/commit/0f29a8127b28dbdc0ff5b4c3505bd7efb01f5b34))
* **flat-components:** button text error of RoomDetailFooter components ([#1227](https://github.com/netless-io/flat/issues/1227)) ([7f6f5b0](https://github.com/netless-io/flat/commit/7f6f5b0200dfc997e26edf73b8217ffa6e103ba9))
* **flat-components:** loading page covers the top bar ([#1204](https://github.com/netless-io/flat/issues/1204)) ([d2d1694](https://github.com/netless-io/flat/commit/d2d1694500857281a94a73743a65d805f0822acf))
* **main-app:** send ipc crash ([#1242](https://github.com/netless-io/flat/issues/1242)) ([22bcc47](https://github.com/netless-io/flat/commit/22bcc4795b602668065970d34f721e1a4fac853c))
* **renderer-app:** close cloud storage panel fail after insert file ([#1193](https://github.com/netless-io/flat/issues/1193)) ([7b159ce](https://github.com/netless-io/flat/commit/7b159cecad6606a89d915a5e0059c2552882aa10))
* **renderer-app:** share screen tips window style incorrect ([#1250](https://github.com/netless-io/flat/issues/1250)) ([56e8fb8](https://github.com/netless-io/flat/commit/56e8fb84a4df62439511812f7fc46a4917ef291c))
* **renderer-app:** share screen tips window unable to drag ([#1256](https://github.com/netless-io/flat/issues/1256)) ([5689d92](https://github.com/netless-io/flat/commit/5689d929274b427586163842262987107ad29c4a))
* **web,renderer-app:** tag type error of MainRoomList components ([#1224](https://github.com/netless-io/flat/issues/1224)) ([c5c391c](https://github.com/netless-io/flat/commit/c5c391c82464481613baa9c173a58029b150ef6f))
* **web:** add dependency `@babel/runtime` ([#1216](https://github.com/netless-io/flat/issues/1216)) ([b37e2ad](https://github.com/netless-io/flat/commit/b37e2ad7ddc0123d9a392b7185ed722f39545419))
* **web:** local track error introduced by [#1203](https://github.com/netless-io/flat/issues/1203) ([#1212](https://github.com/netless-io/flat/issues/1212)) ([b89fbb8](https://github.com/netless-io/flat/commit/b89fbb8c7acfbe8e71d16170da5b91c35d57f76e))
* **web:** rtc not turn-ed off when destroy ([#1203](https://github.com/netless-io/flat/issues/1203)) ([eab733c](https://github.com/netless-io/flat/commit/eab733cf54c1e15adbb380caa94bf38605e9e061))


### Features

* **desktop:** support preview file at new window ([#1243](https://github.com/netless-io/flat/issues/1243)) ([aea964f](https://github.com/netless-io/flat/commit/aea964f41df7602b264efaa61272d14e6f0bcfde))
* **flat-components:** add theme colors ([#1226](https://github.com/netless-io/flat/issues/1226)) ([5339370](https://github.com/netless-io/flat/commit/53393703ee90711e34e875ff2c3b61f24a6e6087))
* **whiteboard:** add new config to whiteboard ([#1245](https://github.com/netless-io/flat/issues/1245)) ([18a94e9](https://github.com/netless-io/flat/commit/18a94e9c3b47ef706030acfb0ee8d898d64054d8))


### Performance Improvements

* **renderer-app:** improve clarity of screen share on desktop ([#1223](https://github.com/netless-io/flat/issues/1223)) ([bc73aea](https://github.com/netless-io/flat/commit/bc73aea55b258684e98bfefb0d597ad8a1ba1526))


### Reverts

* Revert "chore(web): upgrade vite to 2.7.2 (#1215)" (#1218) ([7b51497](https://github.com/netless-io/flat/commit/7b5149771c987d208de6640d8f73d0481b0dcab0)), closes [#1215](https://github.com/netless-io/flat/issues/1215) [#1218](https://github.com/netless-io/flat/issues/1218)
* Revert "fix(web): add dependency `@babel/runtime` (#1216)" (#1217) ([47dc4d9](https://github.com/netless-io/flat/commit/47dc4d963ca89cd1a50e2c8a81f7ba0fd1a2e820)), closes [#1216](https://github.com/netless-io/flat/issues/1216) [#1217](https://github.com/netless-io/flat/issues/1217)



# [1.3.0](https://github.com/netless-io/flat/compare/v1.2.0...v1.3.0) (2021-12-08)


### Bug Fixes

* **electron:** load react devtools extension failed ([#1102](https://github.com/netless-io/flat/issues/1102)) ([5cccbca](https://github.com/netless-io/flat/commit/5cccbca9ecb4ac4886129dca811c87ab512c84b8))
* **flat-components:** fix ant-mod text layout ([#1156](https://github.com/netless-io/flat/issues/1156)) ([0503813](https://github.com/netless-io/flat/commit/0503813fdfee6b10be32f38395c0c30812c0f875)), closes [#872](https://github.com/netless-io/flat/issues/872)
* **flat-types:** ci failure with lose build script ([#1154](https://github.com/netless-io/flat/issues/1154)) ([174f695](https://github.com/netless-io/flat/commit/174f69515d58d9badc08c43140a186c4dc0a9e5e))
* **project:** hanging on login page when no-login join room ([#1147](https://github.com/netless-io/flat/issues/1147)) ([54b271b](https://github.com/netless-io/flat/commit/54b271b0866542f7c94da3ddf5236c1ad76f54f2))
* **renderer-app:** audio playback device test failed on windows system ([#1182](https://github.com/netless-io/flat/issues/1182)) ([1a2d13f](https://github.com/netless-io/flat/commit/1a2d13f2f3dcc26f3a10183d82a3db2c2c80324e))
* **room:** room detail request failed ([#1165](https://github.com/netless-io/flat/issues/1165)) ([21001e5](https://github.com/netless-io/flat/commit/21001e5d5f2c68af4915eae435dc8a3a3cf578dd))
* **web:** at most download once ([#1106](https://github.com/netless-io/flat/issues/1106)) ([90f467b](https://github.com/netless-io/flat/commit/90f467b46b3c8f1749caee4b3b88e11d9ff59e70))
* **web:** import utils incorrect ([#1166](https://github.com/netless-io/flat/issues/1166)) ([26ead1f](https://github.com/netless-io/flat/commit/26ead1f3525fb2955cdc285d2a4c975b4ae763b3))
* **web:** manual open invite url crash in safari ([#1146](https://github.com/netless-io/flat/issues/1146)) ([d2d6958](https://github.com/netless-io/flat/commit/d2d69589997d40dfed0cef4236797363cdb74768))
* **web:** open invite url crash in safari ([#1113](https://github.com/netless-io/flat/issues/1113)) ([a5d3da1](https://github.com/netless-io/flat/commit/a5d3da1ba1f884e2baf4da0468c2e5f1697aed08))
* **web:** prevent duplicate `network error` ([#1177](https://github.com/netless-io/flat/issues/1177)) ([e9be221](https://github.com/netless-io/flat/commit/e9be2213af83b817895ea294b2af70fb4906ba47))
* **web:** whiteboard size error when the avatar wrap becomes longer ([#1103](https://github.com/netless-io/flat/issues/1103)) ([b11c83d](https://github.com/netless-io/flat/commit/b11c83df144b9e6af22f0b1b6ec7d475f8ce8be8))


### Features

* **classroom:** add user guide to the classroom ([#1179](https://github.com/netless-io/flat/issues/1179)) ([f75c14e](https://github.com/netless-io/flat/commit/f75c14e0e299c16f5c13d26183c1ece4afa06382))
* **desktop:** support local react devtools ([#1084](https://github.com/netless-io/flat/issues/1084)) ([0ea1e5c](https://github.com/netless-io/flat/commit/0ea1e5c4670511904812ed559cdb635e1b573aa6))
* **desktop:** support window manager in replay mode ([#1142](https://github.com/netless-io/flat/issues/1142)) ([d0edfe0](https://github.com/netless-io/flat/commit/d0edfe0bda752168bf2087c576cbf16268b3d3c9))
* **project:** support drag and drop supported file in room ([#1144](https://github.com/netless-io/flat/issues/1144)) ([e779367](https://github.com/netless-io/flat/commit/e779367fb8aacd35596bbec60c2e606923b6706c))
* **web:** add device test page ([#1145](https://github.com/netless-io/flat/issues/1145)) ([653bd2e](https://github.com/netless-io/flat/commit/653bd2ea7a9951c6829eac1741ce12aacee71d8e))
* **web:** support android asset links ([#1170](https://github.com/netless-io/flat/issues/1170)) ([537f898](https://github.com/netless-io/flat/commit/537f898c41b2b212260959a6446633d2d8ce4e06))
* **web:** support apple app site association ([#1167](https://github.com/netless-io/flat/issues/1167)) ([59bab15](https://github.com/netless-io/flat/commit/59bab15dc012137aede1322110e8f1379b05c8d2))
* **web:** support window manager in replay mode ([#1140](https://github.com/netless-io/flat/issues/1140)) ([7d0360b](https://github.com/netless-io/flat/commit/7d0360b6ca2eb479dd88e726d1338fc04f66fd44))
* **web:** the classroom page device keep consistent with devices selected by the devices test page ([#1183](https://github.com/netless-io/flat/issues/1183)) ([7c002d8](https://github.com/netless-io/flat/commit/7c002d88b2abd86cf14710c42fbee9756e4c9ec0))


### Performance Improvements

* **project:** optimize SVGs ([#1152](https://github.com/netless-io/flat/issues/1152)) ([0145f9f](https://github.com/netless-io/flat/commit/0145f9f1d20fc8fb0f3c88b6b8b8a09131b03deb))



# [1.2.0](https://github.com/netless-io/flat/compare/v1.1.0...v1.2.0) (2021-11-16)


### Bug Fixes

* **deployment:** svg is not cached ([#1040](https://github.com/netless-io/flat/issues/1040)) ([d0c4fd2](https://github.com/netless-io/flat/commit/d0c4fd29fb61090d004b884283f2a94785964786))
* **desktop:** cannot open camera on desktop ([#1072](https://github.com/netless-io/flat/issues/1072)) ([f46055c](https://github.com/netless-io/flat/commit/f46055c1f6d156d27a0e0f1beb3d4a11f37f52bb))
* **flat-components:** add width value for avoid content dislocation when cover resource not loaded ([#1039](https://github.com/netless-io/flat/issues/1039)) ([508bfdb](https://github.com/netless-io/flat/commit/508bfdbf287ad7a9b73537e6e44b8cef5973b740))
* **renderer-app:** the right side of classroom bar not hidden when click hidden button ([#1008](https://github.com/netless-io/flat/issues/1008)) ([08620d0](https://github.com/netless-io/flat/commit/08620d0f04bf5b6c10ade2b6a26d2ff1e285007e))
* **scripts:** flat-web build failed on windows system ([#1062](https://github.com/netless-io/flat/issues/1062)) ([8a239fe](https://github.com/netless-io/flat/commit/8a239fe140f0e0e41a16d14588a686a085a8bf9a))
* **storybook:** fix FakeStore api ([#1030](https://github.com/netless-io/flat/issues/1030)) ([5ed7415](https://github.com/netless-io/flat/commit/5ed7415c481963fdc4e56a4203a149e6f1a24cec))
* **style:** error style of the slide button ([#1092](https://github.com/netless-io/flat/issues/1092)) ([8757bc0](https://github.com/netless-io/flat/commit/8757bc0e7903c1839996ed5e4eadd93a8e1316d4))
* **web,scripts:** flat-web failed to startup in windows system ([#1007](https://github.com/netless-io/flat/issues/1007)) ([d2ab4a5](https://github.com/netless-io/flat/commit/d2ab4a5b2dff26b53e236903e64972f91cf22612))
* **web:** black screen when playing dynamic PPT video ([#1024](https://github.com/netless-io/flat/issues/1024)) ([080ac55](https://github.com/netless-io/flat/commit/080ac55611af46f68dcd16fd79e5b1917e5974fc))
* **web:** force wait rtc join ([#1036](https://github.com/netless-io/flat/issues/1036)) ([b3ea971](https://github.com/netless-io/flat/commit/b3ea97152c7b8e6f64e9a6766ca122f61ab3b46e))
* **web:** pptx extension check failed ([#1028](https://github.com/netless-io/flat/issues/1028)) ([afcdf71](https://github.com/netless-io/flat/commit/afcdf715c6de8e4609a55f54ee34849200b2693a))
* **web:** record tips position error ([#1041](https://github.com/netless-io/flat/issues/1041)) ([f9b3d99](https://github.com/netless-io/flat/commit/f9b3d9988f15687cb096b6d678271e2212224e71))
* **web:** rtc is not initialized ([#1035](https://github.com/netless-io/flat/issues/1035)) ([d1dc852](https://github.com/netless-io/flat/commit/d1dc852da9819247b16548c283d5888bfc234feb))
* **web:** try to fix chrome permission popup ([#1057](https://github.com/netless-io/flat/issues/1057)) ([dae0386](https://github.com/netless-io/flat/commit/dae0386b25eda9bd71995237270a8dcd0e35a5ce))
* **whiteboard:** disabled read only the user zoom behavior ([#1073](https://github.com/netless-io/flat/issues/1073)) ([069861a](https://github.com/netless-io/flat/commit/069861af7ddd7746ce1c6a402f1c70b0b36e9604))
* **whiteboard:** style error of the smallClassPage when join room ([#1076](https://github.com/netless-io/flat/issues/1076)) ([933a7e5](https://github.com/netless-io/flat/commit/933a7e5662976e31aa6f5cf1b782e890d5e1a068))
* **whiteboard:** the buttons at the bottom of the whiteboard error style ([#1089](https://github.com/netless-io/flat/issues/1089)) ([885d936](https://github.com/netless-io/flat/commit/885d936974f2f4a4d217d06d8865e0c0320303d7))
* **whiteboard:** window-manager not mount when whiteboard was connected ([#1034](https://github.com/netless-io/flat/issues/1034)) ([c555024](https://github.com/netless-io/flat/commit/c555024e2f6aecc980a29cb6445e82c924454e51))
* **whiteboard:** window-manager repeat mount when whiteboard unMount ([#1014](https://github.com/netless-io/flat/issues/1014)) ([587b498](https://github.com/netless-io/flat/commit/587b498a20dca66c8a3c28cfddfcd2bceafdebf3))


### Features

* add html5 courseware uploading ([#1023](https://github.com/netless-io/flat/issues/1023)) ([4c25b01](https://github.com/netless-io/flat/commit/4c25b01a1a8cedbc6d5e0fa5c4c41f860396b4bb))
* **web:** add apps in whiteboard  ([#994](https://github.com/netless-io/flat/issues/994)) ([a87b1e5](https://github.com/netless-io/flat/commit/a87b1e592599f2811db1b4af26781e74c08a37ec))
* **web:** add loadingPage to AppRouteContainer ([#1038](https://github.com/netless-io/flat/issues/1038)) ([c402fcc](https://github.com/netless-io/flat/commit/c402fccf4b67c4f6e1367deeba29d5ecc5330bce))
* **web:** add vf html5 courseware ([#1026](https://github.com/netless-io/flat/issues/1026)) ([2b3dc95](https://github.com/netless-io/flat/commit/2b3dc95409815b48829fcd8ea1a764280507754a))



# [1.1.0](https://github.com/netless-io/flat/compare/v1.0.0...v1.1.0) (2021-10-15)


### Bug Fixes

* **ci:** deploy web action fail ([#908](https://github.com/netless-io/flat/issues/908)) ([d85e7fc](https://github.com/netless-io/flat/commit/d85e7fc9c2dd2d41987d92d77d2769f7bf2412a0))
* **ci:** flat-web dockerfile build failed ([#887](https://github.com/netless-io/flat/issues/887)) ([e997157](https://github.com/netless-io/flat/commit/e9971579e8432eb0dd1d7777df23626834bc495e))
* **debug:** vscode debugging main process failed ([#933](https://github.com/netless-io/flat/issues/933)) ([097188e](https://github.com/netless-io/flat/commit/097188efec75a7e520d76d39c38f5aa78dcc4593))
* **desktop:** cannot find build script, causing build to failed ([#975](https://github.com/netless-io/flat/issues/975)) ([9998435](https://github.com/netless-io/flat/commit/9998435602ab2487d191c93fe95d3d632aa842ae))
* **desktop:** load source-map error ([#938](https://github.com/netless-io/flat/issues/938)) ([9306316](https://github.com/netless-io/flat/commit/9306316f57adfe60cd1001fbb894f3e5c09556e3)), closes [#804](https://github.com/netless-io/flat/issues/804)
* **desktop:** share display failed in windows system ([#998](https://github.com/netless-io/flat/issues/998)) ([e1f4013](https://github.com/netless-io/flat/commit/e1f4013eb972344eaa50921b15add320dc99e838))
* **eslint,flat-components:** eslint invalid and rule too weak ([#858](https://github.com/netless-io/flat/issues/858)) ([94977c5](https://github.com/netless-io/flat/commit/94977c56b5bc25c5bc6d2d298356ab1d79183ffe))
* **eslint:** eslint error ([#916](https://github.com/netless-io/flat/issues/916)) ([97a5b90](https://github.com/netless-io/flat/commit/97a5b9062551c4b0750fcd17aabc44ebd0966441))
* **eslint:** eslint rule no-unused-vars invalid ([#915](https://github.com/netless-io/flat/issues/915)) ([7d71753](https://github.com/netless-io/flat/commit/7d717533be54863fc8afe988cbcbe3fb1eeb74bf))
* **flat-components:** rename fileUUID to uploadID ([#849](https://github.com/netless-io/flat/issues/849)) ([ed4e9c9](https://github.com/netless-io/flat/commit/ed4e9c91be685087f5eef9c822647d2df85bdee6))
* **flat-components:** tips has higher priority than modal ([#960](https://github.com/netless-io/flat/issues/960)) ([c2d880e](https://github.com/netless-io/flat/commit/c2d880ed21cdd82df3c8df304381bfaf5621f9a3))
* **flat-web:** blocking browser fallback ([#857](https://github.com/netless-io/flat/issues/857)) ([d833d18](https://github.com/netless-io/flat/commit/d833d1867e1cb041357bbdb2df3ec11e09a91835)), closes [#856](https://github.com/netless-io/flat/issues/856)
* **husky:** git hooks invalid ([#847](https://github.com/netless-io/flat/issues/847)) ([6232ce1](https://github.com/netless-io/flat/commit/6232ce197f1cf445c62b99f8018ffea2dd4c0c09))
* **main-app:** does not meet aspect ratio when resize window ([#949](https://github.com/netless-io/flat/issues/949)) ([00920b8](https://github.com/netless-io/flat/commit/00920b8a7bafa63124e9669483b247253f3befd4))
* **main-app:** homepage and repo url incorrect in package.json ([#948](https://github.com/netless-io/flat/issues/948)) ([4d737e7](https://github.com/netless-io/flat/commit/4d737e7bb4bc1981f7223415c632eebf33fa9ee3))
* **main-app:** npm script ship:mac failed ([#977](https://github.com/netless-io/flat/issues/977)) ([63b14ae](https://github.com/netless-io/flat/commit/63b14ae5ac38a9a9822f1dbdba0da3f6a3d6aa83))
* **project:** run bootstrap script fail in linux ([#944](https://github.com/netless-io/flat/issues/944)) ([fe534f7](https://github.com/netless-io/flat/commit/fe534f79e978058fddc445e36e41a04e31fc1323))
* **readme:** storybook link error ([#875](https://github.com/netless-io/flat/issues/875)) ([124fb33](https://github.com/netless-io/flat/commit/124fb33a90b066464621daa892db7c1cb3d21eaf))
* **renderer-app:** monaco-editor load failed in windows system ([#999](https://github.com/netless-io/flat/issues/999)) ([388ea3f](https://github.com/netless-io/flat/commit/388ea3f6f434107dd80950d9e49480c35623045a))
* **scripts:** activate terminal after start command ([#981](https://github.com/netless-io/flat/issues/981)) ([4c46d36](https://github.com/netless-io/flat/commit/4c46d363bbfa78bc684c306f0cf0fe933b49ef3c))
* **scripts:** start will error when iTerm2 not installed ([#965](https://github.com/netless-io/flat/issues/965)) ([ef6668b](https://github.com/netless-io/flat/commit/ef6668bbcb75503b0fb6c502601ec2de910b2df8))
* **service-worker:** support range ([#844](https://github.com/netless-io/flat/issues/844)) ([cae51ff](https://github.com/netless-io/flat/commit/cae51ffaaf40b61126fdaf8b9d8133e92995b522))
* **storybook:** fix type error ([#853](https://github.com/netless-io/flat/issues/853)) ([2ae424c](https://github.com/netless-io/flat/commit/2ae424c42d18e56ec47160ba4d739fe3027e7e3c))
* **style:** share screen z-index less then telebox collector ([#995](https://github.com/netless-io/flat/issues/995)) ([26cd62e](https://github.com/netless-io/flat/commit/26cd62ee2fb0cc81a79cc3b6d8564edfda79cf7b))
* **vscode:** not found tsconfig.json ([#885](https://github.com/netless-io/flat/issues/885)) ([2eccd47](https://github.com/netless-io/flat/commit/2eccd47079cc2563323a79d1fc6bc64dafad6c5f))
* **web:** class room topbar icon no change ([#913](https://github.com/netless-io/flat/issues/913)) ([d3c9134](https://github.com/netless-io/flat/commit/d3c913463bf5072f9e87b0b45808fc54221ae497))
* **web:** ignore isPlaying when calling setEnabled ([#969](https://github.com/netless-io/flat/issues/969)) ([445b5ff](https://github.com/netless-io/flat/commit/445b5ffbb7f9da889a658dbac0cfa24f593be382))
* **web:** make rtc more stable ([#937](https://github.com/netless-io/flat/issues/937)) ([4aba742](https://github.com/netless-io/flat/commit/4aba7420bd6368f472bcf8f9767cd6485f5a53b7))
* **web:** not found env variable ([#863](https://github.com/netless-io/flat/issues/863)) ([1d5f879](https://github.com/netless-io/flat/commit/1d5f879499a612e8bb58c15258fb59c2fc3d3f6b))
* **web:** process.env type not effective ([#980](https://github.com/netless-io/flat/issues/980)) ([3b3938f](https://github.com/netless-io/flat/commit/3b3938feaf1d3e70ec87e9657a0753936419c790))
* **web:** rtc error on publishing video track ([#950](https://github.com/netless-io/flat/issues/950)) ([b4a6ef3](https://github.com/netless-io/flat/commit/b4a6ef3e65138aa156430f9e723e141d9e80cd48))
* **web:** should check remote tracks when creating avatar ([#954](https://github.com/netless-io/flat/issues/954)) ([332cd17](https://github.com/netless-io/flat/commit/332cd17e51cec1e8816ed966e710de007f2d709f))
* **web:** should listen event before join ([#935](https://github.com/netless-io/flat/issues/935)) ([9e959d5](https://github.com/netless-io/flat/commit/9e959d50860e6dcdae838d2debd43791fa94774c))
* **web:** volume to low check logic inaccurate ([#942](https://github.com/netless-io/flat/issues/942)) ([319483a](https://github.com/netless-io/flat/commit/319483a0f6aa79c7ec5d22756514649363212989))
* **web:** when room owner exit room, not close own share screen ([#895](https://github.com/netless-io/flat/issues/895)) ([c916329](https://github.com/netless-io/flat/commit/c916329f761c80fa0a6f5aa5a9b36973af90e0e6))


### Features

* **desktop:** add share screen tip window and support multiple window ([#992](https://github.com/netless-io/flat/issues/992)) ([7480733](https://github.com/netless-io/flat/commit/74807330c2235f74105e8a1ebf13cb81b6a2ea3e))
* **desktop:** support share screen ([#894](https://github.com/netless-io/flat/issues/894)) ([0654db7](https://github.com/netless-io/flat/commit/0654db77448fcc1d25e810b2b0ae2b9be4ceec27))
* **flat-components:** add invite code support ([#993](https://github.com/netless-io/flat/issues/993)) ([8e9e780](https://github.com/netless-io/flat/commit/8e9e780de0d04021f139877155c3aeb9561bda84))
* **flat-components:** add scenes controller components ([#886](https://github.com/netless-io/flat/issues/886)) ([51f359f](https://github.com/netless-io/flat/commit/51f359f9a433509f5b1a0ad72e4ace23dee82e01))
* **flat-components:** add skeletons component to cloud storage ([#985](https://github.com/netless-io/flat/issues/985)) ([44b537b](https://github.com/netless-io/flat/commit/44b537b6e0ad090fa7402968cf3a42dd51d6716c))
* **renderer-app:** add Monaco app to whiteboard ([#978](https://github.com/netless-io/flat/issues/978)) ([ee33fee](https://github.com/netless-io/flat/commit/ee33feed9d0f8039f85b2d48b7893eaea0685c36))
* **web:** add Monaco app to flat-web ([#961](https://github.com/netless-io/flat/issues/961)) ([af8cc68](https://github.com/netless-io/flat/commit/af8cc68d18189b0533a58558a52db91709f17945))
* **web:** support share screen ([#881](https://github.com/netless-io/flat/issues/881)) ([ab19c10](https://github.com/netless-io/flat/commit/ab19c10c4cf07e0400055c0f933ff948a744170f))
* **whiteboard:** add the resize EventListener event to change whiteboard size ([#941](https://github.com/netless-io/flat/issues/941)) ([b4b9805](https://github.com/netless-io/flat/commit/b4b98054e368cb02261ef89c0611fc0a1fbc0941))
* **whiteboard:** support multi window ([#924](https://github.com/netless-io/flat/issues/924)) ([1b7b76b](https://github.com/netless-io/flat/commit/1b7b76be515d626d724e114826186e2b0f1809ae)), closes [#896](https://github.com/netless-io/flat/issues/896) [#899](https://github.com/netless-io/flat/issues/899) [#900](https://github.com/netless-io/flat/issues/900) [#901](https://github.com/netless-io/flat/issues/901) [#903](https://github.com/netless-io/flat/issues/903) [#907](https://github.com/netless-io/flat/issues/907) [#919](https://github.com/netless-io/flat/issues/919) [#920](https://github.com/netless-io/flat/issues/920) [#921](https://github.com/netless-io/flat/issues/921)


### Reverts

* Revert "chore(flat-components): remove rollup and add alias (#870)" (#871) ([8fc00d8](https://github.com/netless-io/flat/commit/8fc00d8b4ef0e1e2cf89413d79039b0f2ac34d4e)), closes [#870](https://github.com/netless-io/flat/issues/870) [#871](https://github.com/netless-io/flat/issues/871)



# 1.0.0 (2021-08-06)


### Bug Fixes

* **app:** application flickers ([#587](https://github.com/netless-io/Flat-native/issues/587)) ([b7db699](https://github.com/netless-io/Flat-native/commit/b7db699049e8ffd8946c7daa43184a2df9ca6814))
* **auto-updater:** remove extra get-update-info ([#570](https://github.com/netless-io/Flat-native/issues/570)) ([85bcf9a](https://github.com/netless-io/Flat-native/commit/85bcf9a8878dfb69c94a2648e1679ec4b43f3aa1))
* **big-class:** avatar default black background ([#576](https://github.com/netless-io/Flat-native/issues/576)) ([035771c](https://github.com/netless-io/Flat-native/commit/035771ccb1888ca5387279447356c08cad46ba03))
* **ci:** code check ci failed ([#682](https://github.com/netless-io/Flat-native/issues/682)) ([958738b](https://github.com/netless-io/Flat-native/commit/958738bbe074454fffd368d7febfd98c035451fb))
* **ci:** lose yarn script exit code ([#701](https://github.com/netless-io/Flat-native/issues/701)) ([0784719](https://github.com/netless-io/Flat-native/commit/078471969349875f3b188bead233057c52460088))
* **ci:** typo workspace name ([#674](https://github.com/netless-io/Flat-native/issues/674)) ([443f0f3](https://github.com/netless-io/Flat-native/commit/443f0f3d1eb3c0cc6f66e9453109a9463647363a))
* **classroom:** fix user join room race condition ([#579](https://github.com/netless-io/Flat-native/issues/579)) ([2d28915](https://github.com/netless-io/Flat-native/commit/2d2891563528cc9b2db18391c94624ce3064a0a4))
* **classroom:** incorrectly destroy `<AvatarCanvas>` ([#780](https://github.com/netless-io/Flat-native/issues/780)) ([15d8f0f](https://github.com/netless-io/Flat-native/commit/15d8f0f1cebede4abb38704730874c2227c79ccd))
* **classroom:** show fallback avatar if the user's failed ([#390](https://github.com/netless-io/Flat-native/issues/390)) ([e594ac0](https://github.com/netless-io/Flat-native/commit/e594ac0ceb7f2ee5e3556c4414c420d2722a7c64))
* **classroom:** stop recording only if is recording ([#807](https://github.com/netless-io/Flat-native/issues/807)) ([a94a305](https://github.com/netless-io/Flat-native/commit/a94a305ba9742924b6805a88f917a21717733bf3))
* **cloud-storage:** cancel upload when error ([#481](https://github.com/netless-io/Flat-native/issues/481)) ([54f201e](https://github.com/netless-io/Flat-native/commit/54f201eccb2c3122f123713671cfef4ef301a0c7))
* **cloudstorage:** refresh list on file upload complete ([#549](https://github.com/netless-io/Flat-native/issues/549)) ([e09113b](https://github.com/netless-io/Flat-native/commit/e09113b41b7a291291eb0706c7682f0187f161d1))
* **convert:** parse ppt url failed ([#831](https://github.com/netless-io/Flat-native/issues/831)) ([d36f52b](https://github.com/netless-io/Flat-native/commit/d36f52b66649673d2f7c32429dc0459b8fc574b8))
* **convert:** query convert status with region ([#823](https://github.com/netless-io/Flat-native/issues/823)) ([f6e9836](https://github.com/netless-io/Flat-native/commit/f6e98361bd7ddfccd7fa99bbaa4f8d69c010b862))
* **deployment:** upload artifacts file to alibaba cloud oss mime type incorrect ([#779](https://github.com/netless-io/Flat-native/issues/779)) ([910c93f](https://github.com/netless-io/Flat-native/commit/910c93f562cbc480b949380c454a3caa599b0e99))
* **desktop:** creator exits room cause bug in homepage room list ([#679](https://github.com/netless-io/Flat-native/issues/679)) ([a6dfae2](https://github.com/netless-io/Flat-native/commit/a6dfae23798d2ba7093ff9a5bb4220d67699e66e))
* **desktop:** exit room when creator cancel it ([#654](https://github.com/netless-io/Flat-native/issues/654)) ([f2bdff9](https://github.com/netless-io/Flat-native/commit/f2bdff967cbc51eefd774844430b081dce547eda))
* **desktop:** fix homepage list scrolling overflow ([#540](https://github.com/netless-io/Flat-native/issues/540)) ([2181196](https://github.com/netless-io/Flat-native/commit/2181196aa61b6703efa1bde85fdc013d1984c353))
* **desktop:** menu is not automatically hidden ([#463](https://github.com/netless-io/Flat-native/issues/463)) ([1699158](https://github.com/netless-io/Flat-native/commit/1699158bbb8069196e81ef4dcae28afe3e305eae))
* **desktop:** preload static converted courseware bug ([#827](https://github.com/netless-io/Flat-native/issues/827)) ([d503568](https://github.com/netless-io/Flat-native/commit/d503568bb00cd7c98a361ea89cc7dc3e37ba052c))
* **desktop:** remove rtc enableVideo and disableVideo ([#551](https://github.com/netless-io/Flat-native/issues/551)) ([f07505a](https://github.com/netless-io/Flat-native/commit/f07505a93743090231a6741e0651d1dd86f42f7d))
* **desktop:** upgrade agora-electron-sdk ([#740](https://github.com/netless-io/Flat-native/issues/740)) ([2b2878b](https://github.com/netless-io/Flat-native/commit/2b2878b2d60560ef9d31485ef27c6dce4b43da4e))
* **desktop:** when leaving the room with the maximized window, there is no unmaximize ([#457](https://github.com/netless-io/Flat-native/issues/457)) ([5757695](https://github.com/netless-io/Flat-native/commit/57576953295b8959f859b8337f663fc645eb4bdb))
* **device-check:** cannot play mp3 ([#652](https://github.com/netless-io/Flat-native/issues/652)) ([8b64410](https://github.com/netless-io/Flat-native/commit/8b64410e9d71a7a7ffa6b82cf3a09e7d30dd3d64))
* **devtools:** a lot of extension server error: Operation failed: Permission denied ([#375](https://github.com/netless-io/Flat-native/issues/375)) ([55b8d3d](https://github.com/netless-io/Flat-native/commit/55b8d3df78627a6bc66e4e032bf51cd8e900c4c5))
* **edit-room:** correct initial periodic room end date ([#308](https://github.com/netless-io/Flat-native/issues/308)) ([c7d84c5](https://github.com/netless-io/Flat-native/commit/c7d84c5e609b6af0df5d6357408955c3e9ce5ed5))
* **electron:** cannot launch electron ([#645](https://github.com/netless-io/Flat-native/issues/645)) ([4657a87](https://github.com/netless-io/Flat-native/commit/4657a87b396349a59b8e0689c7062c87230ac4e1))
* **electron:** cannot open in after build ([#653](https://github.com/netless-io/Flat-native/issues/653)) ([5ac583b](https://github.com/netless-io/Flat-native/commit/5ac583bd1bea89f558ad506159e73fc051d28bec))
* **electron:** error when dev use electron-devtools-installer ([#646](https://github.com/netless-io/Flat-native/issues/646)) ([f9b8e6c](https://github.com/netless-io/Flat-native/commit/f9b8e6c16d8073b28e4d418e3a6c8b06bcabd204))
* **env:** miss SKIP_MAC_NOTARIZE logic ([#564](https://github.com/netless-io/Flat-native/issues/564)) ([c95d1c7](https://github.com/netless-io/Flat-native/commit/c95d1c7e5eed53a1f2dd4bb8470cb909cafa6e25))
* **flat-component:** fix type error ([#399](https://github.com/netless-io/Flat-native/issues/399)) ([c85f687](https://github.com/netless-io/Flat-native/commit/c85f687a84e0ec30b67a83c12725b5f069bfdc5d))
* **flat-component:** fixed an error in join room link ([#754](https://github.com/netless-io/Flat-native/issues/754)) ([426d95a](https://github.com/netless-io/Flat-native/commit/426d95a273acf3e41ce0ace307b94d7b756328a0))
* **flat-components:** add black background to video avatar ([#686](https://github.com/netless-io/Flat-native/issues/686)) ([fe55ad8](https://github.com/netless-io/Flat-native/commit/fe55ad8bdb4ef43955219f9f3ade3b5f99e7eb72))
* **flat-components:** cloud storage store missing actions ([#476](https://github.com/netless-io/Flat-native/issues/476)) ([87c97fb](https://github.com/netless-io/Flat-native/commit/87c97fb2c4c34ce6ae3e228d6882b9a61a2aa687))
* **flat-components:** edit room page build type error ([#610](https://github.com/netless-io/Flat-native/issues/610)) ([84be862](https://github.com/netless-io/Flat-native/commit/84be8629ab0400d1b9e17bf1ae28b5cf1713d054))
* **flat-components:** fix file list empty rename ([#483](https://github.com/netless-io/Flat-native/issues/483)) ([9e795d5](https://github.com/netless-io/Flat-native/commit/9e795d550523ed8aeb407cf4b784456cbefbcee5))
* **flat-components:** fix round button style ([#530](https://github.com/netless-io/Flat-native/issues/530)) ([4921d36](https://github.com/netless-io/Flat-native/commit/4921d360af88bd3d5eb9f6957d075ee752a0f7c8))
* **flat-components:** fix storybook less loader ([#408](https://github.com/netless-io/Flat-native/issues/408)) ([03f8ed9](https://github.com/netless-io/Flat-native/commit/03f8ed98aa4f9eefc5e3ec6d40b49b5efee015a6))
* **flat-components:** hide upload panel mask when not visible ([#586](https://github.com/netless-io/Flat-native/issues/586)) ([a93a6ee](https://github.com/netless-io/Flat-native/commit/a93a6ee4ac5e9a6ca424e8b91ddb812b6650c5c6))
* **flat-components:** missing css in production mode ([#467](https://github.com/netless-io/Flat-native/issues/467)) ([3e66e41](https://github.com/netless-io/Flat-native/commit/3e66e417d1c5dfa398a8fb304d74b8d032fcc03e))
* **flat-web:** 2 icons not import from module ([#737](https://github.com/netless-io/Flat-native/issues/737)) ([ecc1431](https://github.com/netless-io/Flat-native/commit/ecc1431428de7ec3679c0e8325d9710a8718e247))
* **flat-web:** always play tracks on user published ([#743](https://github.com/netless-io/Flat-native/issues/743)) ([4fd0bcd](https://github.com/netless-io/Flat-native/commit/4fd0bcdb7771d7dda5c436a8b85ef9f7d420c6eb))
* **flat-web:** don't play local audio track ([#741](https://github.com/netless-io/Flat-native/issues/741)) ([0f7d0e0](https://github.com/netless-io/Flat-native/commit/0f7d0e0f5df54c43411dbbd7982b309291c2a236))
* **flat-web:** lift up main page layout to prevent blinking ([#728](https://github.com/netless-io/Flat-native/issues/728)) ([9533234](https://github.com/netless-io/Flat-native/commit/953323434b4797f197f7e1ccdbeec7edf5b206df))
* **flat-web:** not close tracks when exiting room ([#722](https://github.com/netless-io/Flat-native/issues/722)) ([3cf5072](https://github.com/netless-io/Flat-native/commit/3cf5072abd9001e0b58b8f2206cd50227b036c82))
* **flat-web:** remove misleading error alert ([#735](https://github.com/netless-io/Flat-native/issues/735)) ([70ef156](https://github.com/netless-io/Flat-native/commit/70ef156d0f738fa7b72b9dcc58b8281f0eb626b9))
* **flat-web:** wrong assets url in build result ([#736](https://github.com/netless-io/Flat-native/issues/736)) ([59b70ae](https://github.com/netless-io/Flat-native/commit/59b70ae323df81a4711d2e140a872ab0c7d7b5c1))
* **flat-web:** wrong logic in using "title" ([#730](https://github.com/netless-io/Flat-native/issues/730)) ([c83c4f0](https://github.com/netless-io/Flat-native/commit/c83c4f0dc80272833d2ce252711e41dfdb853b2f))
* **homepage:** break long room title name ([#359](https://github.com/netless-io/Flat-native/issues/359)) ([60fe8b3](https://github.com/netless-io/Flat-native/commit/60fe8b36096ea467aa8a2cfe69bf41b1748c9859))
* **invite-modal:** fix crashes ([#326](https://github.com/netless-io/Flat-native/issues/326)) ([cfdd546](https://github.com/netless-io/Flat-native/commit/cfdd5462bf8f6b8c6f446e6bfa16a382f30a7f98))
* **launch:** not show stderr(console.error) in development ([#307](https://github.com/netless-io/Flat-native/issues/307)) ([e44f22a](https://github.com/netless-io/Flat-native/commit/e44f22abc2a9f9d0772855001e30a2a0064645a8))
* **login:** cannot show QR code in wechat login ([#313](https://github.com/netless-io/Flat-native/issues/313)) ([6b3012f](https://github.com/netless-io/Flat-native/commit/6b3012f04287f7b38a3ac13864074cd6d5582ca4))
* **login:** login check failed ([#348](https://github.com/netless-io/Flat-native/issues/348)) ([3632976](https://github.com/netless-io/Flat-native/commit/3632976f518c121b551d60ed89884c3dbc56b8b4))
* **MainPageLayout:** fix popMenu item styles ([#537](https://github.com/netless-io/Flat-native/issues/537)) ([d96c337](https://github.com/netless-io/Flat-native/commit/d96c337ce3b0a418159007c5ec70e2eeedc50d82))
* **main:** preload injection agora-electron-sdk probability of failure ([#352](https://github.com/netless-io/Flat-native/issues/352)) ([8b8993d](https://github.com/netless-io/Flat-native/commit/8b8993d12995d60db012b3c1df8adfa9d9f90793))
* **microphoneCheckPage:** fix device check logic ([#538](https://github.com/netless-io/Flat-native/issues/538)) ([bed7047](https://github.com/netless-io/Flat-native/commit/bed70479bafbfb040f1ebd49d89c60b8094fd0b8))
* **package:** consist react-i18next version ([#733](https://github.com/netless-io/Flat-native/issues/733)) ([9f5b835](https://github.com/netless-io/Flat-native/commit/9f5b8355550c7b6d5889f6781d064f88ffe0c28d))
* **pack:** ico resolution too low causes packaging Windows to fail ([#367](https://github.com/netless-io/Flat-native/issues/367)) ([47d455c](https://github.com/netless-io/Flat-native/commit/47d455c3c6cf6fb49912c8acf8296ef823e2c1a5))
* **pack:** no installation package is generated in pack Windows ([#369](https://github.com/netless-io/Flat-native/issues/369)) ([a3540b8](https://github.com/netless-io/Flat-native/commit/a3540b824e5e1ff8d6aed523f2185392320dd410))
* **pack:** not found preload.js file in production ([#366](https://github.com/netless-io/Flat-native/issues/366)) ([4cd8ffc](https://github.com/netless-io/Flat-native/commit/4cd8ffcb3381227b70f92ac9d66b9aef509b43d5))
* **pack:** open flat app fail in build product ([#353](https://github.com/netless-io/Flat-native/issues/353)) ([09df44f](https://github.com/netless-io/Flat-native/commit/09df44ffc68064b1448e256a41e77a02a57e49a1))
* **pages:** adjust RoomDetailPage & userSettingPage styles ([#548](https://github.com/netless-io/Flat-native/issues/548)) ([2365212](https://github.com/netless-io/Flat-native/commit/236521293a959e8f8b66bcaae983c5595a67caa0))
* **pages:** check update new version when click homePage component every time. ([#694](https://github.com/netless-io/Flat-native/issues/694)) ([a47b8b3](https://github.com/netless-io/Flat-native/commit/a47b8b3cd967e335319bc36f55af4d020366d3b7))
* **pkg-types:** lint-stage failed ([#299](https://github.com/netless-io/Flat-native/issues/299)) ([262268a](https://github.com/netless-io/Flat-native/commit/262268a0159e72c649388c29a69f634727213525))
* **preload:** preload sometimes fails to execute the code inside correctly ([#362](https://github.com/netless-io/Flat-native/issues/362)) ([59dea3b](https://github.com/netless-io/Flat-native/commit/59dea3b8e4e7d81f0a5dc7b92aae3b44e8f24809))
* **preview:** add bottom center style to the pagination element ([#817](https://github.com/netless-io/Flat-native/issues/817)) ([017ab90](https://github.com/netless-io/Flat-native/commit/017ab90d6b92d60b3fb989fd6ef5a15e06ffc178))
* **region:** policy url incorrect ([#803](https://github.com/netless-io/Flat-native/issues/803)) ([da02f73](https://github.com/netless-io/Flat-native/commit/da02f7333a97b4fd97fbe8d240c90a5290c31b7f))
* **region:** set region when in room ([#802](https://github.com/netless-io/Flat-native/issues/802)) ([8f7ed14](https://github.com/netless-io/Flat-native/commit/8f7ed145250fb47beb442b0cf5be35489133bb38))
* **region:** should save region when create room ([#825](https://github.com/netless-io/Flat-native/issues/825)) ([7a44a0e](https://github.com/netless-io/Flat-native/commit/7a44a0ec0fa70f8c1fa515e652036878a09edac8))
* **renderer:** optimize invite modal(title use current user name) ([cfa0517](https://github.com/netless-io/Flat-native/commit/cfa0517dbabda9b256f423ec32aa26177a82255a))
* **replay:** update rtm message when replaying ([#534](https://github.com/netless-io/Flat-native/issues/534)) ([6c4ef42](https://github.com/netless-io/Flat-native/commit/6c4ef42fca31b7a575478218890d4cca668ae0bb))
* **replay:** use new ErrorPage ([#680](https://github.com/netless-io/Flat-native/issues/680)) ([cb910db](https://github.com/netless-io/Flat-native/commit/cb910dbb45ee4daea9d4296f0fa65c6a972de10a))
* **rtc:** enable local video on camera testing ([#560](https://github.com/netless-io/Flat-native/issues/560)) ([66bd999](https://github.com/netless-io/Flat-native/commit/66bd9997c09b7de963968a8d94a680172da91a0f))
* **rtm:** remove user before add ([#796](https://github.com/netless-io/Flat-native/issues/796)) ([0f7e229](https://github.com/netless-io/Flat-native/commit/0f7e229e77560b1bf4a795e8e7a382162828f91e))
* **script:** bootstrap script path error ([#716](https://github.com/netless-io/Flat-native/issues/716)) ([b8b5bec](https://github.com/netless-io/Flat-native/commit/b8b5bec8865882f1f45c6a75f12e04d46eed2c72))
* **script:** postinstall script error in main-app ([#464](https://github.com/netless-io/Flat-native/issues/464)) ([1131ae7](https://github.com/netless-io/Flat-native/commit/1131ae78fc8a5154b5926955e221472e2d6f837c))
* **script:** use flat replace main-app in root package scripts ([#687](https://github.com/netless-io/Flat-native/issues/687)) ([5c8d09b](https://github.com/netless-io/Flat-native/commit/5c8d09b0aaf1d538991173f8822812bafdbee8c1))
* **server:** correct server api ([#350](https://github.com/netless-io/Flat-native/issues/350)) ([429c9a0](https://github.com/netless-io/Flat-native/commit/429c9a0adb9259c0cb7322f8a079b71acc9c6d9c))
* **ship:** typo ([#505](https://github.com/netless-io/Flat-native/issues/505)) ([6726d2e](https://github.com/netless-io/Flat-native/commit/6726d2ed74be230610a0fb3694cc41d7ed811a41))
* **small-class:** avatar user name overflow ([#575](https://github.com/netless-io/Flat-native/issues/575)) ([e7c150b](https://github.com/netless-io/Flat-native/commit/e7c150bd45b6b4246df0fcaf3f33e773c8945ce9))
* **topbar:** typo ([#609](https://github.com/netless-io/Flat-native/issues/609)) ([79bf7c3](https://github.com/netless-io/Flat-native/commit/79bf7c3f9fe7ed05a9dc3c942b1147b12ca06bca))
* **ui:** remove unknown char ([#578](https://github.com/netless-io/Flat-native/issues/578)) ([c156715](https://github.com/netless-io/Flat-native/commit/c156715ae5fcbcbe44abde85a2e7eec5f65b7fb4))
* **update-version:** remove modalVisible in GlobalStore ([#567](https://github.com/netless-io/Flat-native/issues/567)) ([e670d6e](https://github.com/netless-io/Flat-native/commit/e670d6e4a9098a1ca60622217a2f788d1fbbdbc8))
* **WeChatLogin:** spin element covered English text of WeChat login. ([#794](https://github.com/netless-io/Flat-native/issues/794)) ([8ebae66](https://github.com/netless-io/Flat-native/commit/8ebae66dd39fa5a8a1ead376639e51154b6378c8))
* **whiteboard:** guard scalePptToFit() ([#550](https://github.com/netless-io/Flat-native/issues/550)) ([6ec35ed](https://github.com/netless-io/Flat-native/commit/6ec35ed6cf2d7269e273e19c5b5b4f7c69fece24))
* **whiteboard:** line feed display error in ppt ([#584](https://github.com/netless-io/Flat-native/issues/584)) ([b591512](https://github.com/netless-io/Flat-native/commit/b5915128ea0b1356b39dab87e2677828a989816b))
* **window:** no center when entering the room, no reset size when exiting the room ([#510](https://github.com/netless-io/Flat-native/issues/510)) ([2c138d9](https://github.com/netless-io/Flat-native/commit/2c138d974cc02a06c9ba27dfa7404e0e446557d1))
* **window:** not reset window size in exit ClassRoom/Replay ([#398](https://github.com/netless-io/Flat-native/issues/398)) ([3bab1b3](https://github.com/netless-io/Flat-native/commit/3bab1b3f1211a18352c3b38c038d76e5d067dfd3))
* **worker:** add multiple baseURL to match fetch request ([#833](https://github.com/netless-io/Flat-native/issues/833)) ([816e305](https://github.com/netless-io/Flat-native/commit/816e3056e0bae3a4abdf435f1e8cdb501cbbb420))


### Features

* **classroom:** add network quality check ([#300](https://github.com/netless-io/Flat-native/issues/300)) ([589c38c](https://github.com/netless-io/Flat-native/commit/589c38c4069a51b278ee7bee8802c661b5e06501))
* **classroom:** add record hint tips ([#334](https://github.com/netless-io/Flat-native/issues/334)) ([134e586](https://github.com/netless-io/Flat-native/commit/134e586719904fc6904bcc10f2c3205be7f2ef51))
* **cloud-recording:** add user avatar ([#554](https://github.com/netless-io/Flat-native/issues/554)) ([16e87a7](https://github.com/netless-io/Flat-native/commit/16e87a7bb0274dfcc8363124dfa527e19debc102))
* **cloud-storage:** add cloud-storage modal to room ([#487](https://github.com/netless-io/Flat-native/issues/487)) ([d0a96e1](https://github.com/netless-io/Flat-native/commit/d0a96e14eac000cc91a695643e544af059e63016))
* **cloud-storage:** cancel upload ([#480](https://github.com/netless-io/Flat-native/issues/480)) ([58698f0](https://github.com/netless-io/Flat-native/commit/58698f0cc9053044ef28e832fb72f854c31c9795))
* **CloudStoragePage:** add preview components to cloud storage page ([#837](https://github.com/netless-io/Flat-native/issues/837)) ([e80badb](https://github.com/netless-io/Flat-native/commit/e80badb2d927d84e234b972d35758cf9708470bc))
* **desktop:** add app update logic(UI not implemented yet) ([#503](https://github.com/netless-io/Flat-native/issues/503)) ([56cdcf1](https://github.com/netless-io/Flat-native/commit/56cdcf1c9f07492c9c87d8117331db994c1ca2ee))
* **desktop:** customize url protocol to join room on homepage ([#749](https://github.com/netless-io/Flat-native/issues/749)) ([7458149](https://github.com/netless-io/Flat-native/commit/745814976c4befea4b2b4869d9039aa7fb9b6bb9))
* **error-tips:** add error tips when server request failed ([#304](https://github.com/netless-io/Flat-native/issues/304)) ([ad9708e](https://github.com/netless-io/Flat-native/commit/ad9708e318172d88bc5fd34f5ee10261f50bc1a4))
* **flat-component:** add CloudStorage i18n ([#640](https://github.com/netless-io/Flat-native/issues/640)) ([6903937](https://github.com/netless-io/Flat-native/commit/6903937126e58d7ff3fa682a911d3c7982b4ae56))
* **flat-component:** Add disabled mode to ClassPicker component. ([#675](https://github.com/netless-io/Flat-native/issues/675)) ([a6916fc](https://github.com/netless-io/Flat-native/commit/a6916fc28938377486094115e6fc347d14f50260))
* **flat-component:** add large mode to ClassPicker component ([#668](https://github.com/netless-io/Flat-native/issues/668)) ([d794a6d](https://github.com/netless-io/Flat-native/commit/d794a6d797b241edc6c3d1238b7936720fe39500))
* **flat-component:** add LoginChannel component in LoginPage ([#596](https://github.com/netless-io/Flat-native/issues/596)) ([221197a](https://github.com/netless-io/Flat-native/commit/221197a223029956bc080ee3495f2347630465f8))
* **flat-component:** add MainPageHeader component to storybook ([#642](https://github.com/netless-io/Flat-native/issues/642)) ([844e574](https://github.com/netless-io/Flat-native/commit/844e574c0e21ea7cbe382f5cbd0c48969ef57a65))
* **flat-component:** add MoremMenu component to storybook ([#637](https://github.com/netless-io/Flat-native/issues/637)) ([9d8258e](https://github.com/netless-io/Flat-native/commit/9d8258efd830c78990f1bd59139c5b531d6331b9))
* **flat-component:** add new nav component to MainPageLayout ([#693](https://github.com/netless-io/Flat-native/issues/693)) ([6d1c91d](https://github.com/netless-io/Flat-native/commit/6d1c91d2905880439b9f91a6c93bbec66b40da17))
* **flat-component:** add PeriodicRoomPanel component to storybook ([#633](https://github.com/netless-io/Flat-native/issues/633)) ([cc0ccde](https://github.com/netless-io/Flat-native/commit/cc0ccde188125bbd2400b660ac1cd92206c49d09))
* **flat-component:** add return to previous page button to MainPageNavHorizontal. ([#720](https://github.com/netless-io/Flat-native/issues/720)) ([be30e5e](https://github.com/netless-io/Flat-native/commit/be30e5ec05b6445e3eedb31083e86217b19255fa))
* **flat-component:** add room list components ([#426](https://github.com/netless-io/Flat-native/issues/426)) ([caec6ba](https://github.com/netless-io/Flat-native/commit/caec6babe039f927f7caa80f2a1c24e05344ba0d))
* **flat-component:** design class picker component && adjust the directory structure ([#583](https://github.com/netless-io/Flat-native/issues/583)) ([7605743](https://github.com/netless-io/Flat-native/commit/7605743a50943b69cca117c526f908c2cae3e9ac))
* **flat-component:** design LoginPage component ([#590](https://github.com/netless-io/Flat-native/issues/590)) ([66af6a9](https://github.com/netless-io/Flat-native/commit/66af6a9dfa8b575821636d9227c31edd3fbba298))
* **flat-components:** add animated upload panel in compact mode ([#445](https://github.com/netless-io/Flat-native/issues/445)) ([8020f68](https://github.com/netless-io/Flat-native/commit/8020f68252d7d5c2f95131b7af71d148e6a2579d))
* **flat-components:** add clickable file list titles ([#465](https://github.com/netless-io/Flat-native/issues/465)) ([2101548](https://github.com/netless-io/Flat-native/commit/21015484697baccad8e9f35dc9c174b61f68cef4))
* **flat-components:** add cloud storage converting ([#470](https://github.com/netless-io/Flat-native/issues/470)) ([4fe9a13](https://github.com/netless-io/Flat-native/commit/4fe9a133c889c79aeb80c6cd8a95c5b0f088cf8a))
* **flat-components:** add Cloud Storage panel container ([#444](https://github.com/netless-io/Flat-native/issues/444)) ([e0c19e1](https://github.com/netless-io/Flat-native/commit/e0c19e1bf5b60cdd6b0b5acf8f7b51394b002b58))
* **flat-components:** add Cloud Storage Upload Items ([#407](https://github.com/netless-io/Flat-native/issues/407)) ([d8ed8b2](https://github.com/netless-io/Flat-native/commit/d8ed8b28625f2348df8bf5712f3873898bca8a8f))
* **flat-components:** add CloudStorageFileList ([#387](https://github.com/netless-io/Flat-native/issues/387)) ([1b11427](https://github.com/netless-io/Flat-native/commit/1b1142775baff54081bbab85329022f2f8b27283))
* **flat-components:** add compact upload panel ([#432](https://github.com/netless-io/Flat-native/issues/432)) ([404d763](https://github.com/netless-io/Flat-native/commit/404d763407f99f05a97b4ec568666ad91d0e1e21))
* **flat-components:** add EditRoomBody ([#607](https://github.com/netless-io/Flat-native/issues/607)) ([1831e4d](https://github.com/netless-io/Flat-native/commit/1831e4d1abe276174f4a83cf19c817046b423f3f))
* **flat-components:** add fancy scrollbar ([#493](https://github.com/netless-io/Flat-native/issues/493)) ([916aacc](https://github.com/netless-io/Flat-native/commit/916aaccf615a82380c4416ee3a82ae733cac9e9b))
* **flat-components:** add global style to input, radio, checkbo, button ([#528](https://github.com/netless-io/Flat-native/issues/528)) ([2a83d92](https://github.com/netless-io/Flat-native/commit/2a83d92dbbf44d469494741319a570f09f82c1d5))
* **flat-components:** add home page hero button ([#418](https://github.com/netless-io/Flat-native/issues/418)) ([dedabb9](https://github.com/netless-io/Flat-native/commit/dedabb9e1d68f3c43e49d7b0dd00325961f7339b))
* **flat-components:** add InviteModal and RemoveDetailModal ([#618](https://github.com/netless-io/Flat-native/issues/618)) ([a7f2b4f](https://github.com/netless-io/Flat-native/commit/a7f2b4fcdb41c9ddd76b0cefddf34e19ab3cff1b))
* **flat-components:** add join link content to InviteModal component ([#776](https://github.com/netless-io/Flat-native/issues/776)) ([5048af0](https://github.com/netless-io/Flat-native/commit/5048af08af0eedf2c5d0ef87853e77e96748adf4))
* **flat-components:** add join link to InviteModal component. ([#745](https://github.com/netless-io/Flat-native/issues/745)) ([e77f92d](https://github.com/netless-io/Flat-native/commit/e77f92ddeab1fae2675a6b278fb94f9235a8e331))
* **flat-components:** add LoadingPage ([#671](https://github.com/netless-io/Flat-native/issues/671)) ([9e3271e](https://github.com/netless-io/Flat-native/commit/9e3271ecc5b97c733c1b6cb4f9256efd3015fc18))
* **flat-components:** add remove history room modal to flat-components ([#724](https://github.com/netless-io/Flat-native/issues/724)) ([9dbdf9d](https://github.com/netless-io/Flat-native/commit/9dbdf9d86e9e21910334d245b99c4452c572272e))
* **flat-components:** add rename panel ([#474](https://github.com/netless-io/Flat-native/issues/474)) ([2989b8e](https://github.com/netless-io/Flat-native/commit/2989b8e42fa8b9fb0747dd59770efd24be7d1453))
* **flat-components:** add room list item buttons ([#489](https://github.com/netless-io/Flat-native/issues/489)) ([f9a7e0b](https://github.com/netless-io/Flat-native/commit/f9a7e0bbc7cb3ebb7489e6b285b7e583419f6063))
* **flat-components:** add storybook flat brand image ([#389](https://github.com/netless-io/Flat-native/issues/389)) ([6502433](https://github.com/netless-io/Flat-native/commit/6502433007f025b9e11ccae4f88b35cec4b5f6d8))
* **flat-components:** add storybook i18n switching ([#635](https://github.com/netless-io/Flat-native/issues/635)) ([4cd5102](https://github.com/netless-io/Flat-native/commit/4cd5102790a37f01ed58f3c9a73cf681048073d4))
* **flat-components:** add theme css ([#491](https://github.com/netless-io/Flat-native/issues/491)) ([6969875](https://github.com/netless-io/Flat-native/commit/6969875161f2e606a8447f7765898705ba62b2c3))
* **flat-components:** add upload panel ([#428](https://github.com/netless-io/Flat-native/issues/428)) ([3c61baa](https://github.com/netless-io/Flat-native/commit/3c61baa8fb93540697c1155c7dd4c07f9507e083))
* **flat-components:** ChatPanel ([#655](https://github.com/netless-io/Flat-native/issues/655)) ([90f0c56](https://github.com/netless-io/Flat-native/commit/90f0c56e571f787c6e6fb7db3f0a27000107a388))
* **flat-components:** ClassroomPage except chat panel and video avatar ([#632](https://github.com/netless-io/Flat-native/issues/632)) ([db281da](https://github.com/netless-io/Flat-native/commit/db281da5b181a53c2ff9f2ca2a82b66f5cd720c1))
* **flat-components:** design RoomDetailPage module in storybook ([#623](https://github.com/netless-io/Flat-native/issues/623)) ([04218cb](https://github.com/netless-io/Flat-native/commit/04218cb7252989d7ff4d209a22e8b1eb313a8a55))
* **flat-components:** extract RoomListSkeletions ([#689](https://github.com/netless-io/Flat-native/issues/689)) ([c86c546](https://github.com/netless-io/Flat-native/commit/c86c546b5580bb9514bac5460dda0966d8d7df43))
* **flat-components:** video avatar ([#641](https://github.com/netless-io/Flat-native/issues/641)) ([3c15496](https://github.com/netless-io/Flat-native/commit/3c1549664de41bb3a3ce4734987a3a91ebd3c5bc))
* **flat-web:** add big class page ([#719](https://github.com/netless-io/Flat-native/issues/719)) ([0cac4f0](https://github.com/netless-io/Flat-native/commit/0cac4f077739f4ea97039c764bddb6c976313037))
* **flat-web:** add CloudStoragePage to flat-web. ([#715](https://github.com/netless-io/Flat-native/issues/715)) ([60382cf](https://github.com/netless-io/Flat-native/commit/60382cfa440b2822e1f20996d421b45d3cf992c8))
* **flat-web:** add HomePage to Flat-web ([#702](https://github.com/netless-io/Flat-native/issues/702)) ([92f9106](https://github.com/netless-io/Flat-native/commit/92f9106d1ca9f9f27b5baf9b665f84a57ba429df))
* **flat-web:** add join page to flat-web. ([#746](https://github.com/netless-io/Flat-native/issues/746)) ([0575170](https://github.com/netless-io/Flat-native/commit/05751707d4ab1af1f505463b51cb271ef1cb1609))
* **flat-web:** add nav right menus ([#810](https://github.com/netless-io/Flat-native/issues/810)) ([d1d98ed](https://github.com/netless-io/Flat-native/commit/d1d98ed1562f40f5745d4b50a310ede0ad28583c))
* **flat-web:** add one to one class page to flat-web ([#725](https://github.com/netless-io/Flat-native/issues/725)) ([400e874](https://github.com/netless-io/Flat-native/commit/400e874b2a35fb3497bbb103d74a87863f5b1108))
* **flat-web:** add replay page ([#726](https://github.com/netless-io/Flat-native/issues/726)) ([210ebd9](https://github.com/netless-io/Flat-native/commit/210ebd94d2a1c9f9ca5a992ca5cf8d7222003c49))
* **flat-web:** add RoomDetailPage and PeriodicRoomDetailPage to flat-web. ([#703](https://github.com/netless-io/Flat-native/issues/703)) ([5018848](https://github.com/netless-io/Flat-native/commit/50188482f48fa242f5a5626f6c0d443c58c44fec))
* **flat-web:** add rtc & rtm ([#717](https://github.com/netless-io/Flat-native/issues/717)) ([fc6cd73](https://github.com/netless-io/Flat-native/commit/fc6cd733c8eae690ec886112c615eb39984c1445))
* **flat-web:** add small class page to flat-web ([#723](https://github.com/netless-io/Flat-native/issues/723)) ([1cd452f](https://github.com/netless-io/Flat-native/commit/1cd452f7a4f77dd76368b3237afc361a291bbc68))
* **flat-web:** add user settings related pages to the flat-web. ([#709](https://github.com/netless-io/Flat-native/issues/709)) ([e453f9d](https://github.com/netless-io/Flat-native/commit/e453f9dab75982584ab450c874898d62a6497b95))
* **flat-web:** add UserScheduledPage,ModifyOrdinaryRoomPage,ModifyPeriodicRoomPage to flat-component ([#705](https://github.com/netless-io/Flat-native/issues/705)) ([77e51aa](https://github.com/netless-io/Flat-native/commit/77e51aa269bbcbb6faa1633698df462e0bdc4867))
* **flat-web:** setup project ([#696](https://github.com/netless-io/Flat-native/issues/696)) ([0fa4943](https://github.com/netless-io/Flat-native/commit/0fa4943db7539cfdd451459e6bdd17db96b84cdc))
* **i18n:** add all tips ([#765](https://github.com/netless-io/Flat-native/issues/765)) ([026e679](https://github.com/netless-io/Flat-native/commit/026e67969b41798caa7386322642ed5f5c32451e))
* **i18n:** add ChatPanel ([#660](https://github.com/netless-io/Flat-native/issues/660)) ([101b891](https://github.com/netless-io/Flat-native/commit/101b891ce6546c116bacdaf92137226ba1b67fe5))
* **i18n:** add ClassroomPage ([#662](https://github.com/netless-io/Flat-native/issues/662)) ([9d3353f](https://github.com/netless-io/Flat-native/commit/9d3353f252ff20fb14ed258faee90442a79b2e27))
* **i18n:** add CloudStoragePage ([#758](https://github.com/netless-io/Flat-native/issues/758)) ([94a092f](https://github.com/netless-io/Flat-native/commit/94a092f97e9e7ac005ccc0a7576d4d2427536bb9))
* **i18n:** add EditRoomPage i18n ([#734](https://github.com/netless-io/Flat-native/issues/734)) ([6e73c70](https://github.com/netless-io/Flat-native/commit/6e73c7012c692510f34c8a45861d40ddadf528c2))
* **i18n:** add ErrorCode and DeviceCheck i18n ([#774](https://github.com/netless-io/Flat-native/issues/774)) ([6e5c84b](https://github.com/netless-io/Flat-native/commit/6e5c84b49d0c3605d35d3bbf3cc0d20442f68834))
* **i18n:** add JoinPage i18n ([#785](https://github.com/netless-io/Flat-native/issues/785)) ([6215b78](https://github.com/netless-io/Flat-native/commit/6215b78be9925894f260564c20cb482e6611fb49))
* **i18n:** add sample i18n for HomePage components ([#669](https://github.com/netless-io/Flat-native/issues/669)) ([9b0e57f](https://github.com/netless-io/Flat-native/commit/9b0e57fa4eb1d1fb61e97ba318e97709987f236b))
* **i18n:** add server i18n ([#813](https://github.com/netless-io/Flat-native/issues/813)) ([c1aba03](https://github.com/netless-io/Flat-native/commit/c1aba0362dbb117a0132031f593e4dded33ed49c))
* **i18n:** add translations of titles ([#750](https://github.com/netless-io/Flat-native/issues/750)) ([7ee2c13](https://github.com/netless-io/Flat-native/commit/7ee2c135e1c76761cc332a8f63616f6c95c8a3b0))
* **i18n:** AppUpgradeModal and CloudStorageContainer ([#742](https://github.com/netless-io/Flat-native/issues/742)) ([43c5697](https://github.com/netless-io/Flat-native/commit/43c569718b14f6aaa3ab8247fa239c17dbdf530e))
* **i18n:** flat-desktop support language switching ([#775](https://github.com/netless-io/Flat-native/issues/775)) ([0e2854c](https://github.com/netless-io/Flat-native/commit/0e2854c09fce2daf767a752da44e3e62284a4ff4))
* **i18n:** translate texts in utils/room.ts ([#695](https://github.com/netless-io/Flat-native/issues/695)) ([d012b57](https://github.com/netless-io/Flat-native/commit/d012b57d481c89abdc8694ede965bd75728ac4ca))
* **login:** add wechat QR code spinner ([#309](https://github.com/netless-io/Flat-native/issues/309)) ([bc5c8e6](https://github.com/netless-io/Flat-native/commit/bc5c8e63c8e2f71f4f5a898811e4a3eb18fce13b))
* **main-app:** set protocol client ([#602](https://github.com/netless-io/Flat-native/issues/602)) ([659c6ae](https://github.com/netless-io/Flat-native/commit/659c6aedc591041a4bfa1e347fdd2a88a32e2847))
* **main-room-list:** add loading skeletons ([#311](https://github.com/netless-io/Flat-native/issues/311)) ([5657f3c](https://github.com/netless-io/Flat-native/commit/5657f3c0e0745997dd5c481cb790dd6209a8eb2f))
* **main:** enable electron nodeIntegrationInSubFrames window option ([#337](https://github.com/netless-io/Flat-native/issues/337)) ([ebea2f8](https://github.com/netless-io/Flat-native/commit/ebea2f86470ff6dc2b7bd0b380eab8d8580769d0))
* **pages:** finish githubLogin Page ([#598](https://github.com/netless-io/Flat-native/issues/598)) ([5f801a9](https://github.com/netless-io/Flat-native/commit/5f801a9eca828841acc7b85bbe9814d736a41ff9))
* **pages:** Using ClassPicker component in the CreateRoomBox ([#673](https://github.com/netless-io/Flat-native/issues/673)) ([193c1b3](https://github.com/netless-io/Flat-native/commit/193c1b3523fdf33b33fa4a9f372807c81f69e8c2))
* **preview:** add resource preview to flat-web. ([#812](https://github.com/netless-io/Flat-native/issues/812)) ([19a3fbb](https://github.com/netless-io/Flat-native/commit/19a3fbb5b363c4bc0fe759167b75d02d5a40c40d))
* **render:** add preloader utils ([#502](https://github.com/netless-io/Flat-native/issues/502)) ([9b81c8c](https://github.com/netless-io/Flat-native/commit/9b81c8c137c34aa2c9b980e9405a26e2769c435f))
* **room-detail:** add localed time diff between begin and end time ([#318](https://github.com/netless-io/Flat-native/issues/318)) ([fb5aead](https://github.com/netless-io/Flat-native/commit/fb5aead2bf5ddf754519fe526fabb4027420ee0e))
* **rtm:** exit room when user login on other device. ([#755](https://github.com/netless-io/Flat-native/issues/755)) ([b09b39d](https://github.com/netless-io/Flat-native/commit/b09b39d6b378e63c500e425aa4964ea044368b77))
* **URLProtocol:** support browser launch flat join room ([#772](https://github.com/netless-io/Flat-native/issues/772)) ([f9e4fa6](https://github.com/netless-io/Flat-native/commit/f9e4fa67410863f454bb2794f3531232de4d98b8)), closes [#756](https://github.com/netless-io/Flat-native/issues/756) [#767](https://github.com/netless-io/Flat-native/issues/767) [#768](https://github.com/netless-io/Flat-native/issues/768) [#769](https://github.com/netless-io/Flat-native/issues/769) [#770](https://github.com/netless-io/Flat-native/issues/770)
* **UserScheduledPage:** complete room scheduling process. ([f259062](https://github.com/netless-io/Flat-native/commit/f25906229bb3e0f88d1b0191ed1d21dd7e265c3f))
* **version-upgrade:** finish version upgrade features ([#561](https://github.com/netless-io/Flat-native/issues/561)) ([3be4369](https://github.com/netless-io/Flat-native/commit/3be436917d912bf151a76bd4962d736947b0d3ce))
* **whiteboard:** add drag and drop image support ([#801](https://github.com/netless-io/Flat-native/issues/801)) ([217510d](https://github.com/netless-io/Flat-native/commit/217510d1d26b6ae4279bb8addd007d5b34274d21))
* **whiteboard:** add the preload resource feature to flat-web ([#798](https://github.com/netless-io/Flat-native/issues/798)) ([7b9c7d4](https://github.com/netless-io/Flat-native/commit/7b9c7d43f39b5676fca71f34fb95eb4dd35d5b81))
* **whiteboardStore:** preload file when the whiteboard scene state has been changed ([#795](https://github.com/netless-io/Flat-native/issues/795)) ([3739ee1](https://github.com/netless-io/Flat-native/commit/3739ee1f2a9e6fed799c98b4662a6bb16067b794))
* **window:** prevent sleep when in room ([#391](https://github.com/netless-io/Flat-native/issues/391)) ([76e39bd](https://github.com/netless-io/Flat-native/commit/76e39bd555541809bf6d5d2d9a63a83dc179942f))
* **window:** support resizable and maximizable in ClassRoom / Replay ([#388](https://github.com/netless-io/Flat-native/issues/388)) ([0137045](https://github.com/netless-io/Flat-native/commit/013704539b3b83bd3a0306ed44d18f667a15fa3c))
* **window:** warp window exit event(add modal confirm) ([6b8f740](https://github.com/netless-io/Flat-native/commit/6b8f740463c3feca810f8c705fe396864351d2f3))


### Reverts

* Revert "feat(desktop): customize url protocol to join room on homepage (#749)" (#751) ([b58da8d](https://github.com/netless-io/Flat-native/commit/b58da8d98681907ad1e0ceb0993d6133f86b37aa)), closes [#749](https://github.com/netless-io/Flat-native/issues/749) [#751](https://github.com/netless-io/Flat-native/issues/751)



