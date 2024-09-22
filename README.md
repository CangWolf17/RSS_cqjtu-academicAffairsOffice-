# RSS_cqjtu_academicAffairsOffice

基于rssEverything的重庆交通大学教务处RSS订阅源规则



## Feed URL

```
https://rsseverything.com/zh/feed/cb50f5f0-cd0f-482c-a868-e83ebc51d4f3.xml
```



## 教务处地址

```
http://jw.cqjtu.edu.cn/jxxx/tzgg1.htm
```

[跳转](http://jw.cqjtu.edu.cn/jxxx/tzgg1.htm)



## 匹配规则

```
<DT id="{*}"><A title="" href="../{%}"><SPAN class="contitle">{%}</SPAN> <SPAN class="contime">{%}</SPAN></A></DT>
```



## 订阅模板

```
#标题
{%2}
#链接
http://jw.cqjtu.edu.cn/{%1}
#内容
时间：{%3}
```



仅作留存备份和学习用
