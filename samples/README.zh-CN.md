# Apache Commons IO 示例

[English](README.md) | [简体中文](README.zh-CN.md)

[hello.norm](hello.norm) —— 写入、读取并删除 UTF-8 文件，同时读取文件扩展名。这是通过自身的 `Module module()` 声明依赖的独立消费者程序。

[compare-revisions.norm](compare-revisions.norm) 会写入报告和快照、比较内容、修改报告，然后读取未变的快照。程序退出前会删除这两个文件。两个示例都以独占方式创建文件；若同名文件已存在，程序会失败，且不会修改原文件。

在仓库根目录运行：

```sh
norm run samples/hello.norm
norm run samples/compare-revisions.norm
```

[module.norm](../commons/io/module.norm) 指定 Java 制品版本并定义公开 API。

入门示例输出：

```text
txt
Hello from Norm
```

比较示例输出：

```text
true
false
Norm release 1
```

API 入口：[module.norm](../commons/io/module.norm) 列出公开的 `FileUtils` 和 `FilenameUtils`。[适配器验收示例](../examples/sample/commons/io/Main.norm)覆盖更多绑定行为。
