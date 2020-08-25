# 1.1.2

插件市场<https://ext.dcloud.net.cn/plugin?id=2312>

## loadMore 底部加载更多

### 使用方法

#### 引入

```javascript
import aLoadMore from "@/components/a_loadMore/a_loadMore";
Vue.component("aLoadMore", aLoadMore);
```

```html
<aLoadMore :status="" mode="" color="" textColor="" textSize="" padding="" :loadTitle=""></aLoadMore>
```

#### props 值说明

|   属性    | 默认值                          |                可选                 |  类型   |          简介           |
| :-------: | :------------------------------ | :---------------------------------: | :-----: | :---------------------: |
|   mode    | loading1                        | loading1,loading2,loading3,loading4 | String  |       加载中样式        |
|  status   | loading                         |         down,loading,normal         | String  |          状态           |
| showTitle | true                            |             true,false              | Boolean |      是否显示文本       |
|   color   | #FFF                            |         loading 和 文本颜色         | string  |     loading 背景色      |
| textColor | -                               |            文本字体颜色             | string  |      提示文本颜色       |
| textSize  | -                               |            文本字体大小             | string  |   字体大小 rpx px upx   |
|  padding  | -                               |              上下边距               | string  | 上下边距大小 rpx px upx |
| loadTitle | {down: "",loading: normal: "",} |          传入对应格式对象           | Object  |      对应提示文本       |
