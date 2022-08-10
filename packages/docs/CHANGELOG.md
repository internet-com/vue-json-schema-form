# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# 1.15.0 (2022-08-10)


### Bug Fixes

* **arraymultiselect:** 修复type array 多选框不支持配置 uiwidget ([f9b577c](https://github.com/internet-com/vue-json-schema-form/commit/f9b577c479a2c3dd0233952c50e74079c1e4a5ac))
* **doc:** 修复docs:build 报错，修改demo默然 ClientOnly ([dde714c](https://github.com/internet-com/vue-json-schema-form/commit/dde714cfa90ed2514dc2efc6f1f9121f53b2880a))
* **lib:** 添加严格模式配置，更精准计算anyOf 默认值 ([2cd65bb](https://github.com/internet-com/vue-json-schema-form/commit/2cd65bb5f275a021f1cc368e4c63387163c94d57)), closes [#157](https://github.com/internet-com/vue-json-schema-form/issues/157)
* **vue3-antd:** 修复form label 双冒号问题 ([5b4f16c](https://github.com/internet-com/vue-json-schema-form/commit/5b4f16c3c1a4f4b784c2fd5c1fbe7eec40cf8d7b)), closes [#46](https://github.com/internet-com/vue-json-schema-form/issues/46)


### Features

* **core:** widget 节点直接配置onChange ([2d2264b](https://github.com/internet-com/vue-json-schema-form/commit/2d2264b004c3b6586e225c563bf03ca52fc5e53a))
* **customrule:** 添加自定义校验方法 ([017272d](https://github.com/internet-com/vue-json-schema-form/commit/017272dd60c9da3117262749180fbe624d14979b))
* **enum uischema:** enumNames 和anyOf const 形式，支持通过uiSchema配置枚举项标题 ([62698e4](https://github.com/internet-com/vue-json-schema-form/commit/62698e4e1f778f5c90d626513421c07918064cbc))
* **errorschema:** errorSchema 支持直接配置在 uiSchema中 ([5996acc](https://github.com/internet-com/vue-json-schema-form/commit/5996acc04788d3dcad2176cf76e10b96e57c715d)), closes [#7](https://github.com/internet-com/vue-json-schema-form/issues/7)
* **field:** 自定义 field 支持 ui:fieldProps 配置传入附加props ([7bea3a6](https://github.com/internet-com/vue-json-schema-form/commit/7bea3a6b2ecb4f78dde5d0abd721108d8bfe6ec0))
* **lib:** form-mounted event 添加formData 参数 ([c54202c](https://github.com/internet-com/vue-json-schema-form/commit/c54202c27304add9636a7062c05c80c60fc200a6))
* **lib:** uploadWidget 组件支持slots 配置function 接受createElement参数 ([2ceebcb](https://github.com/internet-com/vue-json-schema-form/commit/2ceebcb6970bf0a46d0f8a80acb6dbe3ebcd7b80))
* **lib:** 支持配置 getWidget function回调接收 widget组件实例 ([01b9915](https://github.com/internet-com/vue-json-schema-form/commit/01b9915334b053a940440fff3546e263ba10894c)), closes [#25](https://github.com/internet-com/vue-json-schema-form/issues/25)
* **lib:** 支持配置 slots ([27f1501](https://github.com/internet-com/vue-json-schema-form/commit/27f1501eda01eabd4a723656be56904e9cb0f069)), closes [#45](https://github.com/internet-com/vue-json-schema-form/issues/45)
* **lib:** 添加 defaultSelectFirstOption 配置 ([bf17a61](https://github.com/internet-com/vue-json-schema-form/commit/bf17a616fc000194ddda1259a708b9c52571d3fd)), closes [#171](https://github.com/internet-com/vue-json-schema-form/issues/171)
* **lib:** 添加 fallback-label 参数 ([cd2d8c3](https://github.com/internet-com/vue-json-schema-form/commit/cd2d8c3ed72b9bc03e44eb5b86eb1b18fe67c34c)), closes [#45](https://github.com/internet-com/vue-json-schema-form/issues/45)
* **lib:** 调整 widget onChange prop参数格式，添加 formData参数 ([4c441fc](https://github.com/internet-com/vue-json-schema-form/commit/4c441fce239ade40b10a42bf361c3ee920a044ed)), closes [#45](https://github.com/internet-com/vue-json-schema-form/issues/45)
* **lib ui-schema:** ui-schema 支持配置 ui:hidden 表达式实现数据联动 ([13737fe](https://github.com/internet-com/vue-json-schema-form/commit/13737fea1db56763239be5027a2f375447ca8f70))
* **schema-generator:** 添加导入功能 ([93ea158](https://github.com/internet-com/vue-json-schema-form/commit/93ea158a66dab8f845e8ac0e1fa76c041f0d8abb))
* **vjsf:** 更新渲染表单 inline样式 ([30888ca](https://github.com/internet-com/vue-json-schema-form/commit/30888ca38dd42b0d4ed11e185d63cf1ec0bcc2cb))
* **vjsf dependencies:** 支持 object dependencies property ,scheam 依赖不支持 ([1cda05d](https://github.com/internet-com/vue-json-schema-form/commit/1cda05d78bc312ee1a631f480f2fec3a15f4c5b3))
* **vjsf ui:** 添加ui:showIndexNumber，支持配置 array item 显示序号 ([b8e8389](https://github.com/internet-com/vue-json-schema-form/commit/b8e8389ba0bbc41ec24a88af5da0cfc3dffd6bcd))
* **vue2:** vue2 添加 widgetListeners 配置 ([50348c2](https://github.com/internet-com/vue-json-schema-form/commit/50348c27e72813ea16fdcfcea46e6450ccf06018)), closes [#45](https://github.com/internet-com/vue-json-schema-form/issues/45)
* **vue3:** init vue3 core ([df2c1fe](https://github.com/internet-com/vue-json-schema-form/commit/df2c1fe9873a5e13eeafff924f7d9ab369824fbd))
* **vue3-ant:** 更新初始化 ([71a2810](https://github.com/internet-com/vue-json-schema-form/commit/71a281045af11f215333050396aa546dd5e78b88)), closes [#27](https://github.com/internet-com/vue-json-schema-form/issues/27) [#27](https://github.com/internet-com/vue-json-schema-form/issues/27) [#27](https://github.com/internet-com/vue-json-schema-form/issues/27) [#40](https://github.com/internet-com/vue-json-schema-form/issues/40)
* **vue3-core:** 允许传递props至formFooter ([60ee613](https://github.com/internet-com/vue-json-schema-form/commit/60ee613bda30b818adccd98ad73949ff111df74c))
* **vue3-core:** 完成 @lljj/vue3-form-element package，更新文档 ([a4d65db](https://github.com/internet-com/vue-json-schema-form/commit/a4d65db6c58f96e6afe6e31068c09e914e6b6579)), closes [#27](https://github.com/internet-com/vue-json-schema-form/issues/27)
* **widget:** widget 组件支持透传 $attrs ([1a86316](https://github.com/internet-com/vue-json-schema-form/commit/1a86316500968574f30fe2c2e676c6211930ec2e)), closes [#16](https://github.com/internet-com/vue-json-schema-form/issues/16)
* 更新文档 ([df34da2](https://github.com/internet-com/vue-json-schema-form/commit/df34da2a47a07d06c42a0cbc6a90d1ef42594db2))
* 添加 datatime格式支持，和required 区间校验 ([d3d4e3f](https://github.com/internet-com/vue-json-schema-form/commit/d3d4e3f68090ad9ea6c3900816568247e7d473a0))





# [1.14.0](https://github.com/lljj-x/vue-json-schema-form/compare/v1.13.1...v1.14.0) (2022-08-07)

**Note:** Version bump only for package docs





# [1.13.0](https://github.com/lljj-x/vue-json-schema-form/compare/v1.12.2...v1.13.0) (2022-05-22)


### Features

* **lib:** 添加 defaultSelectFirstOption 配置 ([bf17a61](https://github.com/lljj-x/vue-json-schema-form/commit/bf17a616fc000194ddda1259a708b9c52571d3fd)), closes [#171](https://github.com/lljj-x/vue-json-schema-form/issues/171)





## [1.12.2](https://github.com/lljj-x/vue-json-schema-form/compare/v1.12.1...v1.12.2) (2022-04-11)

**Note:** Version bump only for package docs





## [1.12.1](https://github.com/lljj-x/vue-json-schema-form/compare/v1.12.0...v1.12.1) (2022-04-05)

**Note:** Version bump only for package docs





# [1.12.0](https://github.com/lljj-x/vue-json-schema-form/compare/v1.11.0...v1.12.0) (2022-03-08)

**Note:** Version bump only for package docs





# [1.11.0](https://github.com/lljj-x/vue-json-schema-form/compare/v1.10.0...v1.11.0) (2022-02-19)


### Bug Fixes

* **lib:** 添加严格模式配置，更精准计算anyOf 默认值 ([2cd65bb](https://github.com/lljj-x/vue-json-schema-form/commit/2cd65bb5f275a021f1cc368e4c63387163c94d57)), closes [#157](https://github.com/lljj-x/vue-json-schema-form/issues/157)





# [1.10.0](https://github.com/lljj-x/vue-json-schema-form/compare/v1.9.5...v1.10.0) (2021-11-28)

**Note:** Version bump only for package docs





## [1.9.5](https://github.com/lljj-x/vue-json-schema-form/compare/v1.9.4...v1.9.5) (2021-11-21)

**Note:** Version bump only for package docs





## [1.9.4](https://github.com/lljj-x/vue-json-schema-form/compare/v1.9.3...v1.9.4) (2021-11-02)

**Note:** Version bump only for package docs





## [1.9.3](https://github.com/lljj-x/vue-json-schema-form/compare/v1.9.2...v1.9.3) (2021-10-10)

**Note:** Version bump only for package docs





## [1.9.2](https://github.com/lljj-x/vue-json-schema-form/compare/v1.9.1...v1.9.2) (2021-09-25)

**Note:** Version bump only for package docs





## [1.9.1](https://github.com/lljj-x/vue-json-schema-form/compare/v1.9.0...v1.9.1) (2021-09-22)

**Note:** Version bump only for package docs





# [1.9.0](https://github.com/lljj-x/vue-json-schema-form/compare/v1.7.0...v1.9.0) (2021-09-06)


### Features

* **vue2:** vue2 添加 widgetListeners 配置 ([50348c2](https://github.com/lljj-x/vue-json-schema-form/commit/50348c27e72813ea16fdcfcea46e6450ccf06018)), closes [#45](https://github.com/lljj-x/vue-json-schema-form/issues/45)
* **vue3-core:** 允许传递props至formFooter ([60ee613](https://github.com/lljj-x/vue-json-schema-form/commit/60ee613bda30b818adccd98ad73949ff111df74c))





# [1.8.0](https://github.com/lljj-x/vue-json-schema-form/compare/v1.7.0...v1.8.0) (2021-09-06)


### Features

* **vue2:** vue2 添加 widgetListeners 配置 ([50348c2](https://github.com/lljj-x/vue-json-schema-form/commit/50348c27e72813ea16fdcfcea46e6450ccf06018)), closes [#45](https://github.com/lljj-x/vue-json-schema-form/issues/45)
* **vue3-core:** 允许传递props至formFooter ([60ee613](https://github.com/lljj-x/vue-json-schema-form/commit/60ee613bda30b818adccd98ad73949ff111df74c))





# [1.7.0](https://github.com/lljj-x/vue-json-schema-form/compare/v1.6.4...v1.7.0) (2021-08-29)


### Features

* **lib:** 支持配置 slots ([27f1501](https://github.com/lljj-x/vue-json-schema-form/commit/27f1501eda01eabd4a723656be56904e9cb0f069)), closes [#45](https://github.com/lljj-x/vue-json-schema-form/issues/45)





## [1.6.3](https://github.com/lljj-x/vue-json-schema-form/compare/v1.6.2...v1.6.3) (2021-07-12)

**Note:** Version bump only for package docs





## [1.6.2](https://github.com/lljj-x/vue-json-schema-form/compare/v1.6.1...v1.6.2) (2021-05-31)

**Note:** Version bump only for package docs





## [1.6.1](https://github.com/lljj-x/vue-json-schema-form/compare/v1.6.0...v1.6.1) (2021-05-26)

**Note:** Version bump only for package docs





# [1.6.0](https://github.com/lljj-x/vue-json-schema-form/compare/v1.5.0...v1.6.0) (2021-05-22)


### Features

* **lib:** form-mounted event 添加formData 参数 ([c54202c](https://github.com/lljj-x/vue-json-schema-form/commit/c54202c27304add9636a7062c05c80c60fc200a6))





# [1.5.0](https://github.com/lljj-x/vue-json-schema-form/compare/v1.4.0...v1.5.0) (2021-05-09)

**Note:** Version bump only for package docs





# [1.4.0](https://github.com/lljj-x/vue-json-schema-form/compare/v1.3.0...v1.4.0) (2021-04-22)


### Features

* **lib:** 调整 widget onChange prop参数格式，添加 formData参数 ([4c441fc](https://github.com/lljj-x/vue-json-schema-form/commit/4c441fce239ade40b10a42bf361c3ee920a044ed)), closes [#45](https://github.com/lljj-x/vue-json-schema-form/issues/45)





# [1.3.0](https://github.com/lljj-x/vue-json-schema-form/compare/v1.2.1...v1.3.0) (2021-04-15)


### Features

* **core:** widget 节点直接配置onChange ([2d2264b](https://github.com/lljj-x/vue-json-schema-form/commit/2d2264b004c3b6586e225c563bf03ca52fc5e53a))





## [1.2.1](https://github.com/lljj-x/vue-json-schema-form/compare/v1.2.0...v1.2.1) (2021-04-11)

**Note:** Version bump only for package docs





# [1.2.0](https://github.com/lljj-x/vue-json-schema-form/compare/v1.1.3...v1.2.0) (2021-03-30)


### Features

* **lib:** 添加 fallback-label 参数 ([cd2d8c3](https://github.com/lljj-x/vue-json-schema-form/commit/cd2d8c3ed72b9bc03e44eb5b86eb1b18fe67c34c)), closes [#45](https://github.com/lljj-x/vue-json-schema-form/issues/45)





## [1.1.3](https://github.com/lljj-x/vue-json-schema-form/compare/v1.1.2...v1.1.3) (2021-03-18)

**Note:** Version bump only for package docs





## [1.1.2](https://github.com/lljj-x/vue-json-schema-form/compare/v1.1.1...v1.1.2) (2021-03-07)


### Bug Fixes

* **vue3-antd:** 修复form label 双冒号问题 ([5b4f16c](https://github.com/lljj-x/vue-json-schema-form/commit/5b4f16c3c1a4f4b784c2fd5c1fbe7eec40cf8d7b)), closes [#46](https://github.com/lljj-x/vue-json-schema-form/issues/46)





# [1.1.0](https://github.com/lljj-x/vue-json-schema-form/compare/v1.0.2...v1.1.0) (2021-03-06)


### Features

* **vue3-ant:** 更新初始化 ([71a2810](https://github.com/lljj-x/vue-json-schema-form/commit/71a281045af11f215333050396aa546dd5e78b88)), closes [#27](https://github.com/lljj-x/vue-json-schema-form/issues/27) [#27](https://github.com/lljj-x/vue-json-schema-form/issues/27) [#27](https://github.com/lljj-x/vue-json-schema-form/issues/27) [#40](https://github.com/lljj-x/vue-json-schema-form/issues/40)





## [1.0.2](https://github.com/lljj-x/vue-json-schema-form/compare/v1.0.1...v1.0.2) (2021-01-31)

**Note:** Version bump only for package docs





## [1.0.1](https://github.com/lljj-x/vue-json-schema-form/compare/v1.0.0...v1.0.1) (2021-01-31)

**Note:** Version bump only for package docs





## [0.6.1](https://github.com/lljj-x/vue-json-schema-form/compare/v0.6.0...v0.6.1) (2021-01-19)

**Note:** Version bump only for package docs





# [0.6.0](https://github.com/lljj-x/vue-json-schema-form/compare/v0.5.0...v0.6.0) (2021-01-19)


### Features

* **vue3:** init vue3 core ([df2c1fe](https://github.com/lljj-x/vue-json-schema-form/commit/df2c1fe9873a5e13eeafff924f7d9ab369824fbd))





# [0.5.0](https://github.com/lljj-x/vue-json-schema-form/compare/v0.4.1...v0.5.0) (2020-12-25)


### Features

* **lib:** uploadWidget 组件支持slots 配置function 接受createElement参数 ([2ceebcb](https://github.com/lljj-x/vue-json-schema-form/commit/2ceebcb6970bf0a46d0f8a80acb6dbe3ebcd7b80))





# [0.4.0](https://github.com/lljj-x/vue-json-schema-form/compare/v0.3.0...v0.4.0) (2020-12-05)

**Note:** Version bump only for package docs





# [0.3.0](https://github.com/lljj-x/vue-json-schema-form/compare/v0.2.2...v0.3.0) (2020-12-03)

**Note:** Version bump only for package docs





# [0.2.0](https://github.com/lljj-x/vue-json-schema-form/compare/v0.1.3...v0.2.0) (2020-11-24)

**Note:** Version bump only for package docs
