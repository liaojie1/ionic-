# ionic-
在自学ionic和项目实际应用后....


导入插件的流程，首先安装插件，然后导入依赖，将其封装到一个服务中，然后用方法来完成操作
下面介绍两种插件
1.打开网页
导入ionic Native中的In App Brower插件(同一个事件只能打开一个应用内浏览器，如果已存在打开一个，用close方法关闭)
Create（url,target,options）
2.分享功能 
导入ionic Native中的Social Sharing插件，安装并添加依赖。
Shart方法（url,message，subject(分享的主题，null),file（是否容许图片,null））
测试
