# Pagination

## Props
| prop          | type                                 | desc                    |     default            |
| ------------- | ------------------------------------ | ----------------------  | ---------------------- |
|total          | `number`                             | 数据总数(会计算出页数)     | 0
|defaultCurrent | `number`                             | 初始化当前页数            | 1
|defaultPageSize| `number`                             | 初始化每页条数            | 5

## Event
| event         | args                                 |  desc                  |
| ------------- | ------------------------------------ | ---------------------- | 
| onChange      | `(current: number)`                  | 当发生页面切换的时候调用   |
