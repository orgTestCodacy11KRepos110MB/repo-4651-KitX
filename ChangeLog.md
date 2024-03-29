# 目录
- [目录](#目录)
- [v3.x](#v3-x)
  - [v3.22.x](#v3-22-x)
    - [v3.22.04](#v3-22-04)
      - [2022.10.03 02:24 v3.22.04.6287 Release](#2022-10-03-02-24-v3-22-04-6287-release)
        - [💾 Features](#features)
        - [🔧 Fixes](#fixes)
        - [🍻 New Contributors](#new-contributors)
      - [2022.08.12 00:32 v3.22.04.6235 Release](#2022-08-12-00-32-v3-22-04-6235-release)
        - [💾 Features](#features-1)
        - [🔧 Fixes](#fixes-1)
      - [2022.08.07 04:05 v3.22.04.6230 Preview](#2022-08-07-04-05-v3-22-04-6230-preview)
      - [2022.07.25 v3.0.6187.47831 Preview](#2022-07-25-v3-0-6187-47831-preview)
- [v2.x](#v2-x)
  - [v2.0.x](#v2-0-x)
    - [v2.0.5](#v2-0-5)
      - [2021-\&\&-\&\& \&\&:\&\& v2.0.5 preview](#2021-v2-0-5-preview)
    - [v2.0.4](#v2-0-4)
      - [2021-06-27 14:25 v2.0.4](#2021-06-27-14-25-v2-0-4)
    - [v2.0.3](#v2-0-3)
      - [2021-06-20 13:49 v2.0.3](#2021-06-20-13-49-v2-0-3)
    - [v2.0.2](#v2-0-2)
      - [2021-06-14 13:08 v2.0.2](#2021-06-14-13-08-v2-0-2)
    - [v2.0.1](#v2-0-1)
      - [2021-06-08 14:23 v2.0.1](#2021-06-08-14-23-v2-0-1)
    - [v2.0.0](#v2-0-0)
      - [2021-05-28 14:00 v2.0.0](#2021-05-28-14-00-v2-0-0)
- [v1.x](#v1-x)
  - [v1.2.x](#v1-2-x)
    - [v1.2.7](#v1-2-7)
      - [2021-05-18 17:11 v1.2.7 修正](#2021-05-18-17-11-v1-2-7-修正)
      - [2021-05-04 12:58 KitX v1.2.7 Release Note](#2021-05-04-12-58-kitx-v1-2-7-release-note)
    - [v1.2.6](#v1-2-6)
      - [2021-04-18 15:58 KitX v1.2.6 Release Note](#2021-04-18-15-58-kitx-v1-2-6-release-note)
    - [v1.2.5](#v1-2-5)
      - [2021-04-11 14:20 KitX v1.2.5 Release Note](#2021-04-11-14-20-kitx-v1-2-5-release-note)
    - [v1.2.4](#v1-2-4)
      - [2021-04-05 13:10 KitX v1.2.4 Release Note](#2021-04-05-13-10-kitx-v1-2-4-release-note)
      - [2021-04-02 21:45 KitX v1.2.4 Preview Note](#2021-04-02-21-45-kitx-v1-2-4-preview-note)
    - [v1.2.2](#v1-2-2)
      - [2021-03-14 01:11 KitX v1.2.2 Release Note](#2021-03-14-01-11-kitx-v1-2-2-release-note)
    - [v1.2.1](#v1-2-1)
      - [2021-03-13 23:12 KitX v1.2.1 Release Note](#2021-03-13-23-12-kitx-v1-2-1-release-note)
    - [v1.2.0](#v1-2-0)
      - [2021-02-25 04:51 KitX v1.2.0 Release Note](#2021-02-25-04-51-kitx-v1-2-0-release-note)
  - [v1.1.x](#v1-1-x)
    - [v1.1.5](#v1-1-5)
    - [v1.1.4](#v1-1-4)
    - [v1.1.2](#v1-1-2)
    - [v1.1.1](#v1-1-1)
    - [v1.1.0](#v1-1-0)
      - [2021/02/10 04:10 KitX v1.1.0 Release Note](#2021-02-10-04-10-kitx-v1-1-0-release-note)
  - [v1.0.x](#v1-0-x)
    - [v1.0.5](#v1-0-5)
    - [v1.0.4](#v1-0-4)
    - [v1.0.0](#v1-0-0)
- [Beta](#beta)
  - [Beta](#beta-1)
    - [Beta\_10235, Beta\_10213, Beta\_10016](#beta-10235-beta-10213-beta-10016)
      - [时间过于久远 KitX Beta 版本上新 Beta Note](#时间过于久远-kitx-beta-版本上新-beta-note)

# v3.x

## v3.22.x

### v3.22.04

#### 2022.10.03 02:24 v3.22.04.6287 Release
##### 💾 Features
* 公告面板按照从新到旧的顺序排列公告 by @Dynesshely in #60
* 新增启动时显示公告的设置项 by @Dynesshely in #66
* 二级菜单状态保留, 仓库页面开发者导入按钮, 心跳包过期时间调整, 配置文件重构, 新增语言项 by @Dynesshely in #77
* .kxp 格式编解码器完工, 一些其它更新, CI流程更新 by @Dynesshely in #78
* 导入包逻辑动工, Win平台安装包增加文件关联,增强异常捕获能力 by @Dynesshely in #80
* 新的版本号规则 by @Dynesshely in #83
* 推送包转为手动执行, 以及更先进的 CI 流程控制 by @Dynesshely in #85 #86
* Win安装包有关权限的改进 by @Dynesshely in #91
* Win安装包在安装和卸载时同步更新任务栏进度 by @Dynesshely in #92
* 改用文件信息的产品版本,而不是从程序集中获取 by @Dynesshely in #93
* KXP文件增加格式识别头 by @Dynesshely in #94
* KXP 现在打包 PluginStruct by @Dynesshely in #98
* 错误代码 | Error Codes by @Dynesshely in #100
* 插件列表, 代码样式, 配置项, 语言项 by @Dynesshely in #103
* UI更新, 插件列表 by @Dynesshely in #104
* 插件名称多语言支持, 更详尽的UI布局 by @Dynesshely in #105
* 有关托盘图标的逻辑(已在Win11,Ubuntu22.04中测试并通过) by @Dynesshely in #110
* 基于 Blazor 重写官网, 加入插件市场 by @Dynesshely in #117
* 几个工具项目的创建, 网络部分优化 by @Dynesshely in #122
* 图标更新 by @Dynesshely in #124
* 更新支持情况, 添加新的路线图 by @Dynesshely in #126
* 全部 Framework 项目迁移到 .Net 4.6 by @Dynesshely in #127
* 接口变更, 日志框架更换 by @Dynesshely in #132
* 插件逻辑优化 by @LYF511 in #135
* 设置页面拆分, 多语言主题设置, UI更新 by @Dynesshely in #140
* 日志系统及设置UI大改 by @Dynesshely in #141
* 根目录结构优化, 网络通信规则变更, 更新页面逻辑完善, 更换到等宽字体-更纱黑体 by @Dynesshely in #146
* 一些 UI 更新 by @Dynesshely in #154

##### 🔧 Fixes
* 修复了调色板相关错误 by @Dynesshely in #64 #66
* Correct a typo in KitX Dashboard.csproj by @felixonmars in #113
* 文档目录链接修复 by @Dynesshely in #129
* 链接修复, 文本校对 by @Dynesshely in #130
* 链接修正, 更多折叠 by @Dynesshely in #131
* 一堆bug修复与优化 by @Dynesshely in #137
* 配置系统升级, 自发现逻辑优化, 修复多网络适配器导致的问题 by @Dynesshely in #139

##### 🍻 New Contributors
* @felixonmars made their first contribution in #113
* @truebigsand made their first contribution in #114
* @LYF511 made their first contribution in #135
* @orzMaster made their first contribution in #152

**Full Changelog**: https://github.com/Crequency/KitX/compare/v3.22.04.6235...v3.22.04.6287

#### 2022.08.12 00:32 v3.22.04.6235 Release
##### 💾 Features
* 添加 Light 主题下的窗口透明度效果
* Mica 透明度支持无级调节
* 临时配置保存按钮需要开启开发者选项才变为可见
* 局域网设备发现功能更新
* 日志系统 等模块的功能更新
* 设备页UI更新
* 异常捕获, 新的插件页管理逻辑, 弃用子线程, 降低CPU占用率
* 公告系统更新, 可以在线获取新公告了

##### 🔧 Fixes
* Fixed #42, 修复了多个插件同时退出导致的线程不安全
* Fixed #44, 修复了进入库页面但之前已经有插件连接了的显示错误

**Full Changelog**: https://github.com/Crequency/KitX/compare/v3.22.04.6230...v3.22.04.6235

#### 2022.08.07 04:05 v3.22.04.6230 Preview
基础UI逻辑基本完工, 一些逻辑也大差不差, 现开放公测.

#### 2022.07.25 v3.0.6187.47831 Preview
基础框架制作完毕
包括:
1. 简单的配置文件系统 (由 Crequency.BasicHelper 提供)
2. 简单的日志系统 (由 Crequency.BasicHelper 提供)
3. 深浅色主题切换以及多语言支持
4. 在 Win11 上可以尝试启用云母特效
5. 基础插件模型的制作

此次 Release 并非正式版, 仅用于多平台稳定性测试

# v2.x

## v2.0.x

### v2.0.5

#### 2021-&&-&& &&:&& v2.0.5 preview

记不得更新啥了, 反正这是 KitX 最后一个版本了
也不知道多久更新的
顺便说一句, 这个是 v2.0.5 的预览版
正式版估计永远都不会到来了
再见了, KitX
永远的神级工具箱















因为 KitX 3 来了!!!!!!!!!!!!!!!!!!!!!!!!!!!!😁😍😘🤣😂😊
期待重构过后的 KitX 3 吧!

### v2.0.4

#### 2021-06-27 14:25 v2.0.4

这次更新修复了一些显示问题
同时：

1. 缩减了更新包体积至 166kb ，秒速下载
2. 修复注册KitX账户页面到《用户隐私政策》的链接无法访问的问题
3. 优化了内存占用
4. 对插件的更新：
5. Algorithm List 插件中新增平抛运动模块
6. 修复 NotePads 中字体颜色显示异常的问题

### v2.0.3

#### 2021-06-20 13:49 v2.0.3

此次更新内容如下：

1. 库界面筛选器中：标签组别 和 搜索框 筛选器可用
2. 优化底层算法
3. Algorithm List 插件中新增三个模块，分别是：斐波那契数列、精确求π、精确开平方
4. 遗憾的是，仍然没有带来新版安装包，对不起啦QAQ

### v2.0.2

#### 2021-06-14 13:08 v2.0.2

这次更新内容如下：

1. KitX 中重新启用了 “更新” 功能，可以在线下载最新版的压缩包，但需要用户手动解压，遗憾的是，还是没有做好独立安装包
2. 优化了用户账户登陆速度，重做多线程异步获取用户信息模块，减少卡顿时长，但由于一些不可抗力，还没有做到完全异步，头像的拉取仍然由UI线程执行
3. 用户登录后的账户信息页添加分享按钮，可以获取用户卡片截图，并复制到剪贴板，可以在QQ等应用中粘贴
4. 工具市场中的筛选器可用了，可以筛选不同类别的工具

### v2.0.1

#### 2021-06-08 14:23 v2.0.1

这次是一个小的功能优化：
优化了应用启动速度，优化了KitX账户登陆速度

### v2.0.0

#### 2021-05-28 14:00 v2.0.0

本次是一个常规的普通更新
至于为什么当作一个大版本号的更新，因为许多配套的云服务都有翻天覆地的变化，尤其是 https://docs.catrol.cn/old/ 。
2.0.0 将成为一个新的开始

本次更新内容：

1. 修复了一些底层问题
2. 修改了代码中的指向性链接，使之配套云服务
3. 云服务从 Windows Server 系统的云服务器转移到 使用 CentOS 的 Linux 云服务器
4. 工具市场中新增筛选组按钮，（ps：当前只有 “全部” 按钮可用）

> 另外，此版本开始将取消原先使用的安装包程序，改为压缩包发布，安装包将采用新技术制作，这可能需要一点时间
预计新技术制作的安装包程序将在三周左右内回归

# v1.x

## v1.2.x

### v1.2.7

#### 2021-05-18 17:11 v1.2.7 修正

暂无

#### 2021-05-04 12:58 KitX v1.2.7 Release Note

大大大大大大大大大大大大大大大大大大大更新!!!😁
特别的是，从这个版本之后除了便携本将提供安装包（虽然有点丑）

新增如下功能：

1. 工具市场的工具信息提示
2. 工具栏的透明度调节，置顶优化
3. 工具栏UI布局优化，解决了长语言时显示不全的问题
4. 库界面的UI布局优化，解决了多插件时点击不到三个点的问题
5. 解决了主窗口关闭任务栏之后，控制按钮不会自动弹回的问题
6. 优化了插件的底层代码，提高了效率
7. 新增调试命令 help
8. 修改了主题色，没有那么刺眼了
9. 部分插件迎来大更新

### v1.2.6

#### 2021-04-18 15:58 KitX v1.2.6 Release Note

新增如下功能：

1. 解决了 本地应用管理窗格（ LocalAppsManager ），上部分穿梭框不能用的问题
2. 修复了本地应用的一些 bug
3. 异步起动本地应用，防止可能造成的卡死
4. 修复了一些其他的 Bug

### v1.2.5

#### 2021-04-11 14:20 KitX v1.2.5 Release Note

小更新，主要更新针对添加本地应用到AppsBar的功能。

### v1.2.4

#### 2021-04-05 13:10 KitX v1.2.4 Release Note

大大大大大大大大大大大大大更新！！！
清明节连肝三天终于肝出来了 (￣▽￣)~*

此次更新的内容有：

1. 工具市场增加了下载功能
2. 修复了库界面工具列表鼠标滚轮无法滚动的问题
3. 完善了第一次启动引导（虽然五页内容只做了三页）
4. 修复了语言切换的问题
5. 修复了主题切换的问题
6. 修复了配置文件相关的问题
7. 优化了部分底层逻辑
8. 解决了库界面多次刷新导致重复将插件注入内存的问题
9. 将压缩内存的黑科技的定时器设定为半分钟
10. 网站下载页全新改版，直接重做，更加简约大方
11. 移除了 Zoomer 官方插件，预计在三周之内重做新版 Zoomer 并发布

计划的下次更新：
1. 填补第一次启动引导剩余空白页
2. 还要更新啥我暂时没想好QAQ

#### 2021-04-02 21:45 KitX v1.2.4 Preview Note

v1.2.4 Preview 预览更新中，发现如下问题，将在 Release 正式版中修复

1. 库界面多次刷新已安装插件会重复将已安装插件注入内存，造成软件卡顿，界面卡顿等等问题。
2. 库界面插件列表鼠标滚轮无法滚动页面的问题。

### v1.2.2

#### 2021-03-14 01:11 KitX v1.2.2 Release Note

Release v1.2.2 版本已发布，是的，就过了几个小时而已。
这个版本是针对修改过后的用户数据库的。
所以，注意！！！！！！！！！！！！

> 此版本号之前的所有版本不再能够使用用户系统！！！

具体更新细节如下：

1. 用户系统改用手机号码作为用户的唯一标识符
2. 修复了‘关于’界面版本号显示异常的问题

### v1.2.1

#### 2021-03-13 23:12 KitX v1.2.1 Release Note

Release v1.2.1 版本已发布，包括但不限于官方站点与 KitX插件开发 群文件。
此次更新主要包括一些质量更新以及一些质量修复。

具体更新细节如下：

1. 修复了在应用程序目录下存放插件时配置文件保存的是绝对目录而非相符路径的问题。
2. 修复了 TeamC 插件引发的主题切换失败异常。
3. 修复了一些启动时异常。
4. 重构了一部分代码，启动速度稍稍变快。

计划的更新：
1. 取消以身份证号为账户唯一标识符的注册方式，计划更新为邮箱与电话任意其一的注册方式，并以邮箱作为账户唯一标识符。
2. 工具市场 模块的完善 （ 已经新建文件夹了 QAQ）。

另外:

最近学习任务有些重，老师们赶进度挺紧的，倒是觉得态度比上个学期好太多了，所以放缓了 KitX 的更新，不过，相信我，我觉得今年暑假一定能拿出一个更完善并且适合日常使用的版本。
感谢大家的支持！！！

### v1.2.0

#### 2021-02-25 04:51 KitX v1.2.0 Release Note
大概在几分钟前，正式版 v1.2.0 已经上传到QQ群 KitX插件开发 群文件，这次更新了一个超受用的功能，并为之后的更新打下了基础

具体更新细节如下：

1. 新增加了用户页面，加入了登录、注册、账户信息窗口，现支持用户头像的上传。
2. 新增配置文件云同步功能，登录账号后，可以将配置文件同步至改账号下。
3. 修复了 KitX.exe 主程序退出后 KitX.Helper.exe 仍在运行没有一同退出的问题，解决方法：主程序退出时运行根目录下 KitX.Helper.Shutdown.vbs 来结束 KitX.Helper.exe 进程。

发现的新问题：暂无

计划的更新：
1. Web 应用的支持
2. KitX.Publish 插件的开发 （用于打包现有插件及相关文档为 .kxt 安装包）
3. 完善第一次启动的引导
4. 适当给予插件通过 KitX 账号云同步的权限

备注：
感谢这段时间以来，大家对我的支持
这个版本对数据库的连接调试了很久，SQL 语句很久没用了，捡起来的时候已经差不多忘光了，所以这次更新鸽了挺久的，对不起啦
前段时间听说一个叫 uTool 的电脑工具箱，我试了一下，用起来还行，美中不足的是，Web 应用套一个 Electron 的壳不一定能处理数据量大一点的任务，这正是我开发原生桌面插件式工具箱的原因

## v1.1.x

### v1.1.5
暂无

### v1.1.4
暂无

### v1.1.2
暂无

### v1.1.1
暂无

### v1.1.0
暂无

#### 2021/02/10 04:10 KitX v1.1.0 Release Note

大概在几分钟前，正式版 v1.1.0 已经上传到QQ群 KitX插件开发 群文件，我们迎来了一次超棒的功能完善

具体更新细节如下：

1. 新增了 KitX 专有安装格式 .kxt ，支持拖入工具列表或加号按钮单击导入，不支持复制到工具目录下来添加
2. 新增了对 .kxt 格式的图标支持以及双击打开功能
3. 新增了 KitX.Helper.exe 程序，位于主程序目录下，使得主窗口主菜单中的重启菜单可用
4. 完善了应用的重启功能
5. 完善了亿点点应用栏的动画效果
6. 应用栏的窗体属性更改为了工具窗口属性，你现在可以在不同的虚拟桌面或是多个屏幕上同时看到应用栏啦
7. 工具空间的文件夹组织方式变更为 .../发布者/插件名/... 的形式
8. 修复了工具空间文件夹概率性混乱的问题

发现的新问题：
1. 目前部分自带插件内部代码的异常可能导致主程序的崩溃，至于全局异常处理为什么没有捕获到异常的原因还在排查中
2. 系统更换主题或是自定义颜色时，主窗体显示发生异常（推测是半自定义窗体套用ControlTemplate的问题，该问题已提交到 开发日程 ）
3. 部分情况下访问系统注册表来显示 .kxt 格式文件的图标捕获到了“无法访问注册表”的异常，目前已查明，如果当前系统登录用户没有管理员权限则会出现此异常

计划的更新：
1. Web 应用的支持
2. KitX.Publish 插件的开发 （用于打包现有插件及相关文档为 .kxt 安装包）
3. 完善第一次启动的引导
4. 用户系统的建立

## v1.0.x

### v1.0.5
暂无

### v1.0.4
暂无

### v1.0.0
暂无

# Beta

## Beta

### Beta_10235, Beta_10213, Beta_10016

#### 时间过于久远 KitX Beta 版本上新 Beta Note

趁着时间并不算充裕的寒假，我把 KitX 一些功能完善，来不及完善的地方均打上了 “开发中” 的标志，在年前把 Beta 版算是完善了出来。
希望您能喜欢。

