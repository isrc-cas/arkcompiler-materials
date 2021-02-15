OpenArkCompiler Weekly - #48  January 31st 2021

社区动态：

1、本周四（28日）方舟编译器社区计划召开会议，讨论孵化器merge主干的进度。
会议纪要：https://gitee.com/openarkcompiler/OpenArkCompiler/issues/I2SC8R

2、孵化器merge主干的PR列表：https://gitee.com/openarkcompiler/OpenArkCompiler/issues/I2D6RV

主库Commits:

1、fix a bug in getting func signature string, which also assert debug testing
https://gitee.com/openarkcompiler/OpenArkCompiler/commit/4567444dc742c3676ecb5dd0bebf564adf6ac2db

2、opensource remaining mir_node sourcecode
https://gitee.com/openarkcompiler/OpenArkCompiler/commit/1c761025a67b5bb8a012488b7c2173c553ca1724

孵化器Commits:

1、[mapleall]add API
https://gitee.com/openarkcompiler-incubator/mapleall/commit/93d628f92aa373d09be9c98b4ddf81a66c808331

2、[mapleallSelectIread must handle struct of both top and component levels
https://gitee.com/openarkcompiler-incubator/mapleall/commit/757b717c9ad883bfb5917f06fb11288f39b47950

3、[MapleFE] 本周工作分别在两个部分：parsing和ast2mpl。parsing部分重点在于分析alternative tokens的问题，以及解决方案设计。目前已经在autogen里面完成部分实现。ast2mpl部分重点在于一些基础IR结构的完善，包括field, unary operator的完善，以及一些问题的修复。目前已经能够生成简单的class, function，以及数据结构。

4、[maple_engine]本周没有更新