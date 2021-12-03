makefile学习文档

在讲述这个makefile之前，还是让我们先来粗略地看一看makefile的规则。

```bash
target ... : prerequisites ...
    command
    ...
    ...
```

- target

  可以是一个object file（目标文件），也可以是一个执行文件，还可以是一个标签（label）。对于标签这种特性，在后续的“伪目标”章节中会有叙述。

- prerequisites

  生成该target所依赖的文件和/或target

- command

  该target要执行的命令（任意的shell命令）