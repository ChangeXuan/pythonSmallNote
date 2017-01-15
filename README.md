# pythonSmallNote

- 移位操作:二进制左移<<,二进制右移>>
- 因为在二进制的表示当中，最低位为1，则对应的十进制数一定为基数，所以想通过移位操作来让所有的数字都变为偶数，可以这样做 xx>>1<<1
- 遇到编码问题，可以尝试在头部添加
```
import sys
reload(sys)
sys.setdefaultencoding('xxx')//xxx = gbk | gb2312 |utf-8
```

- python使用bin()转换成二进制后会在二进制的前边添加'0b'
