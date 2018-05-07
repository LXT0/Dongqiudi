# Dongqiudi

这是对"懂球帝"App的数据爬虫与分析。

----

### 1. 数据准备

将所有数据存储在 sqlite3 中。

数据包括：

1. 球队信息列表。

- 共 **144** 个球队，存储在 team 表。

2. 近期的文章列表。

- 一共提取了最近 20 页的 **2000** 篇文章。

3. 用户id列表。

- 2000 篇文章下的 **249685** 个评论用户(未去重)，存储在 article_comment_user 表。

4. 用户信息。

- 去重后共 **103300** 个用户，存储在 user 表。

5. 评论内容。

- todo

----

### 2. 数据分析结果

1. There are 51828 male users, 3292 female users, and 48180 users gender unknown.

2. Top 10 Region:

|   Region   | Count |
|:----------:| :---: |
|  广东 广州  |  2089 |
|  四川 成都  |  1735 |
|  海外 其他  |  1602 |
|  陕西 西安  |  1369 |
|  江苏 南京  |  1310 |
| 北京 东城区 |  1265 |
|  辽宁 大连  |  1100 |
|  山东 济南  |  1090 |
|  广东 深圳  |  1017 |
| 海外 西班牙 |  1002 |

3. Top 10 team:

|    Team    | Count |
| :----------: |  :---:  |
|  巴塞罗那  |  17104 |
|  皇家马德里  |  16575 |
|  曼联  |  6278 |
|  拜仁慕尼黑  |  6106 |
|  利物浦  |  3779 |
| 中国 |  3646 |
|  阿森纳  |  3644 |
|  AC米兰  |  3540 |
|  广州恒大淘宝  |  3031 |
| 国际米兰 |  2797 |

----

### 3. 数据可视化

To do.

使用 d3.js / E-Charts .




