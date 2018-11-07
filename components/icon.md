# Icon 图标

# Props
| prop         | type                                               | desc    | default     | required
| ------------ | -------------------------------------------------- | ------------------------------------------------------------ | ----------- | --|
| name     | required | 图标名字   |    | true|
| group    | `string` | 图标分组   |  `default`  | false|
| size     | `string or Enum('small', 'default', 'large')` | 图标大小   |   `default` | false|
| color    | `string or object` | 图标颜色。可以是任意合法的 CSS 颜色字符串，也可以通过 Object 设置多个[自定义属性](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_variables)   |  `''`  | false|
| invert | `boolean` | 设置图标是否反色显示   |  `false`  | false|
| backgroundColor | `string` | 设置背景色  |    | false|
| borderStyle | `string` | 设置边框的风格,如果不设置,宽度和颜色都不会出现,可以用缩写的形式传入。   | `solid`  | false|
| borderWidth | `string` | 设置边框宽  |  `1px`  | false|
| borderRadius | `string` | 边框的半径（弧度）   | `50%`   | false|
| borderColor | `string` | 边框的颜色  | `#ffffff`   | false|