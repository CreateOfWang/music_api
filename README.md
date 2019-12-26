# music_api


#### 介绍
1. 支持网易云音乐和QQ音乐的在线搜索的后端API
2. vue2.x客户端链接（随搜听）：https://github.com/hcyhehe/nbPlayer


#### 软件架构
基于nodejs+express开发而成


#### 安装教程
1. 安装依赖：npm install 
2. 运行：node app.js


#### 使用说明
1.  后台监听端口在config/setting.js里面设置，不设置默认为8086
2.  路由文件为routes/api_router.js
3.  网易云音乐搜索接口：/net163/search，method为get，参数为keywords
4.  QQ音乐搜索接口：/qq/search，method为get，参数为key


#### 版本更新计划
1.  后期加入虾米音乐的搜索功能
2.  加入歌曲详情页的API


