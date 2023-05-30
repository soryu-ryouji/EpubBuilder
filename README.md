﻿# Epub Builder CLI

通过命令行创建Epub电子书

## Command Line Parameter

-m / --markdown : markdown 文件路径

-c / --cover : cover 文件路径

-b / buildpath : epub 文件生成路径

-d / debug : 开启debug模式，会输出程序运行的信息

```shell
# Example in Windows
eb -m D:/markdown.md -b D:/BuildBook -c D:/cover.jpg -d
```

## Docs

[程序执行流程](./Docs/程序执行流程.md)

[Epub电子书格式](./Docs/Epub电子书格式.md)

## Todo List

- [x] 多级目录的实现
- [ ] 添加子标签目录跳转支持
- [ ] markdown文本渲染
- [ ] markdown图像文件插入

## LICENSE

![MIT](./Docs/Images/MIT.png)

Epub is released under the MIT