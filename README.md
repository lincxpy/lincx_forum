# lincx_forum
这是一个由vue.js做前端语言，golang,java,python做后端的小型论坛

主要功能：
1、基本注册、登录功能，后端使用java实现，使用了springboot+mybatis，利用token保存登录信息
2、个人资料编辑、编辑发布blog、话题，设置话题的主题、分类、评论、点赞功能，这部分使用golang实现，使用了gin+gorm框架
3、话题检索功能，后端使用python实现，使用到了flask框架，还用到了jieba分词，数据库索引等。
4、项目使用docker打包部署到服务器，利用k8s进行容器编排
5、前端用到vue.js+elementui等实现
6、使用nginx容器部署前端项目

项目亮点：
1、论坛功能基本实现，用到不同语言进行后台的编写
2、使用docker进行项目部署，利用k8s容器编排让容器管理方便简单

项目难点：
1、工程量较大，不同语言之间的数据交流比较困难
2、在处理点赞，评论这些功能上边还有待提升

