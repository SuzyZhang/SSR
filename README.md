**这是一个 SSR 服务器端的脚本 + 更换内核脚本 + 锐速破解版安装脚本**

使用 Xsheell 成功连接 VPS 后，依次运行

```
yum -y install wget
wget -N –no-check-certificate https://raw.githubusercontent.com/SuzyZhang/SSR/master/ssr.sh && chmod +x ssr.sh && bash ssr.sh
```
> 仅 Vultr 需要先执行更换内核脚本
```
wget -N --no-check-certificate https://github.com/SuzyZhang/SSR/blob/master/ruisu.sh && bash ruisu.sh
```

```
wget -N --no-check-certificate https://raw.githubusercontent.com/SuzyZhang/SSR/master/serverspeeder.sh && bash serverspeeder.sh
```


