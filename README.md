
# sktrace
https://bbs.pediy.com/thread-264680.htm

## 功能
1. 类似 ida 指令 trace 功能
2. 统计寄存器变化，辅助分析，并且可能会有字符串产生，

## todo
1. arm32。
2. 改为 C 实现


## ios
python3 sktrace.py -m attach -l Omi -i 0x100867264  sg.omi.chat


python3 sktrace.py -m spawn -l Omi -i 0x00867264  sg.omi.chat

## android
 python3 sktrace.py -m attach -l libt.so -i getroot  DEMO-420