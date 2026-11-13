# 卡罗莉娜表情包 · Caroline Stickers

《女神异闻录 5 / Persona 5》卡罗莉娜非官方同人表情包，使用 EmoteLab 制作。**v1.1.0：替换旧版五张基础包，现有 143 张动态 GIF，按 22 个聊天语义类别整理，另附 2 张静态 PNG 参考图。**

![分类预览](previews/overview.webp)

## 下载和安装

**[下载 v1.1.0 分类完整包](downloads/caroline-stickers-1.1.0.zip?raw=true)**

在 AstrBot Meme Manager 的“导入与备份”中选择 ZIP；导入摘要应为 **22 类、143 张表情**。也可从本仓库安装，来源为 `Yamabuki-Kirio/caroline-p5-stickers@main`，包 ID 为 `caroline-p5-stickers`。

已经安装旧包时，请通过插件的包更新流程替换；若手动导入会合并分类，先备份并移除旧版五张素材，避免残留。

包含可复用中文描述和标签，不分发本机向量。安装后按当前向量模型重建索引。`masters/` 的 2 张 PNG 是参考图，不计入自动选图。

## 情绪与用途分类

| 目录 | 中文用途 | GIF 数量 |
| --- | --- | ---: |
| `happy` | 开心庆祝 | 6 |
| `cheer` | 应援赞同 | 7 |
| `affection` | 喜欢亲昵 | 14 |
| `shy` | 害羞脸红 | 6 |
| `teasing` | 调侃玩梗 | 3 |
| `cool` | 得意耍帅 | 7 |
| `angry` | 生气抗议 | 13 |
| `refusal` | 拒绝禁止 | 6 |
| `sad` | 难过委屈 | 9 |
| `panic` | 紧张慌张 | 9 |
| `surprised` | 惊讶意外 | 1 |
| `confused` | 疑惑思考 | 4 |
| `dazed` | 宕机头晕 | 3 |
| `sleep` | 困倦休息 | 6 |
| `work` | 工作学习 | 9 |
| `chill` | 放松充电 | 4 |
| `fun` | 娱乐舞蹈 | 11 |
| `food` | 饮食投喂 | 11 |
| `money` | 金钱打赏 | 5 |
| `greeting` | 招呼上线 | 4 |
| `peek` | 偷看围观 | 1 |
| `reply` | 普通回应 | 4 |

每张 GIF 只有一个主分类，细节由逐图描述和标签补充。例如“生气工作”归生气，“疲倦工作”归困倦，“普通工作”归工作，避免同一图片重复分发。

分类名参考 [魔理沙表情包](https://github.com/liquidtoy001/astrbot-meme-pack-marisa/tree/v1.0.0) 和 [永雏塔菲表情包](https://github.com/flybode/yctf-taffy-meme-pack)，语义文件结构参考 [和泉妃爱表情包](https://github.com/NooAcc/astrbot-meme-IzumiHiyori)。未复制这些仓库的成品图片或授权声明。

## 素材与检查

- 全部素材来自维护者提供的新 ZIP；原始图像字节与中文文件名保留，未缩放、重编码或补帧。
- `classification.csv` / `classification.json`：逐图分类、描述、原路径、规格与 SHA-256。部分导出文件名与画面不符，修正说明单独列出。
- `semantic_metadata.json`：143 条路径级中文语义记录；分类根据动作名称和 GIF 中间帧整理，未标记为用户人工确认；不包含向量。
- `validation.json` / `checksums.json`：全帧解码、文件覆盖和哈希检查。
- 已离线检查素材和 ZIP；尚未在实际 AstrBot 实例验证安装、索引重建与聊天发送。

## 来源与权利

角色归 ATLUS 等相关权利人；基础模型画师为 0x4682B4（失效药片），模型与动画来自 EmoteLab。维护者提供本次导出素材。完整背景见 [SOURCES.md](SOURCES.md)。

非官方同人，未取得商业授权。其他参考包的 MIT、CC 等协议不适用于本包素材；基础资产遵循 EmoteLab 使用条款，不额外授予商业使用权。仓库不含 EmoteLab 软件、骨架或图集。
