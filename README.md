# chatroom
该项目主要为广发证券实习小demo，实习要求
设计一个简易聊天系统，尽可能实现如下功能：
1、【基本功能】支持单聊，即一对一单聊，可以标记不同用户身份，如客户和经理两种身份。
2、【基本功能】延迟提醒，即客户给经理发送消息后，经理在1分钟未回复，就提醒经理。尽量考虑后端支持分布式多点部署。
3、【基本功能】聊天内容，支持敏感词过滤，提示用户发送的内容是否包含敏感词。连续超过5次敏感词，用户当天不能发送消息，直到第二天。
4、【扩展功能】聊天控制，一个用户一天只能发送100条消息，发送消息后间隔3秒才能发送下一条，其中100和3可以配置。
5、【扩展功能】支持搜索，支持聊天文字信息的模糊匹配查询。
6、【扩展功能】支持群聊，即入群后，一个人发消息后，群中其它成员都可以收到消息

交付目标：
1、完成系统功能开发，并提供部署文档、进行演示
2、尽量满足系统设计功能点，越多越好。编程语言不限制，建议使用Java或Nodejs
3、可引用开源基础组件，但业务逻辑需自己实现
4、代码、文档需上传到github 上，工作日期间每天至少提交一次代码，周末不限
5、考察重点为后端实现，前端页面简单完成即可
6、课题时间：发布课题后的第二天开始，为期2周
