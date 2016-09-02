## 多功能系统管理（可二次开发）
>### 示例:

    登录界面：背景用HTML5特效自动切换(百叶窗，幕布等多种切换方式)
![alt](https://github.com/czxapple/Resource/blob/master/ADMIN-%20B1.png)
![alt](https://github.com/czxapple/Resource/blob/master/ADMIN-%20B2.png)

    首页
![alt](https://github.com/czxapple/Resource/blob/master/ADMIN-%20(3).png)

    菜单管理：无限级别自定义菜单，自定义菜单图标，业务菜单和系统菜单分离，菜单状态显示隐藏（递归处理）
![alt](https://github.com/czxapple/Resource/blob/master/ADMIN-%20(4).png)

    数据字典：无限级别，支持多级别无限分类。内设编号，排序等
![alt](https://github.com/czxapple/Resource/blob/master/ADMIN-%20(5).png)

    在线管理：websocket技术，实时检测在线用户列表，统计在线人数,可强制用户下线 同一用户只能在一个客户端登录
![alt](https://github.com/czxapple/Resource/blob/master/ADMIN-%20(6).png)

    代码生成：生成完整的模块代码，并保留生成记录模版，可复用 
    正向生成:  生成完整的模块，页面、处理类、service层、myabaits的xml 建表的sql脚本等
    反向生成:  任意连接其它数据库(mysql、oracle、sqlserver)，根据表反射生成本系统的模块
![alt](https://github.com/czxapple/Resource/blob/master/ADMIN-%20(7).png)

    表单生成：表单代码生成器
![alt](https://github.com/czxapple/Resource/blob/master/ADMIN-%20(8).png)

    发送邮件：单发，群发邮件 
![alt](https://github.com/czxapple/Resource/blob/master/ADMIN-%20(9).png)

    置二维码：生成二维码图表保存到服务器 or  解析读取二维码内信息 
![alt](https://github.com/czxapple/Resource/blob/master/ADMIN-%20(10).png)

    图表报表：柱状图、饼状图、折线图、各种图表大全
![alt](https://github.com/czxapple/Resource/blob/master/ADMIN-%20(11).png)

    地图选点获取经纬度坐标，根据俩经纬度计算距离
![alt](https://github.com/czxapple/Resource/blob/master/ADMIN-%20(12).png)

    数据库连接池  阿里的 druid。Druid在监控、可扩展性、稳定性和性能方面都有明显的优势,支持并发
![alt](https://github.com/czxapple/Resource/blob/master/ADMIN-%20(13).png)

    批量异步上传图片，可预览，有进度条，支持拖拽上传(百度webuploader )。列表动态滑动放大展示。
    图片爬虫：输入某网址，爬出其图片显示在页面上，可以放大预览。可保存到服务器上，到图片管理里面
![alt](https://github.com/czxapple/Resource/blob/master/ADMIN-%20(14).png)
![alt](https://github.com/czxapple/Resource/blob/master/ADMIN-%20(15).png)

    数据库备份：可备份单表、整库，支持本地和远程数据库备份
![alt](https://github.com/czxapple/Resource/blob/master/ADMIN-%20(16).png)

    备份定时器：quartz 2.2 强大的任务调度，多线程备份数据库，任务启动关闭异步操作
![alt](https://github.com/czxapple/Resource/blob/master/ADMIN-%20(17).png)


>### 技术特性
    1. 导出 导入 excel 文件
    2  导出word文件
    3. IO 流上传下载文件
    4. 群发邮件，可以发html、纯文本格式，可以发给任意邮箱(实现批量发送广告邮件)
    5. 群发or单独 发送短信，支持两种第三方短信商接口
    6. spring   aop  事务处理
    7. 代码生成器 (freemarker)， 代码 zip 压缩打包
    8. MD5加密 SHA加密（登录密码用此加密）接口加密身份校验
    9. 数据库连接池  阿里的 druid。Druid在监控、可扩展性、稳定性和性能方面都有明显的优势,支持并发
    10.加入安全框架 shiro (登录授权)(session管理)
    11.根据汉字 解析汉字的全拼(拼音)和首字母(导入excel到用户表，根据用户的汉字姓名生成拼音的用户名)
    12.app接口@ResponseBody（支持与其它语言数据交互）
    13.极光推送 (推送给APP及时消息，APP不启动也能收到)
    14.微信接口(身份验证，文本、图文回复等) 微信远程控制服务器重启、锁定、其它应用程序
    15.java Quartz2.2 任务调度 
    16.java websocket 即时通讯技术，点对点，群聊，单聊
    17.Lucene全文检索
    18.Base64传输图片
    19.图片加水印(图片水印，文字水印）
    20.生成 or  解析 二维码
    21.HTML5 + JAVAEE  WebSocket 通信技术，WebSocket 验证用户登录，强制某用户下线
    22.批量异步上传图片，可预览，有进度条，支持拖拽上传(百度webuploader )。列表动态滑动放大展示。
    23.ehcache 自定义二级缓存 ，选择缓存存放目录，处理并发，增加系统性能
    24.服务器内部GET POST 请求
    25.uploadify 上传插件，单条、批量上传多线程，带进度条，异步，图片、视频, 其它文件格式均可上传
    26.地图选点获取经纬度坐标，根据俩经纬度计算距离
    27.tab标签页面功能，标签自由切换，不重复操作数据库
    28.站内信语音提醒，js控制音频播放
    29.百度富文本编辑器，可上传图片
    30.网页爬虫技术，可根据网页地址爬取图片和网页标题等信息(爬取某商城图片保存本服务器)
    
>### 注意事项

    使用代码生成器时
    位置：
![alt](https://github.com/czxapple/Resource/blob/master/ADMIN-(18).png)

    启动生成器  按要求，输入说明，末级包名，类名，表前缀
![alt](https://github.com/czxapple/Resource/blob/master/ADMIN-(19).png)

    添加属性
![alt](https://github.com/czxapple/Resource/blob/master/ADMIN-(20).png)

    生成的文件包
![alt](https://github.com/czxapple/Resource/blob/master/ADMIN-(22).png)

    菜单管理
![alt](https://github.com/czxapple/Resource/blob/master/ADMIN-(28).png)

    新建菜单
![alt](https://github.com/czxapple/Resource/blob/master/ADMIN-(29).png)

    菜单授权 权限管理->角色(基础权限)admin ，在箭头处对其菜单授权
![alt](https://github.com/czxapple/Resource/blob/master/ADMIN-(30).png)

    其它角色对应角色后面授权菜单权限
![alt](https://github.com/czxapple/Resource/blob/master/ADMIN-(31).png)


__Thanks__   ![][foryou]
[foryou]:https://github.com/czxapple/Resource/blob/master/foryou.gif
