# mapbox-gl-4490

> 说明：本程序涉及的 mapbox-gl.js 均从网络获得（来源未知），其源代码归原作者所有。此处仅为了开发方便将 mapbox-gl.js 封装打包成 npm 包。

## 使用

```
const map = new mapboxl.Map({
    ....
    epsg:'4490', //增加属性配置epsg, 指定 3867,4490，4326
    ....
})
```

## 特别说明

此版本在使用中已发现：在 4490 下，使用 geojson layer 启用 cluster 会报错。

#更新说明

## v0.1.0

基于 mapbox-gl（v2.13.0）修改的 mapboxgl api js 库（支持 3857、4490、4326）
