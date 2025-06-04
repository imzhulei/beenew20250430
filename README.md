Github部署

1. 新建github仓库:把BPB panel项目代码同步到仓库。

2. 配置github Actions: 在仓库目录下创建.github/workflows文件夹，并创建upbpb.yml文件。2025.4.25更新可使用！

可随官方自动更新的工作流，可在CF上部署：

代码参考上述路径

#

Cloudflare 部署

•创建pages：点击workers和pages，选择pages部署。连接github仓库，选择新建的项目仓库，然后点击部署。

•绑定自定义域名：以防止page分配的域名被屏蔽。

•设置变量：UUID，PROXY_IP, TR_PASS

•绑定KV命名空间：名称随便但不能含有bpb等敏感词

•重试部署pages

##

BPB面板设置
•部署成功后，打开浏览器输入:https://[自定义域名]或者你的项目地址,后面加上/panel检查是否能正常访问BPB面板.

•修改BPB面板密码

•配置BPB面板参数

常用IP获取方式
cleanIP/优选IP：

地址1：https://www.wetest.vip/page/cloudflare/address_v4.html  

地址2：https://ipdb.030101.xyz/bestcf/ 

地址3：https://stock.hostmonit.com/CloudFlareYes

地址4：https://mrxn.net/BESTCFDOMAIN


PROXYIP：

点击进入1：https://ipdb.030101.xyz/bestproxy/

点击进入2：https://www.nslookup.io/domains/bpb.yousef.isegaro.com/dns-records/


节点测试
在V2rayN上使用演示
