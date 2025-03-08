# dify-on-wechat-portainer-compose
dify-on-wechat 一键部署【无忧版】

环境：
docker
portainer

```shell
mkdir dify-on-wechat
cd dify-on-wechat
mkdir -p gewechat/data 这里要建一个目录做gewe的数据保存路径
```

可能docker-compose就可以，我没试过。
我所有的docker都是用portainer中文版管理的。

进入“堆栈”--“编辑器”
把.yml文件的内容复制进去。
给堆栈起个响亮的名字
编辑窗口下方
“更新堆栈”
服务拉起来后，到“网络”里，找到堆栈被分配到的IP
![image](https://github.com/user-attachments/assets/e403e07e-b5d6-4265-b205-0cfa13a83fc8)
再回到堆栈编辑器，把IP替换，再更新堆栈，服务就拉起来了。
起动后
点![image](https://github.com/user-attachments/assets/ac9245ea-4451-4a61-b22f-13407c58a51e)
查看日志，找到二维码扫码登陆

好了，可以愉快的玩耍了！~

