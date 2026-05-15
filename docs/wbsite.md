# 网站搭建记录

> [!ABSTRACT]
> 记录一些搭建网站的过程


## 使用工具


### git&github

- git 管理仓库
- github page 创建网站

### mkdocs-material

[官方文档](https://squidfunk.github.io/mkdocs-material/)

比较喜欢这种清晰简介的风格，hexo类的网站我总感觉有点花，不太适合阅读

几位前辈也选择了这种方式，在搭的过程中也参考了许多

[咸鱼暄](https://xuan-insr.github.io/)

[Slowist](https://note.slowist.top/)


## 过程

其实过程还算比较简单吧，Github Action 把活都干了（

### 虚拟环境

codex 在初始化仓库的时候用了一个 Python 的虚拟环境

```powershell
python -m venv .venv

.\.venv\Scripts\Activate.ps1
```

似乎可以避免一些环境冲突，等我补完python的课应该就知道咋回事了

