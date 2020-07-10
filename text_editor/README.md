# 文本编辑器概览

知识点

+ 标准输入输出STDIN_FILENO、STDOUT_FILENO <unistd.h>
+ 终端设置 tcgetattr、tcsetattr | c_iflag、c_oflag、c_cflag <termios.h>
+ escape sequence（\x1b[ ）, 做很多文本格式的工作，比如上色、移动光标、清除屏幕的部分内容， J清除屏幕，H移动光标，C移动光标到右边



文本编辑器属性

+ 光标<当前位置>

+ 窗口<显示>

+ 文本<多行文字>



文本编辑器方法

+ 光标移动（上下左右，滚动）
+ 文本显示，文本换行
+ 插入文本
+ 删除文本
+ 文本换行
+ 保存
+ 退出




