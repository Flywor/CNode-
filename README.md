# CNode罗
一个基于https://cnodejs.org 提供API的小程序项目
目前已发布上线，可自行搜索"CNode罗"
或扫描二维码：

#已实现功能：
1.基础的浏览
2.登录（扫描官网提供的二维码，token仅保存在storage，绝不会窃取使用，如不放心可自行注册测试账号抓包检查）
3.收藏、查看收藏（点击首页头像）
4.回贴（普通text文本）
5.点赞
6.消息通知、查看

#未实现功能：
1.发帖、编辑帖子（没有富文本编辑插件，同时个人小程序无法嵌入web-view）
2.富文本较好的渲染（虽然采用了wxParse来渲染从服务器拉下来的html，但是转换并不尽人意，比如代码块的html代码有时候也会直接被渲染成wxml。。换行符只有在text标签才生效，但是text标签只能嵌入text标签。。。）
