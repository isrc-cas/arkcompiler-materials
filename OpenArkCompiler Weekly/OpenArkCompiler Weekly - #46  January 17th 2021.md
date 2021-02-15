OpenArkCompiler Weekly - #46  January 17th 2021

社区动态：

1、本周（14日）方舟编译器社区召开了社区会议，讨论了方舟编译器主干和孵化器版本的合并问题。
会议纪要：
社区版本https://gitee.com/openarkcompiler/OpenArkCompiler/issues/I2D9T9
小乖他爹个人版本https://zhuanlan.zhihu.com/p/344175169

主库Commits:

1、prepare to support multiple platforms
https://gitee.com/openarkcompiler/OpenArkCompiler/commit/83b8169f57a97709a52f67579c0935308744c7eb

孵化器Commits:

1、[mapleall]本周更新较多，可以查看Dev分支
https://gitee.com/openarkcompiler-incubator/mapleall/commits/dev

2、[MapleFE] 在BuildAST的时候做了数据结构的改进，将构造的时间降低为O(n)；增加了Java语法的支持。以及修正了lexer的一个bug；完成了UniCode的parsing支持；开始构建生成maple IR的模块，即ast2mpl，目前刚搭建了基本框架。

3、[maple_engine]Fixes the issue of OP_sext and OP_zext with expr.param.extractbits.bsize > 63
https://gitee.com/openarkcompiler-incubator/maple_engine/commit/8238fba29d070081c806d0edd5beb0fcd4fe51f3