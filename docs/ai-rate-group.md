# ai-rate-group

评分组。

### Attributes

| 参数 | 说明 | 类型 |可选值 | 默认值 |
| :---: |:---: |:---: |:---:| :---: |
| `index` | 题目索引值 | `Number/String` | - | - |
| `value/v-model` | 绑定值 | `Number/String` | - | `0` |
| `max` | 最大值 | `Number` | - | `5` |
| `showText` | 是否显示辅助文字，若为真，则会从 `texts` 数组中选取当前分数对应的文字内容 | `Boolean` | - | `false` |
| `texts` | 辅助文字数组 | `Array` | - | `[]` |
| `options` | 评分列表配置 | `Array of Object` | - | `[]` |
| `titleStyle` | 定义标题的样式，同 `vue` 中的 `style` prop | `Object/Array` | - | - |
| `titleContent` | 标题的内容 | `String` | - | - |
| `props` | 配置选项 | `Object` | - | 见 <a href="./props.md">props</a> |
| `collectReason`| 是否收集作答原因 | `Boolean` | - | `false` |
| `image` | 问题图片配置选项 | `Object` | - | 见<a href="./image.md">image</a>配置 |