# virtual-list虚拟列表

## 基础用法
<demo src="./demos/basic.vue"></demo>

## 属性

| 属性         | 类型      | 描述                                           | 默认值   |
|--------------|-----------|------------------------------------------------|----------|
| height       | `Number`  | 虚拟列表的高度（以像素为单位）                | `无`     |
| itemHeight   | `Number`  | 每个列表项的高度（以像素为单位）              | `无`     |
| data         | `Array`   | 列表的数据源，包含每一项的数据                | `[]`     |
| @click-item  | `Function`| 点击列表项时触发的事件，返回被点击的项       | `无`     |
| title        | `Slot`    | 自定义标题的插槽                              | `无`     |
| item         | `Slot`    | 自定义项的插槽，接收当前项作为参数            | `无`     |