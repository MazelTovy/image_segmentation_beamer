# Kokura-Beamer：一个极简主义的毕业答辩Beamer模板

灵感来自于[这里](https://github.com/thomas10011/WHU-Beamer)，但是我个人感觉那个模板有点过于花哨，所以我按照自己本科答辩PPT的风格写了这个模板。

该模板主要用于组会、报告、答辩等场景，代码中给出的例子是武汉大学，但是也可以根据自己的需求更换学校logo。

## 相较于PPT，Beamer模板有哪些优势？

1. 代码化，更加方便修改
2. 不需要使用Office软件，可以在Linux下使用
3. 使用者只需要关注内容，不需要关注排版，从PPT操作上解放出来

## 模板页面展示

## 使用方法

### 环境配置

首先需要安装latex环境，推荐使用texlive，具体安装方法可以参考[这里](https://www.tug.org/texlive/doc/texlive-zh-cn/texlive-zh-cn.pdf)。

如果已经是texlive用户，直接clone本项目，将相关部分内容修改为自己的内容即可。

### 编译

当完成了讲义修改之后，需要使用xelaTeX编译（其他引擎有待验证）。不少latex编辑器原生支持xelaTeX编译，例如TexStudio，如果使用的是命令行，可以使用如下命令进行编译：

```bash
xelatex main.tex
```

### 本项目的文件夹结构说明