# Apache Commons IO samples

[English](README.md) | [简体中文](README.zh-CN.md)

[hello.norm](hello.norm) — Write, read, and remove a UTF-8 file while inspecting a filename. This is a standalone consumer with its own `Module module()` dependency.

[compare-revisions.norm](compare-revisions.norm) writes a report and a snapshot, compares them, changes the report, and reads the unchanged snapshot. Both files are removed before the program exits. Both samples create their files exclusively and fail without changing an existing file of the same name.

From the repository root, run:

```sh
norm run samples/hello.norm
norm run samples/compare-revisions.norm
```

[module.norm](../commons/io/module.norm) pins the Java artifact and defines the public API.

The hello sample prints:

```text
txt
Hello from Norm
```

The comparison sample prints:

```text
true
false
Norm release 1
```

API reference: [module.norm](../commons/io/module.norm) lists the exposed `FileUtils` and `FilenameUtils`. The [adapter acceptance example](../examples/sample/commons/io/Main.norm) exercises additional binding behavior.
