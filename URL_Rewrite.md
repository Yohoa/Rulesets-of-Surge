# Useful `URL Rewrite` script 


1. 【Safari多搜索引擎】在Safari搜索框里输入"df+<想查询的单词>"，自动导向Merriam Webster查单词。
```bash
^https:\/\/www\.google\.com\/search\?q=df\+(.*)&ie.*$ https://www.merriam-webster.com/dictionary/$1 header
```
