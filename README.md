# moyi
基于[landscape-plus](https://github.com/xiangming/landscape-plus "") v1.0.3的hexo主题

## 所有新特性
###自己添加的
+ 将CDN改用国内的了
+ 添加**toTop**功能模块
+ 添加**mathjax**的模块开关,不需要的可以自己关闭。（因为加载略耗时间）
+ 修正**文章评论**，**阅读更多**，**上一篇下一篇**，**上一页下一页**的显示国际化

###landscape-plus v1.0.3已经存在的
+ 根据国情，**去掉Google的库**，改用cloudflare的cdn，打开页面不再卡住了。=> [参与国内cdn的讨论](https://github.com/xiangming/landscape-plus/issues/3)
+ 增加了 **语言包** 。（支持英文、中文简体和中文繁体。）
+ 代码高亮，**采用Monokai**，熟悉SublimeText的朋友一定不陌生。
+ 增加了 **友情链接** widget。（已默认开启。）
+ 不使用header里面的大图，节省带宽，页面加载更快。（大图文件还在，恢复方法看下面的。）
+ 修改了原主题的 **配色** 和部分markdown样式（blockquote/code...）
+ 集成 **多说评论模块** 。（开启方法看下面的。）
+ 集成 **百度分享模块** 。（已默认开启，详情看下面的。）
+ 增加对 **IE8** 的支持。
+ 集成 **mathjax**，即latex数学公式的支持。（感谢 @Svtter 的[pull request](https://github.com/xiangming/landscape-plus/pull/35)）


## 文档目录

+ [演示](#演示)
+ [安装](#安装)
+ [启用](#启用)
+ [更新](#更新)

## <a name='演示'>演示</a>

你可以点击[这里](http://myqianlan.com)，查看演示。

## <a name='安装'>安装</a>

``` bash
    $ git clone https://github.com/myqianlan/hexo-theme-moyi.git themes/moyi
```
**Landscape plus 需要 Hexo 2.7 及以上版本.**

## <a name='启用'>启用</a>

修改主题的设置文件`_config.yml`，把`theme`的值设置为`moyi`

## <a name='更新'>更新</a>

``` bash
    cd themes/moyi
    git pull
```






