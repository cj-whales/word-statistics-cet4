# vb_python of cet-4
## 程序介绍  
这是一个单词频率统计程序 基于python3
- 自动批量收集文件中的英语单词 txt (utf-8)
- 统计排序保存到本地数据库voca.db
- 翻译英文得到中文解释
- 数据库文件提取得到csv表格EXCEL  

在结合到大量的往年cet-4真题库的情况下  
- 本软件成为了考试必备词库
- 希望大家都能轻松过四级
## 工作流程  
1. settings配置  
2. work自动分析数据保存至voca.db数据库文件  
3. translate自动打开数据库调用api翻译单词并保存到数据库里
4. db2csv将数据库文件转换成csv表格文件  
- `python work.py`
- `python translate.py`
- `python db2csv.py`  
## todo
- 六级真题词库分析
- 软件模块化
## 自我要求
- 更深刻的了解数据库 和 peewee
- python的yield
- 对象！对象！
- setting作为配置引入
