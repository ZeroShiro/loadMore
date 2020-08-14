# 1.0.0

## loadMore 底部加载更多

### 使用方法

#### 引入

```javascript
import aLoadMore from "@/components/a_loadMore/a_loadMore";
Vue.component("aLoadMore", aLoadMore);
```

```html
<aLoadMore :status="status" mode="loading1"></aLoadMore>
```

#### props 值说明

|   属性    | 默认值                          |                可选                 |  类型   |          简介           |
| :-------: | :------------------------------ | :---------------------------------: | :-----: | :---------------------: |
|   mode    | loading1                        | loading1,loading2,loading3,loading4 | String  |       加载中样式        |
|  status   | loading                         |         down,loading,normal         | String  |          状态           |
| showTitle | true                            |             true,false              | Boolean |      是否显示文本       |
|   color   | #                               |         loading 和文本颜色          | string  | loading4 需手动改变颜色 |
| loadTitle | {down: "",loading: normal: "",} |          传入对应格式对象           | Object  |      对应提示文本       |
