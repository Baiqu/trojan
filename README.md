### 注册域名（已经有了，直接跳过）
# https://hk.godaddy.com
# *.online 域名，首年7.67港币

### Google Cloud
# 新注册帐户，目前送300美元（政策变化，以官方为主）
# 创建一个虚拟主机，系统选择Ubuntu 18的版本（其他版本不代表不能用，只是没有测试过，欢迎大家测试过反馈）
# 安装系统时一定确保域名已经指向到该服务器的IP的地址
# 进入系统后台时，先切换到超级用户，输入：sudo -i回车
# 输入：bash <(curl -sL https://raw.githubusercontent.com/hijkpw/scripts/master/trojan.sh)
# 提示输入主机名：就是准备好的域名，已经成功指向服务器地址的域名地址。
# 安装后成功，就显示密码，记住密码，这个客户端要用到的。
# 整个安装过程非常简单。


### 客户端使用
# MAC系统：推荐 https://github.com/yichengchen/clashX/releases  下载安装
# 配置文件：下载，修改域名与密码即可。
# 其他任何支持Trojan的软件，理论上都能使用，但我在实际过程中，测试过V2RayU，多次测试，重新安装，未能成功使用。

# IOS系统：推荐小火箭 Shadowrocket 是一款收费软件，但真的很好，搭建了几个服务器，在这个软件上全部测试通过，但另两个设备未能成功。

# Android系统：推荐用 Clash ，在谷哥市场中搜索Clash for android下载。
# 为什么推荐这款，测试过V2RayNG，用V2ray服务器Vmess协议正常使用，用Vless协议不成功，这里提一下Vless协议，这个方案安全与目前Trojan类似，都比较安全，因为调试不通过，所以放弃。
