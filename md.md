# Markdown介绍
**Markdown** 是一种文本格式。你可以用它来控制文档的显示。使用 markdown，你可以创建粗体的文字，斜体的文字，添加图片，并且创建列表 等等。基本上来讲，Markdown 就是普通的文字加上 # 或者 * 等符号。

使用文档请参考：https://www.bookstack.cn/read/mpe/zh-cn-markdown-basics.md

# 关于Github上在Markdown里支持LaTeX数学公式
Github用的是[*GitHub Flavored Markdown*](https://github.github.com/gfm/)来进行渲染，和Markdown原生一样默认不支持LaTeX数学公式。不过可以通过[*CodeCogs在线服务*](http://latex.codecogs.com/)来支持，具体方式有2种。
### 1、手工写公式
比如这样：`![](http://latex.codecogs.com/gif.latex?\\frac{1}{1+sin(x)})`，但是这种方式在VSCode等工具中会出现预览问题，但在Github上能正常显示动态生成图片之后的公式。
### 2、通过[*Markdown Preview Enhanced*](https://shd101wyy.github.io/markdown-preview-enhanced/)的Atom或者VSCode扩展来生成
以VSCode举例具体步骤为，通过*Markdown Preview Enhanced*来预览md文件(ctrl+shift+v)，然后点击File再点击另存为新的md文件，会被自动转换成用CodeCogs里的图片服务来实时生成公式。