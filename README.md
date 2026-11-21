# 配置文件图标库

代理软件（Quantumult X、Surge、Loon、Egern、Stash 等）配置文件图标订阅合集。把下面任意一个订阅链接填到代理软件的图标订阅里，就能给配置文件、订阅、策略组换上对应的一套图标。

## 图标列表

### Qure 系列（作者：Koolson）

| 图标集 | 风格 / 说明 | 图标数 | 订阅链接 |
|---|---|---|---|
| Qure mini | 迷你透明主题，适合做订阅图标 | 347 | https://raw.githubusercontent.com/lzr52o/ConfigIconLibrary/master/Quremini.json |
| Qure Color（全部） | 彩色主题 · 所有图标 | 310 | https://raw.githubusercontent.com/lzr52o/ConfigIconLibrary/master/QureColor-All.json |
| Qure Color（默认） | 彩色主题 · 默认 | 15 | https://raw.githubusercontent.com/lzr52o/ConfigIconLibrary/master/QureColor-Default.json |
| Qure Color（常用） | 彩色主题 · 常用 | 12 | https://raw.githubusercontent.com/lzr52o/ConfigIconLibrary/master/QureColor-Common.json |
| Qure Color（应用与游戏） | 彩色主题 · 应用与游戏 | 41 | https://raw.githubusercontent.com/lzr52o/ConfigIconLibrary/master/QureColor-AppGame.json |
| Qure Color（服务） | 彩色主题 · 服务 | 16 | https://raw.githubusercontent.com/lzr52o/ConfigIconLibrary/master/QureColor-Service.json |
| Qure Color（其它） | 彩色主题 · 其它 | 47 | https://raw.githubusercontent.com/lzr52o/ConfigIconLibrary/master/QureColor-Other.json |
| Qure Color（地区） | 彩色主题 · 地区 | 56 | https://raw.githubusercontent.com/lzr52o/ConfigIconLibrary/master/QureColor-Area.json |
| Qure Color（流媒体） | 彩色主题 · 流媒体 | 99 | https://raw.githubusercontent.com/lzr52o/ConfigIconLibrary/master/QureColor-Media.json |
| Qure Color（服务器） | 彩色主题 · 服务器 | 9 | https://raw.githubusercontent.com/lzr52o/ConfigIconLibrary/master/QureColor-Server.json |
| Qure Color（禁止） | 彩色主题 · 禁止 | 4 | https://raw.githubusercontent.com/lzr52o/ConfigIconLibrary/master/QureColor-Inhibition.json |
| Qure Light（全部） | 浅色主题 · 所有图标 | 319 | https://raw.githubusercontent.com/lzr52o/ConfigIconLibrary/master/QureLight-All.json |

原地址（Koolson/Qure）：https://github.com/Koolson/Qure

### 其他作者

| 图标集 | 作者 | 风格 / 说明 | 图标数 | 订阅链接 |
|---|---|---|---|---|
| mini icons | Orz-3 | 迷你图标，含机场订阅、Task、地区、策略组图标 | 86 | https://raw.githubusercontent.com/lzr52o/ConfigIconLibrary/master/mini.json |
| Hand Painted Icon | Semporia | 手绘风 | 379 | https://raw.githubusercontent.com/lzr52o/ConfigIconLibrary/master/Semporia.json |
| Cute | tugepaopao | 可爱风，陆续更新中 | 125 | https://raw.githubusercontent.com/lzr52o/ConfigIconLibrary/master/Cute.json |
| Catcat | Yuanxsxs | 猫咪主题 | 41 | https://raw.githubusercontent.com/lzr52o/ConfigIconLibrary/master/Catcat.json |
| 拿她练技术 | LovedGM | 练手作品 | 40 | https://raw.githubusercontent.com/lzr52o/ConfigIconLibrary/master/zishi-cs.json |
| Attack on Titan | Toperlock | 进击的巨人主题 | 84 | https://raw.githubusercontent.com/lzr52o/ConfigIconLibrary/master/AOT-icons.json |
| Package Name | crossutility | 示例（仅 3 个图标） | 3 | https://raw.githubusercontent.com/lzr52o/ConfigIconLibrary/master/icon-gallery.json |

原地址：
- Orz-3/mini：https://raw.githubusercontent.com/Orz-3/mini/master/mini.json
- Semporia/Hand-Painted-icon：https://raw.githubusercontent.com/Semporia/Hand-Painted-icon/master/Semporia.json
- tugepaopao/Image-Storage：https://raw.githubusercontent.com/tugepaopao/Image-Storage/master/other/Cute.json
- Yuanxsxs/QtumultX：https://raw.githubusercontent.com/Yuanxsxs/QtumultX/master/Icon/Catcat.json
- LovedGM/Quantumult-X-TuBiao：https://raw.githubusercontent.com/LovedGM/Quantumult-X-TuBiao/main/zishi-cs.json
- Toperlock/Quantumult：https://raw.githubusercontent.com/Toperlock/Quantumult/main/AOT-icons.json
- crossutility/Quantumult-X：https://raw.githubusercontent.com/crossutility/Quantumult-X/master/icon-gallery.json

## 使用教程

### 第一步：订阅图标库

复制上面想要的那套图标的「订阅链接」，在代理软件的图标订阅（图标库）里添加，App 就会拉取整套图标，之后在换图标时直接从里面挑。

- Quantumult X：在图标订阅处添加订阅链接。
- Loon：在图标订阅处添加订阅链接。
- Surge / Egern / Stash：在图标订阅或图标库入口添加订阅链接（各 App 入口位置略有不同，一般都在设置或配置文件相关页面）。

### 给配置文件换图标

订阅好图标库后，在 App 里打开配置文件（或长按配置文件），在图标一栏从已订阅的图标库里选一个，保存即可。不同 App 的入口略有不同，一般都在配置文件的设置或长按菜单里。

### 给订阅、策略组换图标

#### Quantumult X

**订阅图标（文本编辑）：**打开配置文件编辑，找到 `[server_remote]`，在想加图标的订阅那行、`enabled=true` 之前加上 `img-url=图标地址`，前后用英文逗号隔开、逗号后空一格。

完整示例：`https://example.com/sub.txt, tag=订阅名, img-url=https://raw.githubusercontent.com/lzr52o/ConfigIconLibrary/master/Quremini.json, enabled=true`

**策略组图标：**
- 界面操作：长按想改图标的策略组，选编辑，在图标一栏填图标地址。
- 文本编辑：打开配置文件编辑，找到 `[policy]`，在想改的策略那段、`enabled=true` 之前加上 `img-url=图标地址`，前后用英文逗号隔开、逗号后空一格。

#### Loon

**界面操作：**点下方「策略」选项卡，长按想改图标的订阅或策略组，在图标一栏填图标地址。

**文本编辑：**打开配置选项卡，点编辑 → 文本编辑，找到 `[Remote Proxy]` / `[Proxy Group]`，在想改的那段加上 `img-url=图标地址`，与前句用英文逗号隔开。

#### Surge / Egern / Stash

在图标订阅处添加本库链接后，在配置文件、订阅或策略组的图标设置里从图标库中选择即可，具体入口以各 App 当前版本为准。

### 单个图标直链（img-url）

如果只想用某一个图标，不用订阅整套，可以直接用图标的 PNG 直链，填到 `img-url=` 后面。图标 PNG 地址一般在原作者仓库里，按图标名拼出来，例如 Qure 的图标在 `https://raw.githubusercontent.com/Koolson/Qure/master/Other/` 目录下。注意把 `name.png` 换成实际文件名。

## 免责声明

1. 本库内所涉及图标、LOGO 仅为资源共享、学习参考之目的，不保证其合法性、正当性、准确性；切勿使用本库做任何商业用途或牟利；
2. 遵循避风港原则，若有图片和内容侵权，请在 Issues 告知，核实后删除，其版权均归原作者及其网站所有；
3. 本人不对任何内容承担任何责任，包括但不限于任何内容错误导致的任何损失、损害；
4. 其它人通过任何方式登陆本网站或直接、间接使用本库相关资源，均应仔细阅读本声明，一旦使用、转载本库任何相关教程或资源，即被视为您已接受此免责声明。
5. 转载请注明出处，谢谢！

## 说明

- 共 19 套配置文件图标，文件都在本仓库根目录。
- 图标文件来自各作者原仓库，版权归原作者所有；仅作订阅收集。
- `zishi-cs.json` 原文件末尾多一个逗号（JSON 不规范），已顺手修掉，图标内容不变。
