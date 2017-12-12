# hosts 说明
hosts for GitHub, VSTS , Microsoft Docs And Others

## 修改步骤：

### 下载 hosts

- 找到hosts所在文件夹

系统|hosts文件位置
---|---
Windows|C:\Windows\System32\drivers\etc\
Android|/etc/
Mac|/etc/
iPhone（iOS）|/etc/
Linux|/etc/
Unix|/etc/

- 将下载的 hosts 覆盖到文件夹中
- 如有需要，请备份原来的hosts

### 让hosts生效

- Windows

    开始 -> 运行 -> 输入cmd -> 在CMD窗口输入  ： ipconfig /flushdns
    
- Linux

    终端输入 ：  sudo rcnscd restart

- Mac OS X

    终端输入 ：  sudo killall -HUP mDNSResponder

- 其他
    
    断网，再开网；

- 终极方法

    重启机器；
