# POC-EXP
本脚本针对CVE-2019-2725weblogic 反序列化RCE漏洞，使用前请修改VPS监听地址，并在运行时提交特定的URL即可完成测试
测试地址为：http://192.168.209.134:49163/_async/AsyncResponseService
修改payload参数中的监听地址和端口后：
#python CVE-2019-2725.py 运行后输入http://ip:端口号/_async/AsyncResponseService
