# 23考研数据爬取-可视化大屏-动态页面

### 介绍：
基于 python3.9 + flask + echarts 的23考研数据爬取与可视化大屏展示

### 目的：

针对23年研招网收录的招生单位、院系所、专业、研究方向、考试方式、考试科目、招录人数、指导老师、备注等信息进行爬取、清洗和可视化分析。

### 准备：

#### 1.找到想要爬取的网站（[https://yz.chsi.com.cn/zsml/queryAction.do](https://yz.chsi.com.cn/zsml/queryAction.do)）

![](https://foruda.gitee.com/images/1686895756236725046/b34ebfe8_10238196.png "屏幕截图")

#### 2.分析网站的HTML结构，以及规划想要爬取的信息

![](https://foruda.gitee.com/images/1686895888033267540/14ea513a_10238196.png "屏幕截图")

![](https://foruda.gitee.com/images/1686895905020139099/d4a9e10f_10238196.png "屏幕截图")

### 搭建/运行

#### 1. 环境

Python3.9+各种库

#### 2. 数据爬取

使用的是 selenium4.2.0 版本的API，可降版本或者改方法/参数

#### 3. 数据分析+可视化大屏

- 可视化大屏

运行：

- 运行app.py:

![](https://foruda.gitee.com/images/1686896228427443176/f3d0df92_10238196.png "屏幕截图")

- 以浏览器的方式打开index.html:

![](https://foruda.gitee.com/images/1686896317126547344/43fcebcd_10238196.png "屏幕截图")

结果【如果网页显示发生错误，先确保app.py在运行，然后重新打开html】：

![](https://foruda.gitee.com/images/1686896781326119848/ac7ea25f_10238196.png "屏幕截图")

#### 4. 单个模块可视化

- 词云

运行该py文件：

![](https://foruda.gitee.com/images/1686896852310454174/e8b2e39e_10238196.png "屏幕截图")

结果：

![](https://foruda.gitee.com/images/1686896865672427369/5f3c1a8e_10238196.png "屏幕截图")

- 英语和数学柱状图

运行：

![](https://foruda.gitee.com/images/1686897101520244343/a9ec22e2_10238196.png "屏幕截图")

结果：

![](https://foruda.gitee.com/images/1686897126719783342/ebfe4e92_10238196.png "屏幕截图")

- 人数分布饼状图

运行：

![](https://foruda.gitee.com/images/1686896896990566193/4be7cde0_10238196.png "屏幕截图")

结果：

![](https://foruda.gitee.com/images/1686897039352402464/1b2edd45_10238196.png "屏幕截图")

- 4. 院校数柱状图

运行：

![](https://foruda.gitee.com/images/1686896923987555563/dcc769a9_10238196.png "屏幕截图")

结果：

![](https://foruda.gitee.com/images/1686896941997665335/b21fcd15_10238196.png "屏幕截图")

- 地图

运行生成**地图.html**，不要运行html，这是一个根据数据生成的html，直接在用浏览器打开即可：

![](https://foruda.gitee.com/images/1686896953597857348/74f5c0a7_10238196.png "屏幕截图")

结果：

![](https://github.com/Mingdaj/bigData/assets/130920375/0711d566-8907-4dbe-ae20-511f2fb81d2e)

天下没有免费的午餐，前后端代码+部署调试搞活动，详情加QQ咨询。前10名购买半价，另外有一些学习问题也可以一起交流，买到就是赚到！

QQ：2790810983

助理QQ：3539048933
