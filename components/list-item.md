# Describe

## Props
| prop          | type                                  | desc                 |                        |
| ------------- | ------------------------------------ | ---------------------- | ---------------------- |
| title         | `string`                             | 标题                    |
| content       | `string`                             | 内容                    |
| imgSrc        | `string`                             | 图片地址                 |

## Event
| event         | args                                 |  desc                  |
| ------------- | ------------------------------------ | ---------------------- | 
| onClick       |                                      | 点击回调                |
| onMouseLeave  |                                      | 鼠标移出回调             |
| onMouseEnter  |                                      | 鼠标移入回调             |



# Single
| prop          | type                                  | desc                   |                        |
| ------------- | ------------------------------------ | ----------------------  | ---------------------- |
| content       | `string`                             | 组件值改变的回调函数。      | `''`
| type          | `default,operation`                  | 选择模式                  |  `default`

## Event
| event         | args                                 |  desc                  |
| ------------- | ------------------------------------ | ---------------------- | 
| onClick       |                                      | 点击回调                 |


# Single(type:operation)
## Props
| prop         | type                                 | desc                      |                        |
| -------------| ------------------------------------ | ----------------------    | ---------------------- |
| index        | `number,string`                      | 头部index                  |  `''`
| children     | `all`                                | 组件或者文字                |  `''`
