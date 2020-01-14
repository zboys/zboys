Trojan➕clash 实现订阅服务

[zboys]

Trojan
建议使用centos 7 bbr

yum -y install wget   先执行这个

Trojan1.13

curl -O https://raw.githubusercontent.com/atrandys/trojan/master/trojan_centos7.sh && chmod +x trojan_centos7.sh && ./trojan_centos7.sh

Trojan1.14

curl -O https://raw.githubusercontent.com/atrandys/trojan/master/trojan_mult.sh && chmod +x trojan_mult.sh && ./trojan_mult.sh/atrandys/trojan/master/trojan_mult.sh && chmod +x trojan_mult.sh && ./trojan_mult.sh

ss与ssr
ss
wget -N –no-check-certificate https://raw.githubusercontent.com/ToyoDAdoubiBackup/doubi/master/ss-go.sh && chmod +x ss-go.sh && bash ss-go.sh

ssr
wget -N –no-check-certificate https://raw.githubusercontent.com/ToyoDAdoubiBackup/doubi/master/ssr.sh && chmod +x ssr.sh && bash ssr.sh

准备工作与说明
在此需要说明几点！centos 7 bbr(本人用搬瓦工)是自带加速的，只需要把系统自带加速开启就可以了！

bbr

wget –no-check-certificate https://raw.githubusercontent.com/cx9208/Linux-NetSpeed/master/tcp.sh && chmod +x tcp.sh && ./tcp.sh

先申请好自己的域名

https://my.freenom.com
解析自己的域名

https://dash.cloudflare.com/
安装Trojan 安装好后我们继续安装ss

安装完Trojan和ss这一步就做完了！

clash

称为小猫咪

clash获取订阅网址(获取订阅时选择获取ssr)

https://sebs.club/user/node
clash脚本下载

https://drive.google.com/drive/folders/1FKPx3ki5l5oyaWuf5qfCCxYtb8YE9DqJ

用clash本地脚本修改好后载入Trojan 的html文件夹📁

在电脑端安装clash客户端，并在clash网站获取自己的订阅！

clash电脑端怎么刷入自己的节点呢如下:

输入自己的域名/上传文本的名字xxx.txt

到这里基本也就搞好了，手机用小火箭获取clash订阅，还可以单独安装节点Trojan！电脑端可以用clash客户端！


       感谢！不足之处还请见谅！

zboys  2020. 冬 https://zboys.ml/
