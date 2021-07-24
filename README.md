# 爱学习的小菜鸡

> 用一种更加猴子的方式去归档整理工作学习中的文档资料
> 勿以善小而不为

gitpage实现：[https://pages.github.com/](https://pages.github.com/)

gitbook的gitpage实现：[http://www.chengweiyang.cn/gitbook/github-pages/README.html](http://www.chengweiyang.cn/gitbook/github-pages/README.html)

gitbook发布方式

``` shell
gitbook init
gitbook build
cp -r _book/* .
git add .
git commit -m "Publish book"
```
