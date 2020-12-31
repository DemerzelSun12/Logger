# Logger


一个轻量级的，可以同时输出到控制台和日志的python的Logger，自己记性不好，先记录着，防止以后忘。

Logger.py放到相应位置，`import`之后，待运行文件加如下两句

```python
sys.stdout = Logger(sys.stdout) # 打印正常的输出
sys.stderr = Logger(sys.stderr) # 打印错误信息
```