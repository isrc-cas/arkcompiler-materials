OpenArkCompiler Weekly - #15 Jun 14th 2020

社区动态：

本周社区风平浪静，未召开会议。

Commits:

1、[me]bugfix:Pi Excute before current check

https://gitee.com/harmonyos/OpenArkCompiler/commit/ede97ee3255df21fc61a2db1e561255a80dab9b5

2、添加名为Annotation Analysis的module phase：

https://gitee.com/harmonyos/OpenArkCompiler/commit/3a04e917d829252f9f13d20cd8c9f7b37f5c0942

点评：需要注意的是，添加新的phase之后，并没有按照phase文档描述的注册phase的流程去修改phases.def。

3、修复：【测试框架】当DEPENDENCE的文件不存在，多线程跑的时候会卡主

https://gitee.com/harmonyos/OpenArkCompiler/commit/f143e4fe248f111064f6bc7d29b6e96385dd483c