## 获取评分的不同方式（主要学习下BeautifulSoup）

scout = soup.select(".rating_right")[0].parent

scout = soup.find_all("strong")[0].get_text()

scout = soup.find_all(class_="ll rating_num")

scout = soup.select("strong[class='ll rating_num']")

scout = soup.find_all(attrs={"class": "ll rating_num"})[0].get_text()

scout = soup.select(".ll.rating_num")[0].get_text()

### 其他都是些基本操作

set_style()函数在定义excel的样式。

#### 链接分了两种方式获取

* 一种是按分页获取，一页25条
* 一种是每次取第一条，循环250次

### 豆瓣会封IP，可以建立IP池解决
