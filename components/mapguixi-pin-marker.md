# MapGuixiPinMarker 桂溪地图图钉标记

## Props

| prop     | type                 | desc                     | default   |
| -------- | -------------------- | ------------------------ | --------- |
| content  | `Enum(string, node)` | 弹出内容                 | `require` |
| isActive | `boolean`            | 图标是否为活跃状态       | `false`   |
| order    | `number`             | 该图钉在搜索结果中的排序 | `require` |

## Events

| event   | args | desc                 |
| ------- | ---- | -------------------- |
| onClick | `()` | 标记被点击的回调函数 |

