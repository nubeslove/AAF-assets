# 外部素材登记

## 2026-10-05 泰拉战斗特效

已收集 [Kenney Particle Pack](https://kenney.nl/assets/particle-pack) 的 CC0 原包，并在 28 个原创程序动画中使用四张透明烟尘／火花／光晕贴图。稳定 ID、36 项技艺搭配预案、原包哈希、原始许可与运行时着色说明见 [特效库](fx/terra/README.md) 和 [逐项来源](fx/terra/LICENSES.md)。仅接入素材图鉴，尚未绑定世界能力；未使用原作拆包动画。

## 2026-09-28 DND 晨光图册 UI

`public/presentation/dnd-dawn.svg` 大厅横幅、`src/tabletop/dnd/icons.tsx` 导航图标均为本项目原创矢量；没有复制 BG3/FVTT 原作资产。源文件、规格和用途见 [DND 美术说明](ui/dnd-dawn/README.md)。本轮未新增外部图片、字体或音轨。

## 2026-09-26 LANCER 三维场景

- 47 个原创 GLB（29 骨架代用模型、6 通用单位、12 地形）：本项目程序建模，CC0；不是官方雕塑，不改变原作名称与设定权利。源与复现见 [三维素材说明](3d/lancer-kit/README.md)。
- 14 个 Kenney City Kit Industrial 2.0 GLB：[官方来源](https://kenney.nl/assets/city-kit-industrial)，CC0；允许个人/教育/商业使用，署名不强制。下载日期 2026-09-26，只将调色贴图内嵌；随客户端保留 `public/assets/3d/lancer-kit/Kenney-License.txt` 和 `CREDITS.txt`。
- 已在实际 Three.js 场景检查风格、尺度、贴图与可辨识轮廓；定位低面数桌面棋子。逐文件验证自包含 GLB、面数预算。FVTT、Retrograde、Quaternius 仅作研究，本次未复制其模型或实现。

## 2026-09-24 晨光 UI 交互样机

新增 [晨光 UI 素材库](ui/dawn-atelier/README.md)：11 类原创矢量/PNG 皮肤，Kenney CC0 图片 10 张、音效 6 个，复用此前许可库中的 Lorc 24 枚 / Ravenmore 6 枚图标。用于开发样机，未替换正式大厅。原 ZIP、许可、下载哈希、处理说明与随包署名完整保留，见 [逐项授权](ui/dawn-atelier/LICENSES.md)。本轮没有新生成 AI 彩绘图标或收集参考游戏的专有素材。

同日大厅修订新增 8 类原创终端面板、指南针与导航符号（SVG＋PNG），运行时合计 84 文件。参考《明日方舟》的信息分区，不使用其专有贴图或图标。

## 2026-09-14 第二轮图标备用库（当前）

用户否定上一批 AI 彩绘的画风后，改收 **Ravenmore 手绘 PNG 39 枚 + Lorc 矢量图标 71 枚，共 110 个条目**。两系列均为免费 CC BY 3.0，需作者署名；来源、许可、修改说明和原图哈希均保留。见 [当前图册](icons/handcrafted/index.html)、[使用说明](icons/handcrafted/README.md)、[授权](icons/handcrafted/LICENSES.md) 与 [随包署名](icons/handcrafted/CREDITS.txt)。未使用生成式 AI 生成本轮图标，未纳入参考游戏原作素材，未接入运行时。画风待用户审阅。

## 2026-09-14 第一轮图标库（已停止推荐，历史）

原 596 枚 PNG 与来源记录保留为历史；其中 Fantasy RPG Core 彩绘 396 枚被用户否定，不能再作为默认候选或成品接入。Skymon 200 枚也不自动混入新图册。旧授权记录仍见 [逐包授权](icons/LICENSES.md)。旧库入口已转向上面的第二轮库，没有删除既有原文件。

## 2026-09-13 已接入的大厅演出素材

- 用户提供的启动动画：原站 `client/src/assets/auth/logoae.gif` → `game/apps/desktop/public/presentation/logo-intro.gif`，137 帧、约 4.11 秒；原文件不变。
- 两张 imagegen 新绘制背景：`bg/dawn-harbor.png`、`bg/meadow-journey.png`；各自 `.prompt.md` 保留生成提示与用途。运行时使用 WebP，仅装饰用途，不确定世界设定。
- 两首 PeriTune 2024 年音乐与五种原创合成音效：见 [音频授权登记](audio/LICENSES.md)。随客户端保留 `public/presentation/CREDITS.txt` 和设置内署名。
- 七枚导航徽记及流云/光点均为本项目 SVG/CSS 实现，不使用第三方图标素材包。

## 2026-09-05 原型素材（历史）

检索/下载日期：2026-09-05。vendor 中保留官方原包，不修改原图；尚未运行时接入或对外发布。

| ID | 作者 | 来源 | 本地目录 | 授权证据 | 状态 |
| --- | --- | --- | --- | --- | --- |
| kenney-tiny-dungeon | Kenney | https://kenney.nl/assets/tiny-dungeon | vendor/kenney-tiny-dungeon | 原包 License.txt：CC0，允许个人/教育/商业使用；署名非强制 | 已下载，预览审阅通过（小型像素风原型库） |
| kenney-tiny-town | Kenney | https://kenney.nl/assets/tiny-town | vendor/kenney-tiny-town | 原包 License.txt：CC0，允许个人/教育/商业使用；署名非强制 | 已下载，待独立场景拼接验收 |

CC0 文本：https://creativecommons.org/publicdomain/zero/1.0/

Time Fantasy / 1000+ Icons / Animals、Mini World 为检索候选，未购买或下载；详情见素材选型文档。禁止将候选状态当作已持有的素材授权。


## 2026-10-06 行于泰拉官方美术

按用户明确要求引入明日方舟官网公开的 8 张插画与 17 套干员立绘/时装。© HYPERGRYPH，非 CC0；当前为本机预览，未宣称获得独立再发行授权。完整来源、指纹与边界见 [专用来源记录](ui/terra-official/LICENSES.md)。新增 37 枚档案徽记为项目原创 SVG。


## 2026-10-06 行于泰拉完整衣装快照与动态模型

按用户要求扩充为 431 干员／形态、1347 立绘衣装条目，其中 520 套命名时装，96 套 Spine 动态；资料快照 2026-09-29，缺件为零。© HYPERGRYPH 及相应权利人；未宣称取得原作素材再发行授权。PixiJS 的 MIT 与 Spine Runtimes 的独立许可分别保留。固定版本、逐文件指纹及原生发行前授权边界见 [专用来源台账](ui/terra-wardrobe/LICENSES.md)。
