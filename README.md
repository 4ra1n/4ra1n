# 关于

我使用过的 id 有：4ra1n | n1ar4 | Qing Xu | emyiqing | rg | ra1lgun

我的博客：https://4ra1n.github.io/

前某乙方安全工程师，主要从事 web 应用安全研究和安全开发相关工作

Jar Analyzer

- 一个 `JAR` 包分析工具
- 完善美观的 `GUI` 支持（现代化 `Java GUI` 界面，可拖拽，明暗双主题，十种风格）
- 基础分析（支持 `Jar/War/Classes` 输入，支持多文件，支持嵌套 `FatJar`）
- 黑白名单配置（构建数据库和搜索功能都支持黑白名单过滤，支持精确类名和包名过滤）
- 反编译（内置 `Fernflower` 改进版本双击反编译，使用 `JavaParser` 精确定位方法位置）
- 方法调用关系搜索（构建方法调用关系数据库，可搜方法定义与方法引用，支持精确和模糊搜索）
- 方法调用链 `DFS` 算法分析（支持 **正向/反向** 调用链分析，基于 `DFS` 算法的深度调用链追踪）
- 字符串搜索（搜索 `LDC` 指令，支持模糊搜索和精确搜索，可定位具体方法，联动调用进行分析）
- `Java Web` 组件入口分析（`Java Servlet/Filter` 组件分析，`Spring` 入口信息一键分析）
- `CFG` 程序分析（方法内部控制流可视化，基本块划分与展示，异常处理流程分析）
- `JVM` 栈帧分析（局部变量表与操作数栈状态跟踪，运行时数据流静态分析）
- 自定义表达式搜索（基于 `SpEL` 的多种语法组合搜索，用于搜索漏洞 `Gadget` 等）
- 常见安全分析功能（支持简单的 `SCA` 分析，敏感信息泄漏分析，可能的 `gadget` 分析）
- 应急响应分析功能（一键提取序列化数据中的恶意 `class` 反编译，一键提取 `BCEL` 代码）
- 测试功能：不同于 `IDEA` 等工具的源码级调试，实现了字节码级别的单步动态调试（仅初步实现）

主要维护的开源项目：
- 一个 `jar` 文件批量分析工具 (引用搜索/漏洞审计/信息泄露检查/Spring分析/程序分析) [jar-analyzer](https://github.com/jar-analyzer/jar-analyzer)
- 一个 `class` 混淆工具 (方法名/字段名/参数名混淆/字符串AES加密/异或混淆/垃圾代码混淆) [class-obf](https://github.com/4ra1n/class-obf)
- 一个 `jar` 混淆工具 (支持以上混淆方式，针对 JAR 特殊处理，支持 SpringBoot 等) [jar-obfuscator](https://github.com/jar-analyzer/jar-obfuscator)

联系我：
- emyiqing@gmail.com
- ra1lgun@foxmail.com

Github 贡献统计
 
![](https://github-readme-stats.vercel.app/api?username=4ra1n&show_icons=true)
 
Github 常用编程语言统计
 
![](https://github-readme-stats.vercel.app/api/top-langs/?username=4ra1n&hide=html,css&layout=compact)
