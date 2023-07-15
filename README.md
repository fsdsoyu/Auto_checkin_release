# 免责声明

- 本仓库发布的脚本及其中涉及的任何解密分析脚本，仅用于测试和学习研究，禁止用于商业用途，不能保证其合法性，准确性，完整性和有效性，请根据情况自行判断。
- 本项目内所有资源文件，禁止任何公众号、自媒体进行任何形式的转载、发布。
- 您必须在下载后的24小时内从计算机或手机中完全删除本仓库所有脚本。
- 任何人使用本仓库脚本不得用于非法用途，任何人将本仓库脚本用于非法用途所造成的一切后果由使用者承担。
- 本人无法100%保证使用本项目之后不会造成账号异常问题，若出现任何账号异常问题本人概不负责，请根据情况自行判断再下载执行！否则请勿下载运行！
- 如果任何单位或个人认为该项目的脚本可能涉及侵犯其权利，则应及时通知并提供相关证明，将在收到认证文件后删除相关脚本。
- 任何以任何方式查看此项目的人或直接或间接使用本项目的任何脚本的使用者都应仔细阅读此声明。
- 本人保留随时更改或补充此免责声明的权利。一旦使用并复制了任何相关脚本或本项目的规则，则视为您已接受此免责声明。
- 您使用或者复制了本仓库且本人制作的任何脚本，则视为 `已接受` 此声明，请仔细阅读

> ***您使用或者复制了本仓库且本人制作的任何脚本，则视为 `已接受` 此声明，请仔细阅读***
> ***本平台不会获取用户的账号密码，不会上传至其他任何地方，如果有所怀疑，请直接删除本程序***

# Auto_CheckIn 多平台自动签到

- 支持多用户签到
- 支持推送消息到pushplus平台(server酱和pushplus选择一个就好，也可以同时推送，如果不配置则不进行推送)
- 支持推送消息到server酱(server酱和pushplus选择一个就好，也可以同时推送，如果不配置则不进行推送)

## 已打包文件地址，可直接下载解压使用，配置yaoys_checkin_config.json即可，进入AutoCheckin找到exe点击启动

## 阿里云盘文件格式为exe格式，msi名称为安装包，green名称为免安装版

## 选择免安装版和安装版下载后解压exe得到程序或者安装包，阿里云盘地址：https://www.aliyundrive.com/s/ZeotJdW4iuh 提取码: 15oy

## 最新版本为v0.1.9

## 目前支持签到平台

- [GLaDOS平台](https://glados.rocks/)
- [天翼云盘](https://cloud.189.cn/web/login.html)
- [bilibili直播](https://live.bilibili.com)
- [科研通签到](https://www.ablesci.com/)
- [谷粉学术签到](http://bbs.99lb.net/)
- [阿里云盘](https://www.aliyundrive.com/)
- [Wps会员时长](https://vip.wps.cn/home)
- [Wps云空间容量](https://zt.wps.cn/spa/2019/vip_mobile_sign_v2/?csource=pc_cloud_membercenter&position=pc_cloud_sign/)
- [百度贴吧](https://tieba.baidu.com/)
- [交易猫](https://www.jiaoyimao.com/)
- [飘云阁](https://www.chinapyg.com/)
- [吾爱破解](https://www.52pojie.cn/portal.php)

## 当前需求或BUG(欢迎随时提出issues)

[Issues.md](说明文件/Issues.md)

## 签到列表

🟢: 正常运行 🔴: 脚本暂不可用 🔵: 可以执行(需更新)

| 状态 | 类别 | 终端 | 任务名称        | 名称                                                         | Cookie 时长 | 检查日期       | 备注                     |
| ---- | ---- | ---- |-------------| ------------------------------------------------------------ |-----------|------------|------------------------|
| 🟢️    | 签到 | WEB  | GLADOS      | https://glados.rocks/                                        | 待测试       | 2023-5-13  | 每日签到获取时长,需要开通会员才可以获取时长 |
| 🟢️    | 签到 | WEB  | BILIBILI    | https://www.bilibili.com/                                    | 待测试       | 2023-02-21 | 直播签到，获取硬币              |
| 🟢️    | 签到 | WEB  | CLOUD189    | https://cloud.189.cn/                                        | 永久        | 2023-02-21 | 每日签到 +2次抽奖获得空间奖励       |
| 🟢️    | 签到 | WEB  | AbleSci     | https://www.ablesci.com/                                     | 待测试       | 2023-5-13  | 科研通平台每日签到获取积分          |
| 🟢️    | 签到 | WEB  | gufenxueshu | http://bbs.99lb.net/                                         | 待测试       | 2023-5-13  | 谷粉学术每日签到获取积分           |
| 🟢️    | 签到 | WEB  | Aliyunpan   | https://www.aliyundrive.com/                                 | 待测试       | 2023-5-13  | 阿里云盘每日签到               |
| 🟢️    | 签到 | WEB  | WPS_Vip     | https://vip.wps.cn/home                                      | 待测试       | 2023-5-28  | WPS签到的会员时长，有时会失败，失败请手动 |
| 🟢️    | 签到 | WEB  | WPS_Cloud   | https://zt.wps.cn/spa/2019/vip_mobile_sign_v2/?csource=pc_cloud_membercenter&position=pc_cloud_sign | 待测试       | 2023-5-28  | Wps签到得空间容量，有时会失败，失败请手动 |
| 🟢️    | 签到 | WEB  | tieba       | https://tieba.baidu.com/                                     | 待测试       | 2023-6-18  | 百度贴吧签到                 |
| 🟢️    | 签到 | WEB  | jiaoyimao   | https://www.jiaoyimao.com/                                   | 2天/3天     | 2023-7-5   | 交易猫签到得积分               |
| 🟢️    | 签到 | WEB  | piaoyunge   | https://www.chinapyg.com                                 | 待测试       | 2023-7-10  | 飘云阁签到得积分               |
| 🟢️    | 签到 | WEB  | wuaipojie   | https://www.52pojie.cn/portal.php                              | 待测试       | 2023-7-10  | 吾爱破解签到得积分              |

## 支持的通知列表

server 酱（微信）

pushplus（微信）

## 更新日志

- 2023-7-10
    1. 新增飘云阁签到，吾爱破解签到
    2. 新增版本检测功能
- 2023-7-5
    1. 新增交易猫签到(Cookie很容易失效，暂时还没想到怎么通过账号密码登录)
- 2023-6-18
    1. 新增百度贴吧签到，每个贴吧之间签到间隔为5秒，关注的贴吧越多，签到时间越久
    2. 支持青龙面板部署
    3. **(重要！！！！！！！！)为了区分其他的config文件，修改配置文件名称为yaoys_checkin_config.json**
    4. 代码优化
    5. 使用Windows服务形式可以正常签到
    6. 发布版本0.1.8

- 2023-6-8

    1. 为了与其他配置文件区分，修改config.json文件名称为yaoys_checkin_config.json
    2. 测试青龙面板签到

- 2023-5-28
    1. 新增WPS签到获取会员时长和云空间容量，由于WPS签到策略，有时会需要验证码，如果出现需要验证码的情况，就只能手动签到了，目前设置云空间和会员时长之间签到需要间隔一分钟，如果出现长时间等待，请耐心
    2. 正在测试做成Windows服务的形式
- 2023-5-21
    1. 配置文件新增了是否是定时任务配置，如果是定时任务则按照定时任务每日执行，否则只执行一次
    2. 新增签到任务可以设置为服务，可以设置服务启动时执行一次或者每日定时执行(通过设置 **"is_scheduler": true/false**
       实现)
       具体如何设置为Windows的服务，请参考本文档''如何设置为Winodws服务''下的内容,**目前只支持Windows**
    3. 推送消息新增任务总数，成功数量，失败数量等信息

- 2023-5-14
    1. 修复glados平台多账号签到错误
- 2023-5-13
    1. 修复天翼云盘登陆失败的问题
    2. 发布0.1.2版本
    3. **签到不再依赖谷歌浏览器，无需谷歌浏览器也可以执行签到(重要)**
    4. yaoys_checkin_config.json文件进行修改，请参考最新版配置文件
    5. 解决[Issues.md](说明文件/Issues.md)文件中0.1.2版本的需求&BUG
- 2023-4-9 修复BUG
- 2023-3-28 增加阿里云盘签到

## 使用教程

参考[使用说明.md](说明文件/使用说明.md)

### 项目打包成exe

#### 使用 Auto PY to EXE将项目打包为exe,然后建立config文件夹，并将想要签到的平台cookie写入即可签到，打包命令：在conda环境下命令行模式输入:'auto-py-to-exe'

#### 使用 cx_Freeze 打包为 exe & msi  'python setup.py build' python setup.py bdist_msi

### 如何设置为Winodws服务

#### 使用NSSM工具，具体下载和使用步骤如下:

     1. 下载安装启动工具，具体可以百度如何使用
     2. 启动工具后选择下载的release中exe文件，设置相应的任务名称，描述等信息，安装服务即可
     3. 安装服务之前必须确保已经下载了已经打包好的exe文件以及相关目录，并且按照要求在相应的目录放置了并配置了config文件，**最好在服务启动之前自己验证下启动exe有没有错误**
     4. 设置服务为自动启动，可以在log日志文件中看到已成功启动，如果是定时任务，则可以按照设置的时间执行签到，如果是立即执行，则每次服务启动时执行签到。
     5. 建议：如果是服务器，则设置为定时任务，每日定时执行，如果是自己的电脑，不能保证每天都开着，那么就设置服务启动时立即执行签到，即："is_scheduler": false
     6. 如果服务启动后修改了配置文件中的‘common_config’ 和 ‘scheduler’中的相关配置，必须要重新启动服务才可以生效

### 青龙面板安装使用

1. 下载安装青龙面板
2. pip install yaoys-checkin 安装最新版本
3. 将 yaoys_checkin_config.json配置文件放在 /ql/scripts/目录下
4. 设置定时执行的时间执行签到