#source:https://github.com/skydark/nstools/tree/master/zhtools

#how to use

from langconv import *

# traditional->simplified
line = Converter('zh-hans').convert(line.decode('utf-8'))
line = line.encode('utf-8')


# simplified->traditional
line = Converter('zh-hant').convert(line.decode('utf-8'))
line = line.encode('utf-8')