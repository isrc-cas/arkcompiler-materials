OpenArkCompiler Weekly - #40 December 6th 2020

社区动态：

本周方舟编译器社区较为活跃，是近几个月最活跃的一周。

1、方舟编译器主库版本开源了大家期盼已久的运行时。

2、12月4日上午 09:15-11:15，方舟编译器社区举行了社区会议。我个人因为和其他会议冲突，没能参加。会议情况等待官方的会议纪要。

3、史宁宁在12月4日的PLCT实验室2020年开放日做了报告《方舟编译器与Android Runtime》，演讲PPT：https://github.com/isrc-cas/PLCT-OpenDay-2020。会议有视频录制，后续会公开。

主库Commits:

1、add compiler-rt
https://gitee.com/openarkcompiler/OpenArkCompiler/commit/5674f6087a2dbe158b6d9f2ecff869af63ab9aa9

2、add mrt dep
https://gitee.com/openarkcompiler/OpenArkCompiler/commit/84749b057e8074249c5204b9806cfa6edce95547

3、add maple runtime
https://gitee.com/openarkcompiler/OpenArkCompiler/commit/8f3005589ebf683cc2a3b61b1cfe42c58a29cc93

孵化器Commits:

1、[mapleall]riscv64 fix register spilling bug with large stack size
https://gitee.com/openarkcompiler-incubator/mapleall/commit/2e583f9cfbbb2ca1ebb4f570015350d309e855e6

2、[MapleFE] Polished container SmallList to reuse LocateValue().
https://gitee.com/openarkcompiler-incubator/MapleFE/commit/3c2549189e7a0a1b4319f5ce6871ff9b5ced27ad

3、[maple_engine]正常bug修复。