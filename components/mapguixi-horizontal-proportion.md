# MapGuixiHorizontalProportion 列表内比例图

## Props

| prop     | type            | desc         | default   |
| -------- | --------------- | ------------ | --------- |
| data     | `Array<object>` | 源数据       | *require* |
| category | `string`        | 分类字段名称 | *require* |
| configurations | `object`        | 配置信息 | *require* |
| value    | `string`        | 数据字段名称 | *require* |

## Events

| event                     | args                 | desc                             |
| ------------------------- | -------------------- | -------------------------------- |
| onActiveCategoriesChanged | `(activeCategories)` | 当选中的分类改变时触发的回调函数 |
