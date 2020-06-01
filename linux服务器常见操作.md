## 1. scp
    windows上传文件到linux服务器：
    scp e:\scpdata\1.txt root@10.1.22.5:/home/

    Windows得到Linux服务器的文件（将上面操作反过来）：
    scp -r root@10.1.22.5:/home/ ./
    (./指代当前执行scp机器的当前目录)
## 2. ls
    查看文件大小：ls -lh
