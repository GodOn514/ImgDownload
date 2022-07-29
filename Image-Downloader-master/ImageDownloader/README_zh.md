# 融合两个主流爬取软件，修正报错

# 安装

## 下载并安装python3.6+

+ [下载地址](https://www.python.org/downloads/)

## 下载chromedriver并配置[推荐]

+ [下载地址](https://chromedriver.chromium.org/downloads)
+ 选择对应系统、chrome浏览器的版本
+ 下载完成后将`chromedriver`拷贝到 "本项目文件夹/bin/"，或者其他文件夹后添加到PATH中

## 下载phantomjs并配置[过时]

+ [下载地址](https://bitbucket.org/ariya/phantomjs/downloads)
+ 选择最新的windows版本下载即可
+ 下载完成后将phantomjs.exe拷贝到 "本项目文件夹/bin/"，或者其他文件夹后添加到PATH中

## 安装相关python库

```bash
pip3 install -r requirements.txt
```

# 如何使用
运行`image_downloader_gui.py`脚本以启动GUI界面
```bash
python image_downloader_gui.py
```
