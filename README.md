# 共坠群星 · 官方可选素材库

软件本身自带底层规则与必需资源；这里放的是**可选**的官方素材包，GM 或玩家需要哪一套就下哪一套。

**只读下载，不需要账号。** 仓库根目录的 `index.json` 是唯一入口，客户端按它取包、校验散列、本地缓存。

## 结构

```
index.json                     索引：包 ID、体积、许可、运行时目标路径、逐文件散列
packs/<规则>/<包名>/...         包内容，每个包自带 LICENSE.md
```

包的 ID 按**规则**分层（如 `lancer/lancer-kit`），不同规则不会混到同一目录。

## 当前的包

| 包 | 规则 | 体积 | 许可 |
| --- | --- | --- | --- |
| `lancer/lancer-kit` | LANCER | 14.6 MiB | CC0（自建模型与地形、Kenney 工业素材） |
| `lancer/forge-mechs` | LANCER | 45.6 MiB | CC0 1.0 · Ramon Linares |

## 这个仓库不放什么

- **GM 自己上传的世界素材**。它们属于单个世界，走部署者配置的私有存储网关（游戏服务器签发短时许可 → Worker/R2），其他玩家按世界访问权限下载。GM 和玩家都不需要本仓库或任何对象存储的账号。
- 世界数据、私密手记、未公布台本、作者规则原稿、账号与凭据。

## 重新生成

包内容由源仓库的 `game/scripts/build-asset-packs.mjs` 生成，不手工编辑：

```
node game/scripts/build-asset-packs.mjs          # 输出到 AAF_PACK_OUT，默认 E:/project/AAF-assets
```

新增包需要在脚本的 `PACKS` 列表登记源目录、规则归属、许可与运行时目标路径，并附许可证文件。
