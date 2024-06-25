# MT3000乾坤大挪移
### 仅面向已刷了iStoreOS的MT3000
使用usb3.0外接移动硬盘，将系统复制到移动硬盘，并设置从移动硬盘启动MT3000,从而解决容量焦虑问题

# 打开首页终端 或 ssh 连接到MT3000的iStoreOS系统
`ssh root@192.168.100.1`
## 在命令行粘贴如下命令
```bash
wget -O mt3000.sh https://cafe.cpolar.cn/wkdaily/istoreos-mt3000-script/raw/branch/master/mt3000.sh && chmod +x mt3000.sh && ./mt3000.sh

```
