# 翻译 vue3 issue/PR 的标签

[vue3 issue](https://github.com/vuejs/vue-next/issues)
[vue3 issue/PR labels](https://github.com/vuejs/vue-next/labels)

## bug 相关

| 标签名             | 标签译名               | 注释                                                              |
| ------------------ | ---------------------- | ----------------------------------------------------------------- |
| 🐞 bug             | 🐞 缺陷                | 有些代码出错了                                                    |
| 🧹 p1-chore        | 🧹 优先级 1 - 日常事务 | 优先级 1 : 不影响代码行为                                         |
| 🍰 p2-nice-to-have | 🍰 优先级 2 - 可有可无 | 优先级 2 : 它不破坏任何行为，但解决了更好                         |
| 🔨 p3-minor-bug    | 🔨 优先级 3 - 边界情况 | 优先级 3 : 它修复了只影响特殊情况的边界条件的 bug                 |
| ❗ p4-important    | ❗ 优先级 4 - 重大影响 | 优先级 4 : 它修复了违背说明文档的错误行为的 bug，或显著提高了性能 |
| 🔥 p5-urgent       | 🔥 优先级 5 - 十万火急 | 优先级 5 : 它修复了影响大多数用户的破坏性 bug，并应该尽快发布     |
| 🔩 p2-edge-case    | 🔩 p2 - 边界情况       |                                                                   |

## feat 相关

| 标签名                | 标签译名                   | 注释           |
| --------------------- | -------------------------- | -------------- |
| ✨ enhancement        | ✨ (特性/功能) 增强        | 新特性或新需求 |
| feat: compiler        | 特性 : 编译器              |                |
| feat: custom elements | 特性 : 自定义元素          |                |
| feat: hmr             | 特性 : 热更新              |                |
| feat: keep-alive      | 特性 : keep-alive 组件     |                |
| feat: reactivity      | 特性 : 响应式              |                |
| feat: script-setup    | 特性 : script-setup 语法糖 |                |
| feat: sfc             | 特性 : 单文件组件          |                |
| feat: sfc-style-vars  | 特性 : 状态驱动的动态 CSS  |                |
| feat: slots           | 特性 : 插槽                |                |
| feat: ssr             | 特性 : 服务端渲染          |                |
| feat: suspense        | 特性 : suspense 组件       |                |
| feat: teleport        | 特性 : teleport 组件       |                |
| feat: transition      | 特性 : transition 组件     |                |
| feat: types           | 特性 : typescript 类型相关 |                |
| feat: v2 compat       | 特性 : 兼容 vue2.x         |                |
| feat: v-model         | 特性 : v-model             |                |
| feat: v-on            | 特性 : v-on                |                |

## 其他

| 标签名                 | 标签译名           | 注释                                             |
| ---------------------- | ------------------ | ------------------------------------------------ |
| browser specific       | 特定浏览器         |                                                  |
| comment or text update | 注释或文本的更新   | 这个 PR 只修改了注释或文本文件，没有修改逻辑代码 |
| dependencies           | 依赖项             | 这个 PR 更新依赖项文件                           |
| duplicate              | 重复项             | 这个 issue 或 PR 已经存在                        |
| good first issue       | 优秀的第一个 issue | 给新朋友的褒奖                                   |
| has PR                 | (issue) 有 PR      | 已经有一个提交的 PR 来解决这个 issue             |
| has workaround         | (issue) 有应变方法 | 发现了一个防止这个 issue 发生的应变方法          |
| help wanted            | 需要帮助           | 需要特别关注                                     |
| invalid                | 无效的             | 这似乎不对                                       |
| need guidance          | 需要指导           | PR 中的解决方法需要来自维护者的指导来继续推进    |
| need more info         | 需要更多信息       | 需要更深入的信息                                 |
| need test              | 需要测试           | 这个 PR 缺少测试用例                             |
| 🛑 on hold             | (PR) 处于搁置状态  | 这个 PR 需要等待其他工作完成后，才能被合并       |
| planned: 3.2           | 计划版本: 3.2      |                                                  |
| ready to merge         | 准备合并           | 这个 PR 将被合并                                 |
| 🔍 review needed       | 🔍 需要审查        | 这个 PR 需要一位团队成员进行审查                 |
| security               | 安全               | 用于解决安全漏洞的 PR                            |
| sfc-playground         | 单文件组件游乐场   |                                                  |
| wontfix                | 不予修复           | 这个 issue 不会被修复                            |
