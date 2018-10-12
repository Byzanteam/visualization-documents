# MapDonut 地图饼图

## Props

- **activeMarker** *(required)*: `string` 当前选中标记的编号。
- **category** *(required)*: `string` 饼图分类字段名。
- **data** *(Default: `[]`)*: `Array<{}>` 绘制饼图的对象数组。
- **donutId** *(required)*: `string` 当前饼图标记的编号。
- **total** *(Default: `''`)*: `string | number` 所有值的总数。
- **value** *(required)*: `number` 饼图数值字段名。

## Events

- **onClick** *(Default: `() => {}`)*: `function` 饼图点击事件句柄。
