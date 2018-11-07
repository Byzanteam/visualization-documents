# Input

## Props

| prop         | type                                               | desc                                                         | default     |
| ------------ | -------------------------------------------------- | ------------------------------------------------------------ | ----------- |
| autocomplete | `Enum('on', 'off')`                                | 原生的自动完成功能。                                         | `'off'`     |
| autofocus    | `boolean`                                          | 自动获得焦点。                                               | `false`     |
| clearable    | `boolean`                                          | 数据清除按钮，默认不显示。                                   | `false`     |
| defaultValue | `string`                                           | 输入框默认值。                                               | `''`        |
| disabled     | `boolean`                                          | 输入框禁用状态。                                             | `false`     |
| divider      | `boolean`                                          | 是否显示后缀前的分隔线，仅当设置了后缀时有效。               | `false`     |
| icon         | `string`                                           | 图标名称。可用名称参见 `Icon` 组件。设置 **icon** 会使前缀失效。 | `''`        |
| maxlength    | `number`                                           | 最大输入字数。                                               | N/A         |
| name         | `string`                                           | 输入框名字。                                                 | N/A         |
| placeholder  | `string`                                           | 占位文本。                                                   | `'请输入'`  |
| readonly     | `boolean`                                          | 设置输入框只读。                                             | `false`     |
| size         | `Enum('default', 'large')`                         | 输入框尺寸。                                                 | `'default'` |
| spellcheck   | `boolean`                                          | 原生拼写检查功能。                                           | `false`     |
| type         | `Enum('date', 'email', 'password', 'text', 'url')` | 输入框类型。                                                 | `'text'`    |
| width        | `string`                                           | 输入框宽度。                                                 | `'100%'`    |

## Events

| event         | args                                 | desc                   |
| ------------- | ------------------------------------ | ---------------------- |
| onChange      | `(value: string, prevValue: string)` | 组件值改变的回调函数。 |
| onEnter       | `(value: string)`                    | 按下回车键的回调函数。 |
| onSuffixClick | `(value: string)`                    | 后缀被电击的回调函数。 |

## Slots

| slot   | desc         |
| ------ | ------------ |
| prefix | 输入框前缀。 |
| suffix | 输入框后缀。 |
