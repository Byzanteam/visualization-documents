# Icon 图标

# Props
- **name** *(required)*: `string` 图标名字。
- **group** *(Default: `'default'`)*: `string` 图标分组。
- **size** *(Default: `'default'`)*: `string | Enum('small', 'default', 'large')` 图标大小，有三种内置的大小。也可以设置任意合法的 CSS 长度。
- **color** *(Default: `''`)*: `string | object` 图标颜色。可以是任意合法的 CSS 颜色字符串，也可以通过 Object 设置多个[自定义属性](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_variables)。

- **invert** *(Default:`false`)*: `boolean` 设置图标是否反色显示。
- **backgroundColor** *(Default:`initial`)* `string` 设置背景色。
- **borderStyle** *(Default:`none`)*: `string` 设置边框的风格。如果不设置宽度于颜色都不会出现，可以用缩写的形式传入。
- **borderWidth** *(Default:`initial`)*: `string`设置边框宽。
- **borderRadius** *(Default:`50%`)*: `string` 边框的半径（弧度）。
- **borderColor** *(Default:`#ffffff`)*: `string` 边框的颜色。