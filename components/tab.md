# Tab 标签页

## Props

| prop | type | desc | default |
| ---- | ---- | ---- | ------- |
| activeTab | `string` | 默认选中标签名 | *第一个面板* |
| position | `Enum('top', 'bottom', 'left', 'right')` | 按钮栏位置 | `'top'` |
| size | `Enum('default', 'large')` | 标签大小 | `'default'` |
| type | `Enum('button', 'label')` | 标签类型 | `'label'` |

## Events

| event | args | desc |
| ----- | ---- | ---- |
| onTabClick | `(name: string)` | 标签点击的回调，入参为当前点击的面板名称 |

## TabPane 标签页面板

### Props

| prop | type | desc | default |
| ---- | ---- | ---- | ------- |
| icon | `string` | 图标名称 | *N/A* |
| name | `string` | 标签页名称 | *require* |
