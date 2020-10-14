# windows cmd&powershell命令大全
---
#### 测试环境：win10企业版1909
1.无法启用移动热点（执行完需要重启）
```
netsh winsock reset
```
2.查看文件的哈希值(MD2, MD5, MD5, SHA1[缺省默认], SHA256, SHA384, SHA512)

```
certutil -hashfile filepath md5
```
3.文件转码为base64
```
certutil -encode sourcefilepath targetfilepath
```
4.解码base64文件
```
certutil -decode base64file targetfilepath
```
