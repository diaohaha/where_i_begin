where_i_begin
=============


1. baidutieba.py
-----------------------------
  实现功能：
  
  	python 简单爬虫,从百度贴吧爬取峨眉山的所有的帖子以及回复，包括标题，姓名，id，回复时间，回复内容。并存入数据库。
 
  包含:
  
  	使用python自带的SGMLParser进行网页解析。数据库用mongodb。
  问题:
  
    不能更新，单线程，id回复对应不一致。未保存图片。

2.phonebook_sqlite3.py
----------------------
  实现功能：
  
    存储通讯录信息，实现基本的增删改查（考虑数据库的连接）。
  
3.serach
--------
  实现功能：
  
    将从百度贴吧里爬下来的数据，从数据库导出json文件，并对文件用xapian建立索引。并且提供查询接口。使用tornado python web
  
  框架，建立查询页面。  
