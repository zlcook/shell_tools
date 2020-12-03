# shell_tools
shell脚本工具集

# ts_dmesg
* 查询dmesg命令的输出信息，将前面的时间秒数转换成日期格式
```
# 使用案例，查看系统因为内存不足kill掉的进程
[xxx@xxx ~]$ ./ts_dmesg.sh | grep "Out"
[2020/11/25 23:34:12] [27326925.857823] Out of memory: Kill process 151096 (anyid) score 988 or sacrifice child
[2020/11/26 11:01:23] [27368156.701624] Out of memory: Kill process 141215 (anyid) score 988 or sacrifice child
[2020/12/02 18:17:46] [27912739.983127] Out of memory: Kill process 27983 (anyid) score 988 or sacrifice child

```
