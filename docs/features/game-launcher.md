---
headerDepth: 0
---

# 高级启动器

::: tip
- 在设置完毕启动游戏所需的附加选项后，点击右下角的`启动游戏`按钮即可
- 选择游戏路径时，请注意此处选择的应是游戏本身
    - 形如："$\Genshin Impact\Genshin Impact Game\YuanShen.exe"
:::

## 切换服务器

- 在主界面点击左侧菜单栏进入`启动游戏`页面

- 点击右侧选项中的服务器名称，选择要进入的服务器

    - 目前可选的服务器为`官方服|天空岛`与`渠道服|世界树`
        - 若需切换至世界树服务器，则应将[PCGameSDK.dll 文件](https://cloud.06dn.com/api/v3/file/source/179514/PCGameSDK.dll?sign=dbF4NoPqrSemUlbugtU71iYk1IZaW7JHQK9TbHMBTNg%3D%3A0)放入"Plugins"文件夹中
            - 该目录的路径形如"$:\Genshin Impact\Genshin Impact Game\YuanShen_Data\Plugins"
        - 若下载到的`PCGameSDK.dll 文件`的文件名中有其他字符，建议将其重命名为"PCGameSDK.dll"，以防止读取错误
        - 若需要切换不同的服务器，须确保`以管理员模式启动`"胡桃工具箱"

## 账号保存
::: tip
本功能所描述的**帐号**，特指当前原神所登录游戏账号的**登录状态**
:::

- 在主界面点击左侧菜单栏进入`启动游戏`标签
- 点击`账号`功能中的`检测`按钮
- 在弹出的`为账号命名`界面中，输入您要为此账号设置的名称，点击确认
- 此时即可在`账号`功能下方自由选择您要切换的账号
    - 每个已保存的账号均为可点击选择的按钮
    - 在其右侧有三个按钮，分别为：
        - `绑定当前用户角色`，即将您当前选择的米游社登录状态绑定至该账号中，点击该按钮后，对应的UID将出现在该账号自定义名称的下方
        - `重命名`，即修改当前选择账号的自定义名称
        - `删除`，即删除当前选择的账号

::: tip
请注意：获取当前原神的**登录状态**通常需要管理员权限，建议`使用管理员模式启动胡桃`
:::

## 外观选项

- 在主界面点击左侧菜单栏进入`启动游戏`标签
- 在右侧的`外观`功能中，有四个选项：
    - **全屏**，即选择启动游戏后的游戏界面是否设置为全屏
    - **无边框**，即选择启动游戏后的游戏界面是否设置为无边框窗口
    - **宽度**，即选择启动游戏后的游戏界面的宽度，例如`1920`
    - **高度**，即选择启动游戏后的游戏界面的高度，例如`1080`

## 解锁帧率上限

::: warning
请注意：此功能已明确标注为`Dangerous Feature`，即**危险功能**，选择启用即代表您选择自行承担任意风险
:::

- 使用`管理员模式`启动胡桃
- 在主界面点击左侧菜单栏进入`启动游戏`标签
- 在最下方可见`Unlock frame rate limit`选项
    - 在右侧点击`开启或关闭`按钮，所显示的`Disable`或`Enable`分别代表`已禁用`或`已启用`该功能
    - 在下方的`Set frame rate`选项中，可自由拖动拉杆，调整到您需要设置的最高帧率上限

- 会导致**解锁帧率上限失败**的因素：
    - 解锁帧率上限，需要保持**胡桃工具箱**在开启状态
    - 游戏内未关闭**垂直同步**选项
    - 在显卡驱动中存在`最大帧速率`的设置
    - 在显卡驱动软件内存在未关闭的类似于`节能模式`的选项
