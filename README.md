# 图床

采用jsDelivr+github搭建的免费cdn。

调用地址为:
https://cdn.jsdelivr.net/gh/wxyww2049/cdn@版本号/文件路径

如:https://cdn.jsdelivr.net/gh/wxyww2049/cdn@now/img/1.png

不发布也可直接使用
调用地址为
https://cdn.jsdelivr.net/gh/wxyww2049/cdn/文件路径
其他仓库类似（修改后面的"cdn"为仓库名）

# 发布

利用Travis CI进行自动发布。

# 图床

图床展示:[https://img.wxyww.top](https://img.wxyww.top)

# 更新版本号

Travis CI会自动增加版本号。

修改之前版本可以先删除标签
> git push origin :refs/tags/标签名

然后发布新标签
> git push origin 标签名
