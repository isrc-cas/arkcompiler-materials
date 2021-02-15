OpenArkCompiler Weekly - #45  January 10th 2021

社区动态：

1、方舟编译器社区计划在1月14日召开网络会议，讨论孵化器和主干版本的合并。
具体时间：2021-01-14 09:15-10:45((UTC+08:00)Beijing)
Zoom  Meeting ID: 235 387 707

主库Commits:

1、use "--retry 1" to smooth out abnormal testing behavior for now
https://gitee.com/openarkcompiler/OpenArkCompiler/commit/4e2076da418acb9d2900647f8c16d2c29ea739c0

2、add maple_util BUILD.gn
https://gitee.com/openarkcompiler/OpenArkCompiler/commit/fb95e68325d49bb9a4b00707f5164186921838b1

3、del maple deplibs,enable new source code build
https://gitee.com/openarkcompiler/OpenArkCompiler/commit/2b1e54446e0010c2424f7a14be67340419b90adb


孵化器Commits:

1、[mapleall]本周更新较多，可以查看Dev分支
https://gitee.com/openarkcompiler-incubator/mapleall/commits/dev

2、[MapleFE] 开始采用openjdk, ojluni里面的代码作为测试用例，当前已经完成A打头和B大头的文件；完成了type equivalent的实现，同时应用到function的ovrride equivalent的实现；开始启动从AST到Maple IR的转换。刚刚完成几个基本的脚本。

3、[maple_engine]merge LLDB exploratory and experimental extension into Maple Debugger 
https://gitee.com/openarkcompiler-incubator/maple_engine/commit/92a270749c0425d8ce07cc109f1844bd9f77b4d9