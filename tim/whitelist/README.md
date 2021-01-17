# TIM 白名单

不允许访问 C:\Users 和其他所有盘符，但开放以下文件夹：

```C:\ProgramData\Tencent\*
C:\Users\*\AppData\Local\Tencent\*
C:\Users\*\AppData\LocalLow\TENCENT\*
C:\Users\*\AppData\Roaming\Tencent\*
C:\Users\*\Documents\Tencent\*
C:\Users\*\Documents\Tencent Files\*
C:\Users\*\AppData\LocalLow\Microsoft\CryptnetUrlCache\*
C:\Users\*\AppData\Roaming\Microsoft\Crypto\*
C:\Users\*\AppData\Local\Microsoft\Windows\Caches\*
C:\Windows\Temp\*
C:\Users\*\AppData\Local\Temp\*
C:\Users\*\AppData\LocalLow\Temp\*
```

如有其他目录需要读写，可直接修改`自定义处理.json`，或导入后在软件内添加规则。