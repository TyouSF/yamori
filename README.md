# Yamori

> `Yamori` 日文：やもり，本意为"守宫，壁虎"之意。

本项目主要基于 `python` 语言，而编写的轻量小巧的爬虫，最初动力源于：仅仅是想要快速保存花瓣网内我喜欢的图片。

** 本项目当前抓取规则只适用于解析花瓣网

# 环境要求

- 无论是 win 还是 mac 亦或者是 linux，都需要最基本的 python3 环境，暂不支持 python3 以下版本；
- 如果可以，最好安装有 git 环境，更方便的获取本项目代码以及最新更新；

# 运行

1. 拷贝本项目代码到本地：`git clone git@github.com:TyouSF/Yamori.git`
2. 网址链接获取：请手动从浏览器的地址栏中，进行拷贝地址链接，这样就得到了 'url'
3. 启动系统命令行工具，进入到拷贝下来的项目根据路 `.*/Yamori/` 下，执行命令：`python3 run.py 'url'`
4. 如果需要继续抓取下一页，可以根据命令行的提示，直接输入 'y' 来继续抓取下一页的图片
5. 结束程序也是如此简单，抓取完毕后，根据提示，输入 'n'，终止抓取

执行后，系统将自动抓取给定的网址（url）内的所有图片并加以保存，默认保存目录是本项目下的 `/Yamori/huabanimgs/` 下，并按照日期进行文件夹级的归类，形如：

```
Yamori
+--run.py
|   +--db/
|   +--yamori/
|   +--huabanimgs/
|       +--20180101/
|           +--01.jpg
|       +--20180102/
|           +--01.jpg
```
