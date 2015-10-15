sseweb-gmap-filter
==================

嵌入谷歌地图。

## 安装

启用本模块后，前往 `admin/config/content/formats` 配置过滤器。

请确保 `将URL转换成链接` 在本过滤器之后，`限制使用HTML标记` 在本过滤器之前

## 使用方法

基本：`[gmap:URL]`

长宽：`[gmap:URL width:600 height:450]`

其中，`URL` 必须以 `/maps/embed` 开头。您可以[使用 API 生成该地址](https://developers.google.com/maps/documentation/embed/start)，或直接使用谷歌地图中的分享功能生成地址（不支持多语言，但支持具体路线）。
