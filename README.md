
# 特性和攻击原理
## 神墓ATB系列
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

## 神墓ARC
### 匿名隐藏攻击
- 匿名SURF
- 负载均衡多Tor创建
### 信息聚合工具
- 网络地图(nmap)
- Dracnmap端口扫描仪
- 标准端口查找
- IP地址托管 
- 中间人攻击
- 红鹰全位扫描系统
- 回溯蜘蛛全位扫描系统
- 网站状态监测
- 邮箱开源共享智能系统
- 警犬甄别系统
- 罢工者监听系统
- 接口通行证秘密寻找器
- Shodan信息查找
- PY27端口扫描
- PY3重构端口扫描
- 开道者
### 字符生成
- Cupp密码词典生成
- 词单生成
- 精灵词汇生成
- 14亿密码词典
### Wireless attack tools
- [WiFi-Pumpkin](https://github.com/P0cL4bs/wifipumpkin3)
- [pixiewps](https://github.com/wiire/pixiewps)
- [Bluetooth Honeypot GUI Framework](https://github.com/andrewmichaelsmith/bluepot)
- [Fluxion](https://github.com/thehackingsage/Fluxion)
- [Wifiphisher](https://github.com/wifiphisher/wifiphisher)
- [Wifite](https://github.com/derv82/wifite2)
- [EvilTwin](https://github.com/Z4nzu/fakeap)
- [Fastssh](https://github.com/Z4nzu/fastssh)
- Howmanypeople
### SQL Injection Tools
- [Sqlmap tool](https://github.com/sqlmapproject/sqlmap)
- [NoSqlMap](https://github.com/codingo/NoSQLMap)
- [Damn Small SQLi Scanner](https://github.com/stamparm/DSSS)
- [Explo](https://github.com/dtag-dev-sec/explo)
- [Blisqy - Exploit Time-based blind-SQL injection](https://github.com/JohnTroony/Blisqy)
- [Leviathan - Wide Range Mass Audit Toolkit](https://github.com/leviathan-framework/leviathan)
- [SQLScan](https://github.com/Cvar1984/sqlscan)
### Phishing attack tools
- [Setoolkit](https://github.com/trustedsec/social-engineer-toolkit)
- [SocialFish](https://github.com/UndeadSec/SocialFish)
- [HiddenEye](https://github.com/DarkSecDevelopers/HiddenEye)
- [Evilginx2](https://github.com/kgretzky/evilginx2)
- [I-See_You(Get Location using phishing attack)](https://github.com/Viralmaniar/I-See-You)
- [SayCheese (Grab target's Webcam Shots)](https://github.com/hangetzzu/saycheese)
- [QR Code Jacking](https://github.com/cryptedwolf/ohmyqr)
- [ShellPhish](https://github.com/An0nUD4Y/shellphish)
- [BlackPhish](https://github.com/iinc0gnit0/BlackPhish)
### Web Attack tools
- [Web2Attack](https://github.com/santatic/web2attack)
- Skipfish
- [SubDomain Finder](https://github.com/aboul3la/Sublist3r)
- [CheckURL](https://github.com/UndeadSec/checkURL)
- [Blazy(Also Find ClickJacking)](https://github.com/UltimateHackers/Blazy)
- [Sub-Domain TakeOver](https://github.com/m4ll0k/takeover)
- [Dirb](https://gitlab.com/kalilinux/packages/dirb)
### Post exploitation tools
- [Vegile - Ghost In The Shell](https://github.com/Screetsec/Vegile)
- [Chrome Keylogger](https://github.com/UndeadSec/HeraKeylogger)
### Forensic tools
- Autopsy
- Wireshark
- [Bulk extractor](https://github.com/simsong/bulk_extractor)
- [Disk Clone and ISO Image Acquire](https://guymager.sourceforge.io/)
- [Toolsley](https://www.toolsley.com/)
### Payload creation tools
- [The FatRat](https://github.com/Screetsec/TheFatRat)
- [Brutal](https://github.com/Screetsec/Brutal)
- [Stitch](https://nathanlopez.github.io/Stitch)
- [MSFvenom Payload Creator](https://github.com/g0tmi1k/msfpc)
- [Venom Shellcode Generator](https://github.com/r00t-3xp10it/venom)
- [Spycam](https://github.com/indexnotfound404/spycam)
- [Mob-Droid](https://github.com/kinghacker0/Mob-Droid)
- [Enigma](https://github.com/UndeadSec/Enigma)
### Exploit framework
- [RouterSploit](https://github.com/threat9/routersploit)
- [WebSploit](https://github.com/The404Hacking/websploit )
- [Commix](https://github.com/commixproject/commix)
- [Web2Attack](https://github.com/santatic/web2attack)
### Reverse engineering tools
- [Androguard](https://github.com/androguard/androguard )
- [Apk2Gold](https://github.com/lxdvs/apk2gold )
- [JadX](https://github.com/skylot/jadx)
### DDOS Attack Tools
- SlowLoris
- [Asyncrone | Multifunction SYN Flood DDoS Weapon](https://github.com/fatihsnsy/aSYNcrone)
- [UFOnet](https://github.com/epsylon/ufonet)
- [GoldenEye](https://github.com/jseidl/GoldenEye)
### Remote Administrator Tools (RAT)
- [Stitch](https://github.com/nathanlopez/Stitch)
- [Pyshell](https://github.com/knassar702/pyshell)
### XSS Attack Tools
- [DalFox(Finder of XSS)](https://github.com/hahwul/dalfox)
- [XSS Payload Generator](https://github.com/capture0x/XSS-LOADER.git)
- [Extended XSS Searcher and Finder](https://github.com/Damian89/extended-xss-search)
- [XSS-Freak](https://github.com/PR0PH3CY33/XSS-Freak)
- [XSpear](https://github.com/hahwul/XSpear)
- [XSSCon](https://github.com/menkrep1337/XSSCon)
- [XanXSS](https://github.com/Ekultek/XanXSS)
- [Advanced XSS Detection Suite](https://github.com/UltimateHackers/XSStrike)
- [RVuln](https://github.com/iinc0gnit0/RVuln)
- [Cyclops](https://github.com/v8blink/Chromium-based-XSS-Taint-Tracking) 
### Steganograhy tools
- SteganoHide
- StegnoCracker
- [StegoCracker](https://github.com/W1LDN16H7/StegoCracker)
- [Whitespace](https://github.com/beardog108/snow10)
### Other tools
#### SocialMedia Bruteforce
- [Instagram Attack](https://github.com/chinoogawa/instaBrute)
- [AllinOne SocialMedia Attack](https://github.com/Matrix07ksa/Brute_Force)
- [Facebook Attack](https://github.com/Matrix07ksa/Brute_Force)
- [Application Checker](https://github.com/jakuta-tech/underhanded)
#### Android Hacking tools
- [Keydroid](https://github.com/F4dl0/keydroid)
- [MySMS](https://github.com/papusingh2sms/mysms)
- [Lockphish (Grab target LOCK PIN)](https://github.com/JasonJerry/lockphish)
- [DroidCam (Capture Image)](https://github.com/kinghacker0/WishFish)
- [EvilApp (Hijack Session)](https://github.com/crypticterminal/EvilApp)
- [HatCloud(Bypass CloudFlare for IP)](https://github.com/HatBashBR/HatCloud)
#### IDN Homograph Attack
- [EvilURL](https://github.com/UndeadSec/EvilURL)
#### Email Verify tools
- [Knockmail](https://github.com/4w4k3/KnockMail)
#### Hash cracking tools
- [Hash Buster](https://github.com/s0md3v/Hash-Buster)
#### Wifi Deauthenticate
- [WifiJammer-NG](https://github.com/MisterBianco/wifijammer-ng)
- [KawaiiDeauther](https://github.com/aryanrtm/KawaiiDeauther)
#### SocialMedia Finder
- [Find SocialMedia By Facial Recognation System](https://github.com/Greenwolf/social_mapper)
- [Find SocialMedia By UserName](https://github.com/xHak9x/finduser)
- [Sherlock](https://github.com/sherlock-project/sherlock)
- [SocialScan | Username or Email](https://github.com/iojw/socialscan)
#### Payload Injector
- [Debinject](https://github.com/UndeadSec/Debinject)
- [Pixload](https://github.com/chinarulezzz/pixload)
#### Web crawling
- [Gospider](https://github.com/jaeles-project/gospider)
#### Mix tools
- Terminal Multiplexer

### 如果你喜欢这个项目，就把star点亮吧！


# 文档
## 神墓ATB
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
## 神墓ARC

### 请以根用户运行神墓ARC!!!


### 常规方法


#### 第一步：克隆地址(SycaCore用户忽略)

    git clone https://github.com/Z4nzu/hackingtool.git

#### 第二步：赋予权限
    
    chmod -R 755 hackingtool  

#### 第三步：跳转目录（SycaCore用户忽略）

    cd hackingtool

#### 第四步：安装工具
    
    sudo bash install.sh

#### 第五步：安装附属插件

    sudo hackingtool


## 使用Docker容器化安装

### 一键式安装
`docker run -it vgpastor/hackingtool`

### 本地构建
`docker-compose build`

`docker-compose run hackingtool`

说多少次了，关注收藏加推送！！！