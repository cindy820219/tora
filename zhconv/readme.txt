#source£ºhttps://github.com/skydark/nstools/tree/master/zhtools

#how to use

from langconv import *

# ·±¡ú¼ò
line = Converter('zh-hans').convert(line.decode('utf-8'))
line = line.encode('utf-8')


# ¼ò¡ú·±
line = Converter('zh-hant').convert(line.decode('utf-8'))
line = line.encode('utf-8')