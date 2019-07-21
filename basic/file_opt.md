## read file
+ with open(file,'r') as fd:
+ readline和readlines的主要区别：
+ readline只读入一行数据，readlines将整个文件读入，并存为list格式，故不能使用strip()去除换行符
