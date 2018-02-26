安装 V2Ray
输入下面命令回车，你可以复制过去，然后在 Xshell 界面按 Shift + Insert 即可粘贴，不能按 Ctrl + V 的。。

bash <(curl -s -L https://233blog.com/v2ray.sh)
如果提示 curl: command not found ，那是因为你的小鸡没装 Curl
ubuntu/debian 系统安装 Curl 方法: apt-get update -y && apt-get install curl -y
centos 系统安装 Curl 方法: yum update -y && yum install curl -y
安装好 curl 之后就能安装脚本了

然后选择安装，即是输入 1 回车
选择传输协议，如果没有特别的需求，使用默认的 TCP 传输协议即可，直接回车
选择端口，如果没有特别的需求，使用默认的端口即可，直接回车
是否屏蔽广告，除非你真的需要，一般来说，直接回车即可

安装过程
是否配置 Shadowsocks ，如果不需要就直接回车，否则就输入 Y 回车
Shadowsocks 端口，密码，加密方式这些东西自己看情况配置即可，我个人当然是全部直接回车。。
OK，按回车继续

Shadowsocks 配置
安装信息，如果确保没有什么问题了，按回车继续

安装信息
(备注，安装信息会因你的配置而变化..不用在乎这截图)

V2Ray 安装完成
OK，此时 V2Ray 已经安装完成了。
询问是否生成需要生成二维码链接，我想，这是老手才需要的东西，萌新还要继续折腾，所以直接回车即可
(备注，二维码链接可以随时生成的，所以不需要有什么顾虑。)

V2Ray 安装完成
如上图所示，V2Ray 配置信息，Shadowsocks 配置信息都有了
如果你使用过 Shadowsocks ，那么现在你可以测试一下 Shadowsocks 配置了，看看是否能正常使用。
如果你使用过 V2Ray 某些客户端，那么现在也可以测试一下配置了。
(备注，可能某些 V2Ray 客户端的选项或描述略有不同，但事实上，上面的 V2Ray 配置信息已经足够详细，由于客户端的不同，请对号入座。)
