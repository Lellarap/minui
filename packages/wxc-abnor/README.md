# wxc-abnor

> MinUI 小程序组件 - 异常流提示

## Install

``` bash
$ min install @minui/wxc-abnor
```

> Please make sure you have installed [Min-Cli](https://github.com/meili/min-cli)☟

```
$ npm install -g @mindev/min-cli
```

For more information about MinUI, please visit [MinUI in Github](https://github.com/meili/minui).


## API

### Abnor【props】

| 名称                  | 描述                         |
|----------------------|------------------------------|
|`type`                | [说明]：异常状态类型，其优先级低于其他属性。<br>[类型]：`String`<br>默认值：`""` <br>[可选值]：`REQUEST_ERROR, NOT_FOUND, DATA, FOLLOW, FEED,SHOP, WEIBO, SEARCH, TAG, MESSAGE, LIVE, ORDER, CART, FOOTPRINT, COUPON`|
|`image`               | [说明]：背景图。若与 `type` 同时指定，将覆盖 `type` 对应的 `image` 。<br>[类型]：`String`<br>[默认值]：`""` <br>   |
|`title`               | [说明]：标题。若与 `type` 同时指定，将覆盖 `type` 对应的 `title` 。<br>[类型]：`String`<br>[默认值]：`""` <br>     |
|`tip`                 | [说明]：副标题。若与 `type` 同时指定，将覆盖 `type` 对应的 `tip` 。<br>[类型]：`String`<br>[默认值]：`""` <br>       |
|`button`              | [说明]：按钮文案。若与 `type` 同时指定，将覆盖 `type` 对应的 `button` 。<br>[类型]：`String`<br>[默认值]：`""` <br>  |
|`bindabnortap`        | [说明]：按钮事件。若配置了 `button` 属性，则需要指定事件。其中 `REQUEST_ERROR, NOT_FOUND` 两种 `type` 中均设置了默认的按钮文案 |

##  ChangeLog

#### v1.0.1（2017.10.24）

- 初始版本