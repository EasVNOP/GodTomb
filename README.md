
## 特性和攻击原理
### 神墓ATB系列
>🔪表示攻击性模块 ⛔表示漏洞模块 🔱表示绕过模块

 * 第七应用层攻击：
   * 🔪 GET | 感染型GET报文攻击
   * 🔪 POST | POST报文攻击
   * 🔱 OVH | 绕过OVH验证攻击
   * 🔪 RHEX | 随机HAX字符串攻击
   * 🔱 STOMP | 绕过人机验证
   * 🔪 STRESS | HTTP请求攻击 
   * 🔪 DYN | 新型随机子域名攻击
   * 🔪 DOWNLOADER | 缓慢数据读取攻击
   * 🔪 SLOW | 传统Slowloris DDos
   * 🔪 HEAD | 强制返回标头
   * 🔪 NULL | 无效用户代理
   * 🔪 COOKIE | 随机PHP曲奇
   * 🔪 PPS |  1.1版本Http报文攻击
   * 🔪 EVEN | 更多表头攻击
   * 🔱 GSB | 绕过谷歌防御系统
   * 🔱 DGB | 绕过DDosGuard反攻击
   * 🔱 AVB | 绕过Arvan反攻击
   * 🔱 BOT | 绕过谷歌机器人
   * ⛔ APACHE | 攻击apache漏洞
   * ⛔ XMLRPC | 攻击Wordpress XMLRPC漏洞
   * 🔱 CFB | 绕过cloudflare验证
   * 🔱 BYPASS | 绕过AntiDDos普通模式
   * 🔱 BOMB | 绕过codesenberg/bombardier反攻击
   * 🔪 KILLER | 多线程攻击
   * 🔱 TOR | 绕过洋葱网站反攻击


* 第四通讯层攻击：
  * 🔱 TCP | 绕过终端控制洪流
  * 🔱 UDP | 绕过用户数据报协议洪流
  * 🔪 SYN | 字符同步洪流攻击
  * 🔪 CPS | 开关连接代理攻击
  * 🔪 ICMP | 互联网报文控制协议回声请求洪流攻击
  * 🔪 CONNECTION | 链接保活攻击
  * 🔪 VSE | 阀门源引擎协议攻击
  * 🔪 TS3 | Teamspeak3状态监测协议攻击
  * 🔪 FIVEM | GTA5服务器状态监测协议攻击
  * 🔪 MEM | 内存缓冲放大攻击
  * 🔪 NTP | 时间同步协议放大化攻击
  * 🔪 MCBOT | 我的世界自动化模拟攻击
  * 🔪 MINECRAFT | 我的世界状态监测协议攻击
  * 🔪 MCPE | 我的世界基岩版状态监测协议攻击
  * 🔪 DNS | 动态域名解析系统放大化攻击
  * 🔪 CHAR | 字符发生器协议扩大化攻击
  * 🔪 CLDAP | Cldap反射攻击
  * 🔪 ARD | 苹果远程桌面放大化攻击
  * 🔪 RDP | 远程桌面协议放大化攻击

* 特殊附加模块（暂不开源）
  * ADMNC 王杖 | 无缓冲夺取权限
  * PATHA 神笔 | 高速刷写环境变量和path
  * DREAM 梦魇 | 制造一个虚拟的环境
  * POPATT 穿杨 | 瞬间破坏僵尸网络中的小型设备
  * 

* 工具 - 使用 
`
python3 start.py tools指令运行
`
  * 🌟 CFIP | 查找cloudflare保护的网站的真实ip地址
  * 🔪 DNS | 查询网站的dns解析记录
  * 📍  TSSRV | TeamSpeak的SRV解析
  * ⚠  PING | 监测网站在线
  * 📌 CHECK | 检查网站状态
  * 😎 DSTAT | 显示字节输入输出数量

* 🎩 其他
  * ❌ STOP | 停止所有攻击
  * 🌠 TOOLS | 控制台工具
  * 👑 HELP | 查看使用方法

### 如果你喜欢这个项目，就把star点亮吧！


## 文档
**克隆程序并运行**

```shell script
git clone https://github.com/MatrixTM/MHDDoS.git
cd MHDDoS
pip install -r requirements.txt
```

**VPS单行安装**

```shell script
apt -y update && apt -y install curl wget libcurl4 libssl-dev python3 python3-pip make cmake automake autoconf m4 build-essential git && git clone https://github.com/MatrixTM/MHDDoS.git && cd MH* && pip3 install -r requirements.txt
```

[python3]: https://python.org 'Python3'
[github issues]: https://github.com/MatrixTM/MHDDoS/issues 'enter'

---
