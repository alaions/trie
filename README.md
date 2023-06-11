# Trie

#### 介绍
Java实现前缀树（字典树），实现搜索与敏感词过滤

可应用与web的搜索与敏感词过滤

使用步骤

```
`insert（）插入，构建前缀树`
insertPlus（）插入，增加拼音识别（一些特殊符号可能会报错）

search（）查询特定词语是否存在
searchList（）查询符合前缀的所有词语
searchListPlus（）增加拼音查询

searchWord（）查询一段文字中是否含有特定词（敏感词检测）
```
