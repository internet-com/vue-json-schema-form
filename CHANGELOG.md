# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# 1.15.0 (2022-08-10)


### Bug Fixes

* **ant:** 修复vue3 ant popover 数据无法响应式 ([3e473ef](https://github.com/lljj-x/vue-json-schema-form/commit/3e473efe7ada39762d1bb79bb8896a590fdcdb89)), closes [#121](https://github.com/lljj-x/vue-json-schema-form/issues/121)
* **anyof:** 新值为object类型直接覆盖 ([d2f9791](https://github.com/lljj-x/vue-json-schema-form/commit/d2f9791ce7d35228edd07257049607177a95fc84)), closes [#77](https://github.com/lljj-x/vue-json-schema-form/issues/77)
* **arraymultiselect:** 修复type array 多选框不支持配置 uiwidget ([f9b577c](https://github.com/lljj-x/vue-json-schema-form/commit/f9b577c479a2c3dd0233952c50e74079c1e4a5ac))
* **core:** 修复 anyof 后代存在 $ref可能无法回填的问题 ([4dd046b](https://github.com/lljj-x/vue-json-schema-form/commit/4dd046bee0e5c3589f2bfa64ba0d90ed7869067a)), closes [#59](https://github.com/lljj-x/vue-json-schema-form/issues/59)
* **demo:** 修复element plus无法打开，锁定element plus cdn版本 ([a3c4312](https://github.com/lljj-x/vue-json-schema-form/commit/a3c43121cee3cdfc06844974028f8c78f5486e4f))
* **doc:** 修复docs:build 报错，修改demo默然 ClientOnly ([dde714c](https://github.com/lljj-x/vue-json-schema-form/commit/dde714cfa90ed2514dc2efc6f1f9121f53b2880a))
* **formfooter:** formFooter 按钮文案调整 ([e5fc714](https://github.com/lljj-x/vue-json-schema-form/commit/e5fc714002188ac057563f941c1651be69fa6ccb))
* **formfooter:** 修复 formFooter 配置确定按钮文案无效的问题 ([6606ca2](https://github.com/lljj-x/vue-json-schema-form/commit/6606ca2412cc830819067313aa82cf798b5a795c))
* **lib:** allOf merge 相同类型直接使用左边 ([c0bd0cd](https://github.com/lljj-x/vue-json-schema-form/commit/c0bd0cde9f15b4ca928fec84b4831a5cb459aa43)), closes [#116](https://github.com/lljj-x/vue-json-schema-form/issues/116)
* **lib:** anyOf onChange 参数 ([60cac99](https://github.com/lljj-x/vue-json-schema-form/commit/60cac995779c1eeb90b23f2cfeeb5deb8c350feb)), closes [#166](https://github.com/lljj-x/vue-json-schema-form/issues/166)
* **lib:** arrayFieldSpecialForamt 响应props变化 ([40536d5](https://github.com/lljj-x/vue-json-schema-form/commit/40536d5135227ebf3ab42fad23ccc4a927f5858e))
* **lib:** ui:hidden 透传到widget组件 ([f63094e](https://github.com/lljj-x/vue-json-schema-form/commit/f63094ee85659d1fea45bd789321817c08664ffa)), closes [#170](https://github.com/lljj-x/vue-json-schema-form/issues/170)
* **lib:** 修复 anyOf 切换时原item下错误不会清除问题 ([8d0b09a](https://github.com/lljj-x/vue-json-schema-form/commit/8d0b09a36a23626d34ffba46bad02d96e060b30e))
* **lib:** 修复 anyOf 类型，编辑时不能匹配正确选项 ([d747722](https://github.com/lljj-x/vue-json-schema-form/commit/d7477227d004e47c2b186c3eb956e4c83d7077ad)), closes [#31](https://github.com/lljj-x/vue-json-schema-form/issues/31)
* **lib:** 修复 d.ts 申明文件错误 ([860c3b4](https://github.com/lljj-x/vue-json-schema-form/commit/860c3b42a38ac3e76b2e16c3d74a45c7cd95dfa1))
* **lib:** 修复antd表单不实时校验 ([5452491](https://github.com/lljj-x/vue-json-schema-form/commit/5452491354acf9884cd37691e766c0007c82f88a))
* **lib:** 修复anyof 默认值计算可能丢失属性 ([44bcb44](https://github.com/lljj-x/vue-json-schema-form/commit/44bcb44af63a37847cd3df5614fad2f26bdf307d)), closes [#108](https://github.com/lljj-x/vue-json-schema-form/issues/108)
* **lib:** 修复anyOf下多级对象初始值计算错误问题 ([6dd9780](https://github.com/lljj-x/vue-json-schema-form/commit/6dd97804573aa55001c2715da4a6ffcc5ee897b9)), closes [#57](https://github.com/lljj-x/vue-json-schema-form/issues/57)
* **lib:** 修复anyOf嵌套object 可能丢失部分校验规则的问题 ([5c06294](https://github.com/lljj-x/vue-json-schema-form/commit/5c06294d9a9c978bda1c3724710cfd4ba478af5b))
* **lib:** 修复array widget 覆盖多选类型问题 ([d7453b3](https://github.com/lljj-x/vue-json-schema-form/commit/d7453b33abea5f903a3cbee073172a28c3cf02ac))
* **lib:** 修复array 多选类型不配置required ，导致array minItems 等后续不校验问题 ([683380e](https://github.com/lljj-x/vue-json-schema-form/commit/683380eb824a4e4dc281eda98f19deb64b0c3fa7))
* **lib:** 修复color 校验 ([2b49753](https://github.com/lljj-x/vue-json-schema-form/commit/2b4975375ba6f322d8dbdac08a1870bbd7335d22))
* **lib:** 修复inline 布局样式问题 ([65a7143](https://github.com/lljj-x/vue-json-schema-form/commit/65a7143fc19105f9096afc24a25107c0ef27ac5f)), closes [#122](https://github.com/lljj-x/vue-json-schema-form/issues/122)
* **lib:** 修复lib boolean 类型使用select渲染时，label=true 导致props类型校验错误 ([70ac8fc](https://github.com/lljj-x/vue-json-schema-form/commit/70ac8fc02b47e6e51e42be9d97daab998bfdadc9))
* **lib:** 修复代码错误导致表单初始化会更新一次form value的问题 ([b9e7ec1](https://github.com/lljj-x/vue-json-schema-form/commit/b9e7ec128ffe9ca508b3fc6ec5feaba7a6d38379))
* **lib:** 修复数组多选框默认值错误问题，修复anyOf选项数据可能合并错误 ([bf4a086](https://github.com/lljj-x/vue-json-schema-form/commit/bf4a086433b420ac0b9aa570bd13ff935c2ddd10))
* **lib:** 修复默认schema生成formData和默认值相等时导致可能不能及时更新的问题 ([590e37d](https://github.com/lljj-x/vue-json-schema-form/commit/590e37dd67d6863d3bb2867e978f83fa52a1fb9c))
* **lib:** 全局Vue下，默认注册 VueForm组件 ([0f81ac6](https://github.com/lljj-x/vue-json-schema-form/commit/0f81ac6a1ae957149c8f572b6bbb4cb17d329aff))
* **lib:** 宽松color format 校验 ([d32d079](https://github.com/lljj-x/vue-json-schema-form/commit/d32d079cd73fe16234ef30ae693f0bd3ab1b75fe))
* **lib:** 添加严格模式配置，更精准计算anyOf 默认值 ([10cdc08](https://github.com/lljj-x/vue-json-schema-form/commit/10cdc089087d83d8fe08e1fd379b7a1aaad0cd5d)), closes [#152](https://github.com/lljj-x/vue-json-schema-form/issues/152)
* **lib:** 添加严格模式配置，更精准计算anyOf 默认值 ([2cd65bb](https://github.com/lljj-x/vue-json-schema-form/commit/2cd65bb5f275a021f1cc368e4c63387163c94d57)), closes [#157](https://github.com/lljj-x/vue-json-schema-form/issues/157)
* **lib:** 解决打包后包含es6代码问题 ([f03352e](https://github.com/lljj-x/vue-json-schema-form/commit/f03352eb129c45963ad41e3e91eebe102c303913)), closes [#29](https://github.com/lljj-x/vue-json-schema-form/issues/29)
* **object vaidate:** 对象类型校验修复 additionalProperties false 不生效问题 ([b8772e8](https://github.com/lljj-x/vue-json-schema-form/commit/b8772e80d0375588d5a689e67ab9ebbba0ed8711))
* **objectfield:** 修复调用isValid 校验schema 返回结果可能不正确的问题 ([1f34d32](https://github.com/lljj-x/vue-json-schema-form/commit/1f34d322ad38696d77454087e5c8be3b6f4b183f))
* **schema generator:** 修复generator schema相同组件，多次使用导致相同引用串数据问题 ([04538b1](https://github.com/lljj-x/vue-json-schema-form/commit/04538b1230f095abd3ef750cd2ed4d3a93bf9bea))
* **schema generator:** 修复schema生成器预览不支持% ([ff0d2da](https://github.com/lljj-x/vue-json-schema-form/commit/ff0d2da9b1944056185803898d3a2c66194cc508))
* **schema generator:** 多选类型强制 uniqueItems ([cd3349e](https://github.com/lljj-x/vue-json-schema-form/commit/cd3349ed960bdf2908ffd76ffce86cf99914b222))
* **schema-generator:** 修复array 下object排序问题 ([55dc50e](https://github.com/lljj-x/vue-json-schema-form/commit/55dc50e128417a67e9d186d3fcd6e2340d713144))
* **style:** 修复p标签等自带边距导致的样式问题  ([7b7e43e](https://github.com/lljj-x/vue-json-schema-form/commit/7b7e43eaa06c14a436b34c38d6d69aad27d67512))
* **style:** 更新表单数组操作样式 ([ca0652f](https://github.com/lljj-x/vue-json-schema-form/commit/ca0652f3c96682e29619894a11bc7d9dd69799f5))
* **ts:** 修复类型定义文件 ([18a7058](https://github.com/lljj-x/vue-json-schema-form/commit/18a70581d4471055a9d1c78eef6e012f37ddd8cb))
* **vue2-lib:** 修复 provide 响应式 ([d4ca316](https://github.com/lljj-x/vue-json-schema-form/commit/d4ca316c693733886626c6f9d6d7248bfa86aaa1))
* 修复select组件无法实时校验 ([85d9545](https://github.com/lljj-x/vue-json-schema-form/commit/85d95451b56b9d985ca7094118fbfaca87342322)), closes [#105](https://github.com/lljj-x/vue-json-schema-form/issues/105)
* **uploadwidget:** 修复上传图片 picture 模式文件获取错误问题 ([e672d74](https://github.com/lljj-x/vue-json-schema-form/commit/e672d7425521b9b3fc51e0bea1f5d101a669a7f8))
* **vjsf:** 移除package中的vue依赖 ([1d42d82](https://github.com/lljj-x/vue-json-schema-form/commit/1d42d82eec563c90db1698c6dd72eb50df8367a6))
* **vue editor:** 修复el-image lazy 判断是否为滚动容器可能错误的问题 ([422f705](https://github.com/lljj-x/vue-json-schema-form/commit/422f705f77d87e9d65ace80f766897f6253ae624))
* **vue2-element:** 修复 vue2-elementUi package 配置问题 ([fcc30d6](https://github.com/lljj-x/vue-json-schema-form/commit/fcc30d6c1b1214b71784d50b14385a4444d4ff43))
* **vue2-iview3:** 修复iveiws组件透透传slot失效 ([f86ec5f](https://github.com/lljj-x/vue-json-schema-form/commit/f86ec5f77f98a40ee31989cf6e554504059b910d))
* **vue3 antd:** 修复color format选择颜色 ([378c2e1](https://github.com/lljj-x/vue-json-schema-form/commit/378c2e1aa6767553998cacf52321a6d5b5bee84e))
* **vue3-antd:** 修复form label 双冒号问题 ([5b4f16c](https://github.com/lljj-x/vue-json-schema-form/commit/5b4f16c3c1a4f4b784c2fd5c1fbe7eec40cf8d7b)), closes [#46](https://github.com/lljj-x/vue-json-schema-form/issues/46)
* 修复选择框需要uiSchema参数问题 ([66be8df](https://github.com/lljj-x/vue-json-schema-form/commit/66be8df61f0b724fdcccf4b387341a948cf6dd05))


### Features

* build vue3-form-element ([4747bf9](https://github.com/lljj-x/vue-json-schema-form/commit/4747bf985397b8c06ee5b7e13dc11cceb9c7b69a))
* 修复fallbackLabel的错误判断 && 优化代码 ([d23da39](https://github.com/lljj-x/vue-json-schema-form/commit/d23da39dbf51a017e0a439512164f3977b520ff6))
* **anyof:** anyOf 下拉切换组件，默认使用 当前schema的 title，description ([edd86ab](https://github.com/lljj-x/vue-json-schema-form/commit/edd86ab561b3aca15dd46f6a9a251fcd50e0f083))
* **array:** 优化数组类型渲染，不可添加的空组不做渲染 ([fadd295](https://github.com/lljj-x/vue-json-schema-form/commit/fadd29541ba6082b1635ca306fc8b31df6eca48b))
* **cdn:** 替换cdn链接 ([245fd2c](https://github.com/lljj-x/vue-json-schema-form/commit/245fd2c0e92d5bb4de1218a9438e64aff37551c3))
* **core:** widget 节点直接配置onChange ([2d2264b](https://github.com/lljj-x/vue-json-schema-form/commit/2d2264b004c3b6586e225c563bf03ca52fc5e53a))
* **customformats:** 支持customFormats配置，添加自定义 formats ([f84c7e1](https://github.com/lljj-x/vue-json-schema-form/commit/f84c7e136153be9682574aad1e02c169dfb5d2b3))
* **customrule:** 添加自定义校验方法 ([017272d](https://github.com/lljj-x/vue-json-schema-form/commit/017272dd60c9da3117262749180fbe624d14979b))
* **datatime:** 时间日期选择支持区间选择，清空时保存数据类型 ([71343e4](https://github.com/lljj-x/vue-json-schema-form/commit/71343e4076abf3afd9a57de68f8381e09ccb0552))
* **daterange:** 支持时间区间选择 ([2de8f14](https://github.com/lljj-x/vue-json-schema-form/commit/2de8f14f8401eb58904187cced3b08556d937521))
* **datetime:** 新增支持 date、time、datetime 三种类型 ([897dedc](https://github.com/lljj-x/vue-json-schema-form/commit/897dedc3f1479c4a150dec7fd744fb1d14d6f453))
* **demo:** demo页面添加ui 框架切换 ([c3f76f7](https://github.com/lljj-x/vue-json-schema-form/commit/c3f76f7272be6f8132e467b130d6f230a048fb9b))
* **demo:** 更新demo页ui样式 ([89b93b2](https://github.com/lljj-x/vue-json-schema-form/commit/89b93b26d0a57e623e6e2784e4636a7aefb32738))
* **enum uischema:** enumNames 和anyOf const 形式，支持通过uiSchema配置枚举项标题 ([62698e4](https://github.com/lljj-x/vue-json-schema-form/commit/62698e4e1f778f5c90d626513421c07918064cbc))
* **errorschema:** errorSchema 支持直接配置在 uiSchema中 ([5996acc](https://github.com/lljj-x/vue-json-schema-form/commit/5996acc04788d3dcad2176cf76e10b96e57c715d)), closes [#7](https://github.com/lljj-x/vue-json-schema-form/issues/7)
* **field:** filed组件 支持通过uiSchema配置 className、attrs、style ([b85b69f](https://github.com/lljj-x/vue-json-schema-form/commit/b85b69f116dbdb985f983d0a6472cc3a08bb356a)), closes [#8](https://github.com/lljj-x/vue-json-schema-form/issues/8)
* **field:** 自定义 field 支持 ui:fieldProps 配置传入附加props ([7bea3a6](https://github.com/lljj-x/vue-json-schema-form/commit/7bea3a6b2ecb4f78dde5d0abd721108d8bfe6ec0))
* **form editor:** 更新form editor 体现ui，error 可以配置在schema中 ([67dffba](https://github.com/lljj-x/vue-json-schema-form/commit/67dffba0fdffccf3c7ef418065d77a105a51273c))
* **form event:** 更新form emit事件名非为驼峰 ([db8bcb7](https://github.com/lljj-x/vue-json-schema-form/commit/db8bcb77ae6021e7e0002ee4c3b159ee3b503725))
* **git:** 添加git hook ([a1e48c4](https://github.com/lljj-x/vue-json-schema-form/commit/a1e48c44436fd2d6625ef3e855d314eef550c934))
* **integerfield:** 添加单独 integerfield 区分 NumberField ([830ab48](https://github.com/lljj-x/vue-json-schema-form/commit/830ab48f514cf1ad53d4a9d04dbacee978360122))
* **iview:** 添加iview i-switch 组件转换 ([8fae70c](https://github.com/lljj-x/vue-json-schema-form/commit/8fae70cb28f7fd02073d6d4318861b7f08f6199b))
* **iview3:** 适配 iview ([c969d97](https://github.com/lljj-x/vue-json-schema-form/commit/c969d97b6d908eabe8c1f60b8c3625b41fbb661a))
* **iview3:** 适配iview3 footer btn ([b734ae0](https://github.com/lljj-x/vue-json-schema-form/commit/b734ae062bb21e82cfec59739de6de843d752b4c))
* **lib:** array 类型 item title description 支持 $index 特殊字符 ([8922650](https://github.com/lljj-x/vue-json-schema-form/commit/89226508fa8dcdb55fe930a014e6ec7d1cc6a9bd)), closes [#19](https://github.com/lljj-x/vue-json-schema-form/issues/19)
* **lib:** form-mounted event 添加formData 参数 ([c54202c](https://github.com/lljj-x/vue-json-schema-form/commit/c54202c27304add9636a7062c05c80c60fc200a6))
* **lib:** uiSchema 支持配置在schema中 ([0732d7f](https://github.com/lljj-x/vue-json-schema-form/commit/0732d7f8e65f806d04112bd93a1ecd623d3a5d8d))
* **lib:** ui配置支持 ui:xxx 配置表达式 ([570dd57](https://github.com/lljj-x/vue-json-schema-form/commit/570dd577fe88b779d37afb8fba8199b97edb2f73)), closes [#19](https://github.com/lljj-x/vue-json-schema-form/issues/19)
* **lib:** uploadWidget 组件支持slots 配置function 接受createElement参数 ([2ceebcb](https://github.com/lljj-x/vue-json-schema-form/commit/2ceebcb6970bf0a46d0f8a80acb6dbe3ebcd7b80))
* **lib:** 优化anyOf切换选项值的复用，修复vue3 anyOf无法切换选项 ([6159160](https://github.com/lljj-x/vue-json-schema-form/commit/6159160d1727165e706343187aca129360dc011f))
* **lib:** 优化样式 ([e53291b](https://github.com/lljj-x/vue-json-schema-form/commit/e53291b8395fdceb971f15f72c9e809cdee8ec7e))
* **lib:** 对ui:xxx 配置支持表达式，options 内不支持表达式以便区分 ([7c20bb8](https://github.com/lljj-x/vue-json-schema-form/commit/7c20bb8c11d5038eca37d5fdb151ae250f7dc074))
* **lib:** 支持 column 布局，1 2 3 列 ，同时支持单个 widget 配置ui:width 指定宽度 ([a088a6f](https://github.com/lljj-x/vue-json-schema-form/commit/a088a6f21448e77f371e8391d93c03aa2e99a3e9))
* **lib:** 支持errorSchema 配置在schema中 ([9e96560](https://github.com/lljj-x/vue-json-schema-form/commit/9e965604559b2931d33a222f5f71b463e9ce75a4))
* **lib:** 支持配置 getWidget function回调接收 widget组件实例 ([01b9915](https://github.com/lljj-x/vue-json-schema-form/commit/01b9915334b053a940440fff3546e263ba10894c)), closes [#25](https://github.com/lljj-x/vue-json-schema-form/issues/25)
* **lib:** 支持配置 slots ([27f1501](https://github.com/lljj-x/vue-json-schema-form/commit/27f1501eda01eabd4a723656be56904e9cb0f069)), closes [#45](https://github.com/lljj-x/vue-json-schema-form/issues/45)
* **lib:** 更新eslint配置 ([6c8d9d5](https://github.com/lljj-x/vue-json-schema-form/commit/6c8d9d5ab355c895e6983ee01cfad0f610781eeb))
* **lib:** 添加 $$uiFormRef 属性，可在mounted 之直接访问子组件实例 ([08c6c4f](https://github.com/lljj-x/vue-json-schema-form/commit/08c6c4f2d247b4881e88fa380de8980c31cc5cd7)), closes [#127](https://github.com/lljj-x/vue-json-schema-form/issues/127)
* **lib:** 添加 defaultSelectFirstOption 配置 ([bf17a61](https://github.com/lljj-x/vue-json-schema-form/commit/bf17a616fc000194ddda1259a708b9c52571d3fd)), closes [#171](https://github.com/lljj-x/vue-json-schema-form/issues/171)
* **lib:** 添加 fallback-label 参数 ([cd2d8c3](https://github.com/lljj-x/vue-json-schema-form/commit/cd2d8c3ed72b9bc03e44eb5b86eb1b18fe67c34c)), closes [#45](https://github.com/lljj-x/vue-json-schema-form/issues/45)
* **lib:** 添加on-validation-failed event，表单校验失败触发 ([388454e](https://github.com/lljj-x/vue-json-schema-form/commit/388454eac1fd1c1d5aa205e965c477604176df09))
* **lib:** 添加vue3 naiveui支持 ([a159c78](https://github.com/lljj-x/vue-json-schema-form/commit/a159c78eb1a9156aa042a0cf82a350c46e035dcc)), closes [#152](https://github.com/lljj-x/vue-json-schema-form/issues/152)
* **lib:** 调整 widget onChange prop参数格式，添加 formData参数 ([4c441fc](https://github.com/lljj-x/vue-json-schema-form/commit/4c441fce239ade40b10a42bf361c3ee920a044ed)), closes [#45](https://github.com/lljj-x/vue-json-schema-form/issues/45)
* **lib:** 配置 format color，默认使用 el-color-picker 组件 ([be915ad](https://github.com/lljj-x/vue-json-schema-form/commit/be915ad8eace3b33bbb70180788c251dafbac50e))
* **lib:** 阻止表单默认submit事件 ([a882181](https://github.com/lljj-x/vue-json-schema-form/commit/a882181d65a9a152f8017e55367100658464aeba)), closes [#150](https://github.com/lljj-x/vue-json-schema-form/issues/150)
* **lib ui-schema:** ui-schema 支持配置 ui:hidden 表达式实现数据联动 ([13737fe](https://github.com/lljj-x/vue-json-schema-form/commit/13737fea1db56763239be5027a2f375447ca8f70))
* **null:** 添加type null 支持 ([5c437ad](https://github.com/lljj-x/vue-json-schema-form/commit/5c437ad2356a1b046b54ea6726f298aa0c7d8e5c))
* **schema generator:** 完成schema生成器 input 组件配置化 ([9d7cc67](https://github.com/lljj-x/vue-json-schema-form/commit/9d7cc67802353b3772e5937aeac9345ec0b46570))
* **schema generator:** 支持基础组件拖入生成 ([93e344e](https://github.com/lljj-x/vue-json-schema-form/commit/93e344e48ce50d3933830c90113dd5d789a0a371))
* **schema generator:** 添加schema generator 参数formLabel左右布局时隐藏description ([f13a159](https://github.com/lljj-x/vue-json-schema-form/commit/f13a159977d8f1677e8942dce2b1e53283943b82))
* **schema-generator:** 优化schema-generator参数配置 ([82d0b7d](https://github.com/lljj-x/vue-json-schema-form/commit/82d0b7d4430d92ae8094044dec3dfa521ed5c410))
* **schema-generator:** 优化导出代码 ([20d429c](https://github.com/lljj-x/vue-json-schema-form/commit/20d429c60f49f7e8181ece0b53974f303fec0c5f))
* **schema-generator:** 修复 schema-generator 导出schema参数丢失问题 ([23f9615](https://github.com/lljj-x/vue-json-schema-form/commit/23f961579dc11fe8a7626186b4f9736c4e1203c6))
* **schema-generator:** 初始化 schema-generator ([3a743ee](https://github.com/lljj-x/vue-json-schema-form/commit/3a743ee48c50493fb17a19cc0657cb351ef5a111))
* **schema-generator:** 完善表单设计器组件库 ([26afd79](https://github.com/lljj-x/vue-json-schema-form/commit/26afd79687263149a1e29c0adf03de3b7bd7f6db))
* **schema-generator:** 添加日期相关组件 ([bcb2836](https://github.com/lljj-x/vue-json-schema-form/commit/bcb283665eab561608062255c5f197f5a1e1a5aa))
* **schema-generator:** 生成表单编辑器 ([dd5eecb](https://github.com/lljj-x/vue-json-schema-form/commit/dd5eecb607e2be8e000a56dd5202d3a9c02d38a0))
* **vjsf:** 更新渲染表单 inline样式 ([30888ca](https://github.com/lljj-x/vue-json-schema-form/commit/30888ca38dd42b0d4ed11e185d63cf1ec0bcc2cb))
* **vjsf:** 表单配置inline时 调整整体样式 ([0ba7ff3](https://github.com/lljj-x/vue-json-schema-form/commit/0ba7ff3b787f0c54ebb9377ac585753e1bf0ed16)), closes [#14](https://github.com/lljj-x/vue-json-schema-form/issues/14)
* **vjsf dependencies:** 支持 object dependencies property ,scheam 依赖不支持 ([1cda05d](https://github.com/lljj-x/vue-json-schema-form/commit/1cda05d78bc312ee1a631f480f2fec3a15f4c5b3))
* **vjsf ui:** 添加ui:showIndexNumber，支持配置 array item 显示序号 ([b8e8389](https://github.com/lljj-x/vue-json-schema-form/commit/b8e8389ba0bbc41ec24a88af5da0cfc3dffd6bcd))
* **vue editor:** 初始化时计算滚动条默认居中 ([0eb5b31](https://github.com/lljj-x/vue-json-schema-form/commit/0eb5b3129c26f321f3f5cc98a6b30b13a43ce628))
* **vue editor:** 更新vue editor ([0106776](https://github.com/lljj-x/vue-json-schema-form/commit/0106776c440f0da72a8701a3882d1b2cf71bb779))
* **vue2:** vue2 添加 widgetListeners 配置 ([50348c2](https://github.com/lljj-x/vue-json-schema-form/commit/50348c27e72813ea16fdcfcea46e6450ccf06018)), closes [#45](https://github.com/lljj-x/vue-json-schema-form/issues/45)
* **vue2-core:** 暴露 okBtnProps ([c832a07](https://github.com/lljj-x/vue-json-schema-form/commit/c832a07eab0d4174d62da42a739bfa7e1f69fa44))
* **vue2-iview3:** 完成iview3时间选择和样式优化 ([27e310e](https://github.com/lljj-x/vue-json-schema-form/commit/27e310e298498ee5a2466f4d6c7d4153ad8b9777))
* **vue2-iview3:** 适配 iview3 ([0120d2b](https://github.com/lljj-x/vue-json-schema-form/commit/0120d2b9a265cf0bffee099c2d4974c883c08a25)), closes [#27](https://github.com/lljj-x/vue-json-schema-form/issues/27)
* **vue3:** init vue3 core ([df2c1fe](https://github.com/lljj-x/vue-json-schema-form/commit/df2c1fe9873a5e13eeafff924f7d9ab369824fbd))
* **vue3:** 完成 vue3 form组件 ([1c5deba](https://github.com/lljj-x/vue-json-schema-form/commit/1c5debae4cb92f3f54de64d8f38c98396022a344))
* **vue3:** 更新vue3 form 组件 ([ab481d6](https://github.com/lljj-x/vue-json-schema-form/commit/ab481d675c4b84a29aa689b99d9d2f8f17fae86d))
* **vue3 core:** 修复provide警告 ([711c932](https://github.com/lljj-x/vue-json-schema-form/commit/711c932e71ead9667f65777e6b65578c76087ce1))
* **vue3core:** 整理代码 ([54e9db4](https://github.com/lljj-x/vue-json-schema-form/commit/54e9db4090155e0e6a78788dccb5c6208f9cb812))
* 下拉选项组件支持直接配置ui:enumOptions，优先级高于schema默计算出的下拉选项 ([af8bee4](https://github.com/lljj-x/vue-json-schema-form/commit/af8bee437cae86deae38480cce6607e7dd42b867))
* 优化 anyOf 切换 ([2c2388d](https://github.com/lljj-x/vue-json-schema-form/commit/2c2388d0b46e068ec24c9e64e7ec2154e3237a59))
* 回退 ([e00a39c](https://github.com/lljj-x/vue-json-schema-form/commit/e00a39c5520c54c8c927447dbaaedbc8b77a2aa9))
* **schema-generator:** 更新schema生成器 支持配置数组 ([0f4d3b4](https://github.com/lljj-x/vue-json-schema-form/commit/0f4d3b4be1b47fb89571500cd8749fed6a412a38))
* **schema-generator:** 添加导入功能 ([93ea158](https://github.com/lljj-x/vue-json-schema-form/commit/93ea158a66dab8f845e8ac0e1fa76c041f0d8abb))
* **vue3-ant:** 更新初始化 ([71a2810](https://github.com/lljj-x/vue-json-schema-form/commit/71a281045af11f215333050396aa546dd5e78b88)), closes [#27](https://github.com/lljj-x/vue-json-schema-form/issues/27) [#27](https://github.com/lljj-x/vue-json-schema-form/issues/27) [#27](https://github.com/lljj-x/vue-json-schema-form/issues/27) [#40](https://github.com/lljj-x/vue-json-schema-form/issues/40)
* **vue3-core:** 允许传递props至formFooter ([60ee613](https://github.com/lljj-x/vue-json-schema-form/commit/60ee613bda30b818adccd98ad73949ff111df74c))
* **vue3-core:** 完成 @lljj/vue3-form-element package，更新文档 ([a4d65db](https://github.com/lljj-x/vue-json-schema-form/commit/a4d65db6c58f96e6afe6e31068c09e914e6b6579)), closes [#27](https://github.com/lljj-x/vue-json-schema-form/issues/27)
* 适配 iview3 ([d4ee166](https://github.com/lljj-x/vue-json-schema-form/commit/d4ee166a7dd71bb9a840525f4eb15c4fdc97f11d))
* **vue3-core:** 初始化vue3-core ([f22a51c](https://github.com/lljj-x/vue-json-schema-form/commit/f22a51cd732c21a244b770cbcae0f9ceb0156c57))
* 添加初始化 iview ([f8b59ce](https://github.com/lljj-x/vue-json-schema-form/commit/f8b59ce6bcc3830c051f1aa823ad9c5d06cae61d))
* 适配 iview3 ([2df6957](https://github.com/lljj-x/vue-json-schema-form/commit/2df69575b4ad2650c2e75863ffcf0c306e42f21e))
* 适配iview 时间日期 ([0baa3cd](https://github.com/lljj-x/vue-json-schema-form/commit/0baa3cdfd22ac19191dfc8adddd7f0bdc3520bf0))
* 适配iview3 upload 组件 ([16060af](https://github.com/lljj-x/vue-json-schema-form/commit/16060af6743c678b4c64e98d58f9503b817d3921))
* **widget:** widget 组件支持透传 $attrs ([1a86316](https://github.com/lljj-x/vue-json-schema-form/commit/1a86316500968574f30fe2c2e676c6211930ec2e)), closes [#16](https://github.com/lljj-x/vue-json-schema-form/issues/16)
* array 类型支持 showTitle showDescription 配置是否显示标题或描述 ([d9e3618](https://github.com/lljj-x/vue-json-schema-form/commit/d9e361837e2c8dcbb180ab5a0be167155bac58b2))
* 对渲染节点添加class， 标识当前渲染节点path ([100d8ec](https://github.com/lljj-x/vue-json-schema-form/commit/100d8ecdc5ba95176050d9e8663e61d2afc2fbd0))
* 更新文档 ([df34da2](https://github.com/lljj-x/vue-json-schema-form/commit/df34da2a47a07d06c42a0cbc6a90d1ef42594db2))
* 添加 datatime格式支持，和required 区间校验 ([d3d4e3f](https://github.com/lljj-x/vue-json-schema-form/commit/d3d4e3f68090ad9ea6c3900816568247e7d473a0))
* 调整lib 导出模块，添加 getDefaultFormState ([5a3c318](https://github.com/lljj-x/vue-json-schema-form/commit/5a3c3180a8428c78c681ab6b68dd3d20c8be0963))
* 调整表单渲染class类都为 首字母小写 ([fc97966](https://github.com/lljj-x/vue-json-schema-form/commit/fc9796607f99830965e6e3b1f8f13ab73e6bd160))


### Performance Improvements

* **vue3-core:** 优化 okBtnProps 的实现方式 ([adfe93e](https://github.com/lljj-x/vue-json-schema-form/commit/adfe93e58a9e8fedc2b0c26484be5691ccc3f65a))





# [1.14.0](https://github.com/lljj-x/vue-json-schema-form/compare/v1.13.1...v1.14.0) (2022-08-07)


### Bug Fixes

* **lib:** 修复color 校验 ([2b49753](https://github.com/lljj-x/vue-json-schema-form/commit/2b4975375ba6f322d8dbdac08a1870bbd7335d22))
* **lib:** 宽松color format 校验 ([d32d079](https://github.com/lljj-x/vue-json-schema-form/commit/d32d079cd73fe16234ef30ae693f0bd3ab1b75fe))
* **vue2-lib:** 修复 provide 响应式 ([d4ca316](https://github.com/lljj-x/vue-json-schema-form/commit/d4ca316c693733886626c6f9d6d7248bfa86aaa1))


### Features

* build vue3-form-element ([4747bf9](https://github.com/lljj-x/vue-json-schema-form/commit/4747bf985397b8c06ee5b7e13dc11cceb9c7b69a))
* 修复fallbackLabel的错误判断 && 优化代码 ([d23da39](https://github.com/lljj-x/vue-json-schema-form/commit/d23da39dbf51a017e0a439512164f3977b520ff6))
* **vue3 core:** 修复provide警告 ([711c932](https://github.com/lljj-x/vue-json-schema-form/commit/711c932e71ead9667f65777e6b65578c76087ce1))
* **vue3core:** 整理代码 ([54e9db4](https://github.com/lljj-x/vue-json-schema-form/commit/54e9db4090155e0e6a78788dccb5c6208f9cb812))





## [1.13.1](https://github.com/lljj-x/vue-json-schema-form/compare/v1.13.0...v1.13.1) (2022-06-12)


### Bug Fixes

* **lib:** arrayFieldSpecialForamt 响应props变化 ([40536d5](https://github.com/lljj-x/vue-json-schema-form/commit/40536d5135227ebf3ab42fad23ccc4a927f5858e))





# [1.13.0](https://github.com/lljj-x/vue-json-schema-form/compare/v1.12.2...v1.13.0) (2022-05-22)


### Features

* **lib:** 添加 defaultSelectFirstOption 配置 ([bf17a61](https://github.com/lljj-x/vue-json-schema-form/commit/bf17a616fc000194ddda1259a708b9c52571d3fd)), closes [#171](https://github.com/lljj-x/vue-json-schema-form/issues/171)





## [1.12.2](https://github.com/lljj-x/vue-json-schema-form/compare/v1.12.1...v1.12.2) (2022-04-11)


### Bug Fixes

* **lib:** ui:hidden 透传到widget组件 ([f63094e](https://github.com/lljj-x/vue-json-schema-form/commit/f63094ee85659d1fea45bd789321817c08664ffa)), closes [#170](https://github.com/lljj-x/vue-json-schema-form/issues/170)





## [1.12.1](https://github.com/lljj-x/vue-json-schema-form/compare/v1.12.0...v1.12.1) (2022-04-05)


### Bug Fixes

* **lib:** anyOf onChange 参数 ([60cac99](https://github.com/lljj-x/vue-json-schema-form/commit/60cac995779c1eeb90b23f2cfeeb5deb8c350feb)), closes [#166](https://github.com/lljj-x/vue-json-schema-form/issues/166)





# [1.12.0](https://github.com/lljj-x/vue-json-schema-form/compare/v1.11.0...v1.12.0) (2022-03-08)


### Bug Fixes

* **lib:** 添加严格模式配置，更精准计算anyOf 默认值 ([10cdc08](https://github.com/lljj-x/vue-json-schema-form/commit/10cdc089087d83d8fe08e1fd379b7a1aaad0cd5d)), closes [#152](https://github.com/lljj-x/vue-json-schema-form/issues/152)
* **ts:** 修复类型定义文件 ([18a7058](https://github.com/lljj-x/vue-json-schema-form/commit/18a70581d4471055a9d1c78eef6e012f37ddd8cb))


### Features

* **lib:** 优化样式 ([e53291b](https://github.com/lljj-x/vue-json-schema-form/commit/e53291b8395fdceb971f15f72c9e809cdee8ec7e))
* **lib:** 添加vue3 naiveui支持 ([a159c78](https://github.com/lljj-x/vue-json-schema-form/commit/a159c78eb1a9156aa042a0cf82a350c46e035dcc)), closes [#152](https://github.com/lljj-x/vue-json-schema-form/issues/152)





# [1.11.0](https://github.com/lljj-x/vue-json-schema-form/compare/v1.10.0...v1.11.0) (2022-02-19)


### Bug Fixes

* **lib:** 添加严格模式配置，更精准计算anyOf 默认值 ([2cd65bb](https://github.com/lljj-x/vue-json-schema-form/commit/2cd65bb5f275a021f1cc368e4c63387163c94d57)), closes [#157](https://github.com/lljj-x/vue-json-schema-form/issues/157)


### Features

* **cdn:** 替换cdn链接 ([245fd2c](https://github.com/lljj-x/vue-json-schema-form/commit/245fd2c0e92d5bb4de1218a9438e64aff37551c3))
* **lib:** 阻止表单默认submit事件 ([a882181](https://github.com/lljj-x/vue-json-schema-form/commit/a882181d65a9a152f8017e55367100658464aeba)), closes [#150](https://github.com/lljj-x/vue-json-schema-form/issues/150)





# [1.10.0](https://github.com/lljj-x/vue-json-schema-form/compare/v1.9.5...v1.10.0) (2021-11-28)


### Features

* **lib:** 添加 $$uiFormRef 属性，可在mounted 之直接访问子组件实例 ([08c6c4f](https://github.com/lljj-x/vue-json-schema-form/commit/08c6c4f2d247b4881e88fa380de8980c31cc5cd7)), closes [#127](https://github.com/lljj-x/vue-json-schema-form/issues/127)
* 回退 ([e00a39c](https://github.com/lljj-x/vue-json-schema-form/commit/e00a39c5520c54c8c927447dbaaedbc8b77a2aa9))





## [1.9.5](https://github.com/lljj-x/vue-json-schema-form/compare/v1.9.4...v1.9.5) (2021-11-21)


### Bug Fixes

* **ant:** 修复vue3 ant popover 数据无法响应式 ([3e473ef](https://github.com/lljj-x/vue-json-schema-form/commit/3e473efe7ada39762d1bb79bb8896a590fdcdb89)), closes [#121](https://github.com/lljj-x/vue-json-schema-form/issues/121)
* **lib:** 修复inline 布局样式问题 ([65a7143](https://github.com/lljj-x/vue-json-schema-form/commit/65a7143fc19105f9096afc24a25107c0ef27ac5f)), closes [#122](https://github.com/lljj-x/vue-json-schema-form/issues/122)





## [1.9.4](https://github.com/lljj-x/vue-json-schema-form/compare/v1.9.3...v1.9.4) (2021-11-02)

**Note:** Version bump only for package vue-json-schema-form





## [1.9.3](https://github.com/lljj-x/vue-json-schema-form/compare/v1.9.2...v1.9.3) (2021-10-10)


### Bug Fixes

* **lib:** allOf merge 相同类型直接使用左边 ([c0bd0cd](https://github.com/lljj-x/vue-json-schema-form/commit/c0bd0cde9f15b4ca928fec84b4831a5cb459aa43)), closes [#116](https://github.com/lljj-x/vue-json-schema-form/issues/116)





## [1.9.2](https://github.com/lljj-x/vue-json-schema-form/compare/v1.9.1...v1.9.2) (2021-09-25)


### Bug Fixes

* **lib:** 修复antd表单不实时校验 ([5452491](https://github.com/lljj-x/vue-json-schema-form/commit/5452491354acf9884cd37691e766c0007c82f88a))
* **lib:** 修复anyof 默认值计算可能丢失属性 ([44bcb44](https://github.com/lljj-x/vue-json-schema-form/commit/44bcb44af63a37847cd3df5614fad2f26bdf307d)), closes [#108](https://github.com/lljj-x/vue-json-schema-form/issues/108)
* **lib:** 修复anyOf嵌套object 可能丢失部分校验规则的问题 ([5c06294](https://github.com/lljj-x/vue-json-schema-form/commit/5c06294d9a9c978bda1c3724710cfd4ba478af5b))





## [1.9.1](https://github.com/lljj-x/vue-json-schema-form/compare/v1.9.0...v1.9.1) (2021-09-22)


### Bug Fixes

* **anyof:** 新值为object类型直接覆盖 ([d2f9791](https://github.com/lljj-x/vue-json-schema-form/commit/d2f9791ce7d35228edd07257049607177a95fc84)), closes [#77](https://github.com/lljj-x/vue-json-schema-form/issues/77)
* 修复select组件无法实时校验 ([85d9545](https://github.com/lljj-x/vue-json-schema-form/commit/85d95451b56b9d985ca7094118fbfaca87342322)), closes [#105](https://github.com/lljj-x/vue-json-schema-form/issues/105)





# [1.9.0](https://github.com/lljj-x/vue-json-schema-form/compare/v1.7.0...v1.9.0) (2021-09-06)


### Features

* **vue2:** vue2 添加 widgetListeners 配置 ([50348c2](https://github.com/lljj-x/vue-json-schema-form/commit/50348c27e72813ea16fdcfcea46e6450ccf06018)), closes [#45](https://github.com/lljj-x/vue-json-schema-form/issues/45)
* **vue2-core:** 暴露 okBtnProps ([c832a07](https://github.com/lljj-x/vue-json-schema-form/commit/c832a07eab0d4174d62da42a739bfa7e1f69fa44))
* **vue3-core:** 允许传递props至formFooter ([60ee613](https://github.com/lljj-x/vue-json-schema-form/commit/60ee613bda30b818adccd98ad73949ff111df74c))


### Performance Improvements

* **vue3-core:** 优化 okBtnProps 的实现方式 ([adfe93e](https://github.com/lljj-x/vue-json-schema-form/commit/adfe93e58a9e8fedc2b0c26484be5691ccc3f65a))





# [1.8.0](https://github.com/lljj-x/vue-json-schema-form/compare/v1.7.0...v1.8.0) (2021-09-06)


### Features

* **vue2:** vue2 添加 widgetListeners 配置 ([50348c2](https://github.com/lljj-x/vue-json-schema-form/commit/50348c27e72813ea16fdcfcea46e6450ccf06018)), closes [#45](https://github.com/lljj-x/vue-json-schema-form/issues/45)
* **vue2-core:** 暴露 okBtnProps ([c832a07](https://github.com/lljj-x/vue-json-schema-form/commit/c832a07eab0d4174d62da42a739bfa7e1f69fa44))
* **vue3-core:** 允许传递props至formFooter ([60ee613](https://github.com/lljj-x/vue-json-schema-form/commit/60ee613bda30b818adccd98ad73949ff111df74c))


### Performance Improvements

* **vue3-core:** 优化 okBtnProps 的实现方式 ([adfe93e](https://github.com/lljj-x/vue-json-schema-form/commit/adfe93e58a9e8fedc2b0c26484be5691ccc3f65a))





# [1.7.0](https://github.com/lljj-x/vue-json-schema-form/compare/v1.6.4...v1.7.0) (2021-08-29)


### Bug Fixes

* **demo:** 修复element plus无法打开，锁定element plus cdn版本 ([a3c4312](https://github.com/lljj-x/vue-json-schema-form/commit/a3c43121cee3cdfc06844974028f8c78f5486e4f))
* **schema-generator:** 修复array 下object排序问题 ([55dc50e](https://github.com/lljj-x/vue-json-schema-form/commit/55dc50e128417a67e9d186d3fcd6e2340d713144))


### Features

* **lib:** 支持配置 slots ([27f1501](https://github.com/lljj-x/vue-json-schema-form/commit/27f1501eda01eabd4a723656be56904e9cb0f069)), closes [#45](https://github.com/lljj-x/vue-json-schema-form/issues/45)





## [1.6.4](https://github.com/lljj-x/vue-json-schema-form/compare/v1.6.3...v1.6.4) (2021-07-18)


### Bug Fixes

* **vue3 antd:** 修复color format选择颜色 ([378c2e1](https://github.com/lljj-x/vue-json-schema-form/commit/378c2e1aa6767553998cacf52321a6d5b5bee84e))





## [1.6.3](https://github.com/lljj-x/vue-json-schema-form/compare/v1.6.2...v1.6.3) (2021-07-12)

**Note:** Version bump only for package vue-element-schema-form





## [1.6.2](https://github.com/lljj-x/vue-json-schema-form/compare/v1.6.1...v1.6.2) (2021-05-31)

**Note:** Version bump only for package vue-json-schema-form





## [1.6.1](https://github.com/lljj-x/vue-json-schema-form/compare/v1.6.0...v1.6.1) (2021-05-26)


### Bug Fixes

* **lib:** 修复 d.ts 申明文件错误 ([860c3b4](https://github.com/lljj-x/vue-json-schema-form/commit/860c3b42a38ac3e76b2e16c3d74a45c7cd95dfa1))





# [1.6.0](https://github.com/lljj-x/vue-json-schema-form/compare/v1.5.0...v1.6.0) (2021-05-22)


### Features

* **lib:** form-mounted event 添加formData 参数 ([c54202c](https://github.com/lljj-x/vue-json-schema-form/commit/c54202c27304add9636a7062c05c80c60fc200a6))





# [1.5.0](https://github.com/lljj-x/vue-json-schema-form/compare/v1.4.0...v1.5.0) (2021-05-09)


### Features

* **lib:** 优化anyOf切换选项值的复用，修复vue3 anyOf无法切换选项 ([6159160](https://github.com/lljj-x/vue-json-schema-form/commit/6159160d1727165e706343187aca129360dc011f))





# [1.4.0](https://github.com/lljj-x/vue-json-schema-form/compare/v1.3.0...v1.4.0) (2021-04-22)


### Features

* **lib:** 调整 widget onChange prop参数格式，添加 formData参数 ([4c441fc](https://github.com/lljj-x/vue-json-schema-form/commit/4c441fce239ade40b10a42bf361c3ee920a044ed)), closes [#45](https://github.com/lljj-x/vue-json-schema-form/issues/45)





# [1.3.0](https://github.com/lljj-x/vue-json-schema-form/compare/v1.2.1...v1.3.0) (2021-04-15)


### Bug Fixes

* **core:** 修复 anyof 后代存在 $ref可能无法回填的问题 ([4dd046b](https://github.com/lljj-x/vue-json-schema-form/commit/4dd046bee0e5c3589f2bfa64ba0d90ed7869067a)), closes [#59](https://github.com/lljj-x/vue-json-schema-form/issues/59)


### Features

* **core:** widget 节点直接配置onChange ([2d2264b](https://github.com/lljj-x/vue-json-schema-form/commit/2d2264b004c3b6586e225c563bf03ca52fc5e53a))





## [1.2.1](https://github.com/lljj-x/vue-json-schema-form/compare/v1.2.0...v1.2.1) (2021-04-11)


### Bug Fixes

* **lib:** 修复anyOf下多级对象初始值计算错误问题 ([6dd9780](https://github.com/lljj-x/vue-json-schema-form/commit/6dd97804573aa55001c2715da4a6ffcc5ee897b9)), closes [#57](https://github.com/lljj-x/vue-json-schema-form/issues/57)





# [1.2.0](https://github.com/lljj-x/vue-json-schema-form/compare/v1.1.3...v1.2.0) (2021-03-30)


### Features

* **lib:** 添加 fallback-label 参数 ([cd2d8c3](https://github.com/lljj-x/vue-json-schema-form/commit/cd2d8c3ed72b9bc03e44eb5b86eb1b18fe67c34c)), closes [#45](https://github.com/lljj-x/vue-json-schema-form/issues/45)





## [1.1.3](https://github.com/lljj-x/vue-json-schema-form/compare/v1.1.2...v1.1.3) (2021-03-18)

**Note:** Version bump only for package vue-element-schema-form





## [1.1.2](https://github.com/lljj-x/vue-json-schema-form/compare/v1.1.1...v1.1.2) (2021-03-07)


### Bug Fixes

* **vue3-antd:** 修复form label 双冒号问题 ([5b4f16c](https://github.com/lljj-x/vue-json-schema-form/commit/5b4f16c3c1a4f4b784c2fd5c1fbe7eec40cf8d7b)), closes [#46](https://github.com/lljj-x/vue-json-schema-form/issues/46)





## [1.1.1](https://github.com/lljj-x/vue-json-schema-form/compare/v1.1.0...v1.1.1) (2021-03-06)


### Bug Fixes

* **vue2-iview3:** 修复iveiws组件透透传slot失效 ([f86ec5f](https://github.com/lljj-x/vue-json-schema-form/commit/f86ec5f77f98a40ee31989cf6e554504059b910d))





# [1.1.0](https://github.com/lljj-x/vue-json-schema-form/compare/v1.0.2...v1.1.0) (2021-03-06)


### Features

* **vue3-ant:** 更新初始化 ([71a2810](https://github.com/lljj-x/vue-json-schema-form/commit/71a281045af11f215333050396aa546dd5e78b88)), closes [#27](https://github.com/lljj-x/vue-json-schema-form/issues/27) [#27](https://github.com/lljj-x/vue-json-schema-form/issues/27) [#27](https://github.com/lljj-x/vue-json-schema-form/issues/27) [#40](https://github.com/lljj-x/vue-json-schema-form/issues/40)





## [1.0.2](https://github.com/lljj-x/vue-json-schema-form/compare/v1.0.1...v1.0.2) (2021-01-31)


### Bug Fixes

* **style:** 修复p标签等自带边距导致的样式问题  ([7b7e43e](https://github.com/lljj-x/vue-json-schema-form/commit/7b7e43eaa06c14a436b34c38d6d69aad27d67512))





## [1.0.1](https://github.com/lljj-x/vue-json-schema-form/compare/v1.0.0...v1.0.1) (2021-01-31)


### Bug Fixes

* **vue2-element:** 修复 vue2-elementUi package 配置问题 ([fcc30d6](https://github.com/lljj-x/vue-json-schema-form/commit/fcc30d6c1b1214b71784d50b14385a4444d4ff43))





## [0.6.1](https://github.com/lljj-x/vue-json-schema-form/compare/v0.6.0...v0.6.1) (2021-01-19)

**Note:** Version bump only for package vue-element-schema-form





# [0.6.0](https://github.com/lljj-x/vue-json-schema-form/compare/v0.5.0...v0.6.0) (2021-01-19)


### Bug Fixes

* **lib:** 修复 anyOf 类型，编辑时不能匹配正确选项 ([d747722](https://github.com/lljj-x/vue-json-schema-form/commit/d7477227d004e47c2b186c3eb956e4c83d7077ad)), closes [#31](https://github.com/lljj-x/vue-json-schema-form/issues/31)
* **lib:** 解决打包后包含es6代码问题 ([f03352e](https://github.com/lljj-x/vue-json-schema-form/commit/f03352eb129c45963ad41e3e91eebe102c303913)), closes [#29](https://github.com/lljj-x/vue-json-schema-form/issues/29)


### Features

* **iview3:** 适配iview3 footer btn ([b734ae0](https://github.com/lljj-x/vue-json-schema-form/commit/b734ae062bb21e82cfec59739de6de843d752b4c))
* 添加初始化 iview ([f8b59ce](https://github.com/lljj-x/vue-json-schema-form/commit/f8b59ce6bcc3830c051f1aa823ad9c5d06cae61d))
* **demo:** demo页面添加ui 框架切换 ([c3f76f7](https://github.com/lljj-x/vue-json-schema-form/commit/c3f76f7272be6f8132e467b130d6f230a048fb9b))
* **iview:** 添加iview i-switch 组件转换 ([8fae70c](https://github.com/lljj-x/vue-json-schema-form/commit/8fae70cb28f7fd02073d6d4318861b7f08f6199b))
* **iview3:** 适配 iview ([c969d97](https://github.com/lljj-x/vue-json-schema-form/commit/c969d97b6d908eabe8c1f60b8c3625b41fbb661a))
* 适配iview3 upload 组件 ([16060af](https://github.com/lljj-x/vue-json-schema-form/commit/16060af6743c678b4c64e98d58f9503b817d3921))
* **vue2-iview3:** 完成iview3时间选择和样式优化 ([27e310e](https://github.com/lljj-x/vue-json-schema-form/commit/27e310e298498ee5a2466f4d6c7d4153ad8b9777))
* **vue2-iview3:** 适配 iview3 ([0120d2b](https://github.com/lljj-x/vue-json-schema-form/commit/0120d2b9a265cf0bffee099c2d4974c883c08a25)), closes [#27](https://github.com/lljj-x/vue-json-schema-form/issues/27)
* **vue3:** init vue3 core ([df2c1fe](https://github.com/lljj-x/vue-json-schema-form/commit/df2c1fe9873a5e13eeafff924f7d9ab369824fbd))
* **vue3:** 完成 vue3 form组件 ([1c5deba](https://github.com/lljj-x/vue-json-schema-form/commit/1c5debae4cb92f3f54de64d8f38c98396022a344))
* **vue3:** 更新vue3 form 组件 ([ab481d6](https://github.com/lljj-x/vue-json-schema-form/commit/ab481d675c4b84a29aa689b99d9d2f8f17fae86d))
* **vue3-core:** 初始化vue3-core ([f22a51c](https://github.com/lljj-x/vue-json-schema-form/commit/f22a51cd732c21a244b770cbcae0f9ceb0156c57))
* 适配 iview3 ([d4ee166](https://github.com/lljj-x/vue-json-schema-form/commit/d4ee166a7dd71bb9a840525f4eb15c4fdc97f11d))
* 适配 iview3 ([2df6957](https://github.com/lljj-x/vue-json-schema-form/commit/2df69575b4ad2650c2e75863ffcf0c306e42f21e))
* 适配iview 时间日期 ([0baa3cd](https://github.com/lljj-x/vue-json-schema-form/commit/0baa3cdfd22ac19191dfc8adddd7f0bdc3520bf0))





# [0.5.0](https://github.com/lljj-x/vue-json-schema-form/compare/v0.4.1...v0.5.0) (2020-12-25)


### Bug Fixes

* **lib:** 修复 anyOf 切换时原item下错误不会清除问题 ([8d0b09a](https://github.com/lljj-x/vue-json-schema-form/commit/8d0b09a36a23626d34ffba46bad02d96e060b30e))
* **uploadwidget:** 修复上传图片 picture 模式文件获取错误问题 ([e672d74](https://github.com/lljj-x/vue-json-schema-form/commit/e672d7425521b9b3fc51e0bea1f5d101a669a7f8))


### Features

* **lib:** uploadWidget 组件支持slots 配置function 接受createElement参数 ([2ceebcb](https://github.com/lljj-x/vue-json-schema-form/commit/2ceebcb6970bf0a46d0f8a80acb6dbe3ebcd7b80))
* 下拉选项组件支持直接配置ui:enumOptions，优先级高于schema默计算出的下拉选项 ([af8bee4](https://github.com/lljj-x/vue-json-schema-form/commit/af8bee437cae86deae38480cce6607e7dd42b867))
* **lib:** 添加on-validation-failed event，表单校验失败触发 ([388454e](https://github.com/lljj-x/vue-json-schema-form/commit/388454eac1fd1c1d5aa205e965c477604176df09))
* **lib:** 配置 format color，默认使用 el-color-picker 组件 ([be915ad](https://github.com/lljj-x/vue-json-schema-form/commit/be915ad8eace3b33bbb70180788c251dafbac50e))





# [0.4.0](https://github.com/lljj-x/vue-json-schema-form/compare/v0.3.0...v0.4.0) (2020-12-05)


### Features

* **lib:** 更新eslint配置 ([6c8d9d5](https://github.com/lljj-x/vue-json-schema-form/commit/6c8d9d5ab355c895e6983ee01cfad0f610781eeb))





# [0.3.0](https://github.com/lljj-x/vue-json-schema-form/compare/v0.2.2...v0.3.0) (2020-12-03)


### Bug Fixes

* **lib:** 修复array widget 覆盖多选类型问题 ([d7453b3](https://github.com/lljj-x/vue-json-schema-form/commit/d7453b33abea5f903a3cbee073172a28c3cf02ac))
* **lib:** 修复array 多选类型不配置required ，导致array minItems 等后续不校验问题 ([683380e](https://github.com/lljj-x/vue-json-schema-form/commit/683380eb824a4e4dc281eda98f19deb64b0c3fa7))


### Features

* 优化 anyOf 切换 ([2c2388d](https://github.com/lljj-x/vue-json-schema-form/commit/2c2388d0b46e068ec24c9e64e7ec2154e3237a59))





## [0.2.2](https://github.com/lljj-x/vue-json-schema-form/compare/v0.2.1...v0.2.2) (2020-11-25)

**Note:** Version bump only for package vue-json-schema-form





## [0.2.1](https://github.com/lljj-x/vue-json-schema-form/compare/v0.2.0...v0.2.1) (2020-11-25)


### Bug Fixes

* **schema generator:** 修复schema生成器预览不支持% ([ff0d2da](https://github.com/lljj-x/vue-json-schema-form/commit/ff0d2da9b1944056185803898d3a2c66194cc508))
* **schema generator:** 多选类型强制 uniqueItems ([cd3349e](https://github.com/lljj-x/vue-json-schema-form/commit/cd3349ed960bdf2908ffd76ffce86cf99914b222))





# [0.2.0](https://github.com/lljj-x/vue-json-schema-form/compare/v0.1.3...v0.2.0) (2020-11-24)


### Bug Fixes

* **lib:** 修复lib boolean 类型使用select渲染时，label=true 导致props类型校验错误 ([70ac8fc](https://github.com/lljj-x/vue-json-schema-form/commit/70ac8fc02b47e6e51e42be9d97daab998bfdadc9))
* **lib:** 修复数组多选框默认值错误问题，修复anyOf选项数据可能合并错误 ([bf4a086](https://github.com/lljj-x/vue-json-schema-form/commit/bf4a086433b420ac0b9aa570bd13ff935c2ddd10))
* **lib:** 修复默认schema生成formData和默认值相等时导致可能不能及时更新的问题 ([590e37d](https://github.com/lljj-x/vue-json-schema-form/commit/590e37dd67d6863d3bb2867e978f83fa52a1fb9c))


### Features

* **demo:** 更新demo页ui样式 ([89b93b2](https://github.com/lljj-x/vue-json-schema-form/commit/89b93b26d0a57e623e6e2784e4636a7aefb32738))
* **lib:** array 类型 item title description 支持 $index 特殊字符 ([8922650](https://github.com/lljj-x/vue-json-schema-form/commit/89226508fa8dcdb55fe930a014e6ec7d1cc6a9bd)), closes [#19](https://github.com/lljj-x/vue-json-schema-form/issues/19)
* **lib:** ui配置支持 ui:xxx 配置表达式 ([570dd57](https://github.com/lljj-x/vue-json-schema-form/commit/570dd577fe88b779d37afb8fba8199b97edb2f73)), closes [#19](https://github.com/lljj-x/vue-json-schema-form/issues/19)
* **lib:** 对ui:xxx 配置支持表达式，options 内不支持表达式以便区分 ([7c20bb8](https://github.com/lljj-x/vue-json-schema-form/commit/7c20bb8c11d5038eca37d5fdb151ae250f7dc074))
* **lib:** 支持 column 布局，1 2 3 列 ，同时支持单个 widget 配置ui:width 指定宽度 ([a088a6f](https://github.com/lljj-x/vue-json-schema-form/commit/a088a6f21448e77f371e8391d93c03aa2e99a3e9))
* **schema generator:** 完成schema生成器 input 组件配置化 ([9d7cc67](https://github.com/lljj-x/vue-json-schema-form/commit/9d7cc67802353b3772e5937aeac9345ec0b46570))
* **schema generator:** 支持基础组件拖入生成 ([93e344e](https://github.com/lljj-x/vue-json-schema-form/commit/93e344e48ce50d3933830c90113dd5d789a0a371))
* **schema generator:** 添加schema generator 参数formLabel左右布局时隐藏description ([f13a159](https://github.com/lljj-x/vue-json-schema-form/commit/f13a159977d8f1677e8942dce2b1e53283943b82))
* **schema-generator:** 优化schema-generator参数配置 ([82d0b7d](https://github.com/lljj-x/vue-json-schema-form/commit/82d0b7d4430d92ae8094044dec3dfa521ed5c410))
* **schema-generator:** 优化导出代码 ([20d429c](https://github.com/lljj-x/vue-json-schema-form/commit/20d429c60f49f7e8181ece0b53974f303fec0c5f))
* **schema-generator:** 修复 schema-generator 导出schema参数丢失问题 ([23f9615](https://github.com/lljj-x/vue-json-schema-form/commit/23f961579dc11fe8a7626186b4f9736c4e1203c6))
* **schema-generator:** 初始化 schema-generator ([3a743ee](https://github.com/lljj-x/vue-json-schema-form/commit/3a743ee48c50493fb17a19cc0657cb351ef5a111))
* **schema-generator:** 完善表单设计器组件库 ([26afd79](https://github.com/lljj-x/vue-json-schema-form/commit/26afd79687263149a1e29c0adf03de3b7bd7f6db))
* **schema-generator:** 更新schema生成器 支持配置数组 ([0f4d3b4](https://github.com/lljj-x/vue-json-schema-form/commit/0f4d3b4be1b47fb89571500cd8749fed6a412a38))
* **schema-generator:** 添加日期相关组件 ([bcb2836](https://github.com/lljj-x/vue-json-schema-form/commit/bcb283665eab561608062255c5f197f5a1e1a5aa))
* **schema-generator:** 生成表单编辑器 ([dd5eecb](https://github.com/lljj-x/vue-json-schema-form/commit/dd5eecb607e2be8e000a56dd5202d3a9c02d38a0))
