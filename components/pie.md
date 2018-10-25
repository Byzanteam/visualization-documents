# Pie 饼图

## Props

- **data** *(required)*: `Array<object>` 图表数据，对象数组。
- **sort** *(required)*: `string` 分类字段名称。
- **value** *(required)*: `string` 数值字段名称。
- **adjust** *(Default: `false`)*: `boolean` 是否对原始数据进行调整。
- **innerRadius** *(Default: `0`)*: `number` 内半径和外半径的比值。
- **offset** *(Default: `[12, 12]`)*: `[number, number]`
  - **offset[0]**: 起始点与圆弧的距离
  - **offset[1]**: 起始点与拐点的距离
- **order** *(Default: `'DESC'`)*: `Enum('ORIGINAL', 'ASC', 'DESC')` 扇形排序。
- **padding** *(Default: `8`)*: `number | Array<number>` 绘图区域和画布的距离。
- **percentage** *(Default: `true`)*: `boolean` 是否以百分比显示数据。
- **width** *(Default: `'400'`)*: `number | string` 画布宽度。

## Events

-- **onSelectionChanged** *(Default: `() => {}`)*: `(selections: Array<object>) => void` 选中扇形改变事件，当前选中扇形数据作为参数传入。
