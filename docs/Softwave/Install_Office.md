---
comments: true

---

# 安装Office

## 前言

> Microsoft Office是由微软公司开发的办公软件套裝，有Microsoft Windows、Mac系列、iOS和Android等不同系统的版本。
>——维基百科

相较于金山文档的WPS，Office提供更加强大功能，更好的性能优化，  丝滑的动画，触控优化，以及最重要的兼容性。与WPS整天往文件和用户电脑里偷偷加私货，以及那糟糕的优化和令人恶心的会员功能相比，Office是你扔掉WPS最好的理由！
一个干净，强大，流畅的办公套件！

## 认识Ofiice
Office包含以下套件:

| 图标 | 名称 | 描述 |
|  ----  | ----  | ----  |
| ![word](./img/Pasted%20image%2020240711163910.png)  | Word | 写文档的 |
| ![](img/Pasted%20image%2020240711163945.png)  | PowerPoint | 做PPT的 |
| ![](img/Pasted%20image%2020240711163916.png)  | Excel | 做表格 |
| ![](img/Pasted%20image%2020240711164435.png)  | Outlook | Outlook邮箱客户端 |
| ![](img/Pasted%20image%2020240711164357.png)  | OneDrive | 微软自家的网盘 |
| ![](img/Pasted%20image%2020240711164411.png)  | OneNote | 笔记应用 |
| ... | ... | ... |

还有一些是企业软件或者日常不怎么会碰到软件这里就不列举了，可以自行去[Microsoft官网]([Microsoft 365 - Office 应用的订阅 | Microsoft 365](https://www.microsoft.com/zh-cn/microsoft-365))去看

## Windows安装Office

在Windows下安装Office非常简单，国内已经有大佬为此开发出[**Office Tool Plus**]([Office Tool Plus | 一键部署 Office (landian.vip)](https://otp.landian.vip/zh-cn/))这个强大且好用的Office部署工具，可以帮助我们快速部署微软官方的原版Office，接下来我们将通过Office Tool Plus来安装Office。

您可以选择阅读Office Tool Plus官方的新手入门教程(里面有傻瓜式一键部署命令)[[新手必读] Office Tool Plus 入门教程 - Yerong の小窝 (coolhub.top)](https://www.coolhub.top/archives/42)也可以阅读我们提供的使用教程。
### 系统要求

在Windows下安装Office需要确保您不是古老的**Windows XP**以及**更低**版本的系统，对于Windows 7/8/8.1等系统，我们建议您升级到Windows 10系统，这些版本的Windows无法使用**Office 2019/2021**以及更高的版本(Office 365除外)。

!!! Info "注意"
	Office默认安装在C盘且不可更改，请确保您的C盘有足够的空间
### 下载工具

打开[Office Tool Plus](https://otp.landian.vip/zh-cn/)官网，在右上方选择下载，并选择合适的版本下载(32位操作系统选32位，64位操作系统选64位，ARM架构选择ARM64)

解压压缩包到一个你喜欢的位置比如`G:/Office Tool`当然桌面也是没问题的(虽然这是个坏习惯)

解压后文件目录应为如图所示:

![](img/Pasted%20image%2020240711172519.png)
### 运行工具

运行**Office Tool Plus.exe**，进入欢迎界面

在安装开始前，请做好以下事情(如果没安装过Office或者WPS可以直接忽略)：
1. 卸载 WPS Office，两者共存容易出问题（没有问题当我没说）。
2. 卸载旧版本 Office，按照标准流程操作。请勿直接强制移除，有问题再强制。
3. 清除旧版本激活信息，看下方的截图。
4. 清除 Office 设置，⌈工具箱⌋ - ⌈重置 Office 设置为默认设置⌋，可以选择所有选项进行删除

![](img/Pasted%20image%2020240711173323.png)
### 安装Office

点击**安装Office**按钮旁的小勾，选择Microsoft 365（家庭和个人版）

![](img/Pasted%20image%2020240711172955.png)

弹出消息提示仔细阅读后根据需要进行选择（建议选是）

![](img/Pasted%20image%2020240711173556.png)

进入最后的部署配置文件确认弹窗，确认后点击**是**开始部署，然后耐心等待

!!! Info "注意"
	该选项默认安装**Word、PowerPoint以及Excel**如果需要安装其它套件请选择**否**并下拉到(产品->应用程序)选择自己需要的套件(图二)
	
![](img/Pasted%20image%2020240711173640.png)

![](img/Pasted%20image%2020240711173920.png)

### 激活Office

#### 前言

与Windows一样Office依旧是买断制软件(Office 365是订阅制)但不妨碍我们进行"白嫖",接下来我们将尝试激活您的Office，当然如果有能力请支持微软正版->[Microsoft 365 - Office 应用的订阅 | Microsoft 365](https://www.microsoft.com/zh-cn/microsoft-365)
#### 注意事项

**为了确保激活能顺利完成，请务必使用最新版 Office Tool Plus.**

**+** 激活开始前，请知晓以下事情：

1. 如果你激活出现了问题，请首先检查自己的步骤是否有误，再去检查系统是否有问题。
2. 激活出现问题时，请不要盲目去重装 Office，这几乎是毫无作用的，只会浪费时间。
3. Office 激活完成后，所有功能正常使用，不存在什么不能登录账户这种说法。
4. Office 的部分功能需要搭配个人/企业账户使用。
5. 使用此处的 KMS 并不会造成电脑被控制，请放心使用。
6. 你不能使用 KMS 激活零售 (Retail) 许可证，KMS 只能激活批量 (Volume) 许可证。
7. 如果你的 Office 版本太旧会导致 Office Tool Plus 无法正常识别，请通过 Office Tool Plus 重新安装 Office.
8. 激活后，在 KMS 主机以及网络正常的情况下，系统会自动续期，不会 180 天后到期。

**请务必仔细查阅教程，如因个人问题造成误解等，请自行承担所有后果。**

#### 原理浅谈

//不想看的可以直接看下一节

1.Ohook激活
	Ohook激活即通过Dll劫持Hook掉SPPC，通过劫持Software Protection 服务(Office会通过Software Protection 服务来查询激活状态)返回修改后的消息，让Office误认为所有许可证已经被激活，从而达到永久激活的效果

2.KMS激活
	烂大街的激活方法，本质上类似于你小时候为了避免屁股开花“帮”你父母代签，你的试卷Or作业，起初是微软为了方便企业批量管理许可而整的激活方式，一般有微软授权的KMS服务器一般情况下只能部署在 Windows Server 上，只在内网部署，不对外开放。大家用的懂的都懂，基于 vlmcs 的 KMS 服务器，非正版，无激活限制，谁都可以访问。只要微软没发现（不管）你就可以一直用。KMS激活需要180天一续，但通常软件都会设置自动续期。
#### 使用Office Tool Plus自动激活

1.先清除激活消息，激活信息并不会随Office卸载而清除（如果上面您已经清除了，请忽略这一步）

![](img/Pasted%20image%2020240711173323.png)

2.按下快捷键 Ctrl + Shift + P，打开命令框，按需复制下面的命令，粘贴后回车 Enter。

![](img/Pasted%20image%2020240711181044.png)

Microsoft 365:
`ospp /inslicid MondoVolume /sethst:kms.03k.org /setprt:1688 /act`

??? details "Office LTSC 2021, Visio LTSC 2021, Project 2021"
	`ospp /inslicid ProPlus2021Volume /sethst:kms.loli.best /setprt:1688 /act`
	`ospp /inslicid VisioPro2021Volume /sethst:kms.loli.best /setprt:1688 /act`
	`ospp /inslicid ProjectPro2021Volume /sethst:kms.loli.best /setprt:1688 /act`

??? details "Office, Visio, Project 2019"
	`ospp /inslicid ProPlus2019Volume /sethst:kms.loli.best /setprt:1688 /act`
	`ospp /inslicid VisioPro2019Volume /sethst:kms.loli.best /setprt:1688 /act`
	`ospp /inslicid ProjectPro2019Volume /sethst:kms.loli.best /setprt:1688 /act`

??? details "Office, Visio, Project 2016"
	`ospp /inslicid ProPlusVolume /sethst:kms.loli.best /setprt:1688 /act`
	`ospp /inslicid VisioProXVolume /sethst:kms.loli.best /setprt:1688 /act`
	`ospp /inslicid ProjectProXVolume /sethst:kms.loli.best /setprt:1688 /act`

想要手动激活？访问官方文档[[激活 Office] Office Tool Plus 入门教程 - Yerong の小窝 (coolhub.top)](https://www.coolhub.top/archives/14)

#### 使用Microsoft Activation Scripts (MAS)激活

通过Office Tool Plus的自动激活我们可以发现其许可证是2016的许可证，虽然不会导致您的Office有任何的功能确实但对于强迫症来说emmm.....，接下来我们将使用MAS进行Ohook激活。

对于windows10以上的用户打开终端或者Powershell（反正只要不是cmd就行）输入`irm https://get.activated.win | iex`回车Enter即可安装MAS

对于没有Powershell的系统可以前往[项目主页]([massgravel/Microsoft-Activation-Scripts: A Windows and Office activator using HWID / Ohook / KMS38 / Online KMS activation methods, with a focus on open-source code and fewer antivirus detections. (github.com)](https://github.com/massgravel/Microsoft-Activation-Scripts/tree/master))将仓库打包下来解压到本地，并打开`/MAS/All-In-One-Version`下的.cmd文件

![](img/Pasted%20image%2020240711183233.png)

打开后进入主界面，按下**数字2**选择Ohook激活Office

![](img/Pasted%20image%2020240711183444.png)

随即按下**数字1**进行激活，其它选项分别是\[2]卸载Ohook激活、\[3]下载Office、\[0]返回

![](img/Pasted%20image%2020240711183533.png)

稍等片刻出现绿色的`Office is permanently activated.`即表示激活成功

![](img/Pasted%20image%2020240711183804.png)

此时打开Office发现许可证变成了Microsoft 365 Apps for enterprise

![](img/Pasted%20image%2020240711184637.png)

