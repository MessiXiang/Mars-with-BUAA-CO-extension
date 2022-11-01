## 这是什么？

这是一个魔改版 Mars，专用于 BUAA 的计算机组成实验。

基于 [Mars 4.5 开发](http://courses.missouristate.edu/KenVollmar/MARS/)

## 与原版有什么不同？

它能够支持输出课程实验要求 CPU 输出的内容，因此能方便与自己的 CPU 进行测试/对拍。

## 如何使用？

目前是首个版本（0.1），新拓展的功能只支持在命令行使用。

目前在原版基础上新增命令行指令如下（在命令行界面输出 `java -jar Mars.jar h` 也能快速查看原版指令和新增指令的提示信息）（指令均不区分大小写）：

1. `coERR`：将本扩展打印的任何内容（扩展版本信息除外）打印到 `stderr` 而非默认的 `stdout`
2. `coL1`：打印寄存器修改或内存修改信息，与 `P4` 要求相同
3. `coL2`：打印额外信息，方便逐步查错和调试

## 注意事项

根据计组实验要求，建议搭配指令 `mc CompactDataAtZero` 使用

另外，若要禁用版本信息，请使用指令 `nc`

## 版权声明

请务必准守[原版 Mars 版权声明](http://courses.missouristate.edu/KenVollmar/MARS/license.htm)。

本拓展无版权声明，可以随意下载使用或修改，前提是声明出处，并保留源代码中的`版本信息`