# 不寐仿宋 Insomnia FangSong

一款开源的**仿宋体**（日文称「宋朝体」）。以 **HZ 宋朝** 为基底，
补齐简体中文缺字，并把全部 GB2312 汉字改为**大陆国标（G 源 / 新字形）字形**。

> 这款字体创作于我失眠之时，故名「不寐仿宋」。

<img width="1677" height="938" alt="不寐仿宋演示图" src="https://github.com/user-attachments/assets/5b295c03-0d24-4c2d-8027-1f6f3dbd235b" />


## 简介

[HZ 宋朝/HZ Socho](https://github.com/MihailJP/minchovariant) 是由 [字形维基（GlyphWiki）](https://glyphwiki.org) 的汉字数据生成的开源仿宋体（宋朝体）。其汉字以**日本字形**为准，不符合中国大陆书写规范。

《不寐仿宋》在保留其仿宋风格的基础上，把简体中文部分 GB 化：凡与大陆字形不同的汉字，一律改用字形维基的 G 源数据重新生成。

## 字体特性

- **全 GB2312 大陆字形**：HZ 宋朝自带的约 3100 个日式（JIS）汉字已改为大陆简体标准，另补齐 2238 个缺失的简体字；GB2312 一二级共 6763 字全部为国标字形。
- **三字重**：Book / Demi / Bold（见下表）。
- **支持竖排**：保留 `vhea` / `vmtx` 与 GSUB `vert` / `vrt2`，竖排度量已校正。
- **兼容性好**：TrueType（glyf）轮廓、非 CID 结构，可在 CorelDRAW 等软件正常显示中文。
- **补上间隔号 ·**：HZ 宋朝缺 `·`（U+00B7）与 `‧`（U+2027）；已用字体自带的仿宋中点补齐，随字重自动变粗。
- 其余非汉字（拉丁 / 希腊 / 西里尔 / 假名 / 符号 / 标点）沿用 HZ 宋朝，未改动。

### 字重

| 字重 | 字重值（usWeightClass） |
|---|---|
| Book | 400 |
| Demi | 600 |
| Bold | 700 |

### 演示
<img width="2043" height="2627" alt="横排" src="https://github.com/user-attachments/assets/f006a5a3-3b7a-4830-955c-17dc7918011a" />


<img width="1998" height="2031" alt="竖排" src="https://github.com/user-attachments/assets/b77189b3-8903-4b06-8cbd-d75831eb7ce9" />




### 开源许可列表

本字体依 **X11 许可（带字体嵌入例外）** 及下列自由条款发布。完整条款与全部声明见仓库中的 [`LICENSE`](LICENSE) 文件。

| 组成部分 | 来源 | 许可协议 |
|---|---|---|
| 汉字字形数据 | [字形维基 GlyphWiki](https://glyphwiki.org) | GlyphWiki 自由许可（可任意使用、复制、修改、再分发，含商业用途） |
| 拉丁 / 希腊 / 西里尔 | Computer Modern Unicode | **X11 许可**（带字体嵌入例外） |
| 部分符号 | M+ fonts / GL-Antique | 自由许可（可任意使用、复制、分发） |
| 构建工具 | [KAGE engine](https://github.com/MihailJP/kage-engine) / Potrace | GPL-3.0 / GPL-2.0+（**仅作为构建工具，其代码不包含在字体文件中**） |

总体而言，本字体依 **X11 许可（带字体嵌入例外）** 及上述自由条款发布，**不受 GPL 约束**。  
KAGE 引擎与 Potrace 仅用于生成轮廓，字体文件本身并不包含其代码。（以上为对上游条款的善意理解，不构成法律意见；HZ 宋朝亦采用类似方式生成，并以 X11 许可发布。）

### ✅ 允许

- 一切商业与非商业使用；
- 转载、分享字体文件；
- 将字体嵌入文档、软件、图片、视频等；
- 修改字体、制作衍生版本（衍生版须同样保留上述全部上游许可与声明）。

### ⛔ 不允许

- 在衍生字体的**名称**中使用「不寐」「Insomnia」等字样（保留名称）。

> 本字体不作任何担保，使用风险由使用者自行承担。请在遵守当地法律法规的前提下使用。

## 致谢

- [HZ 宋朝/HZ Socho](https://github.com/MihailJP/minchovariant) — MihailJP（基底字体）
- [字形维基 GlyphWiki](https://glyphwiki.org) — 提供汉字数据，及其贡献者
- [KAGE engine](https://github.com/MihailJP/kage-engine) — 字形渲染引擎（构建工具）
- Computer Modern Unicode — Andrey V. Panov（拉丁 / 希腊 / 西里尔）
- M+ fonts — Coji Morishita；GL-Antique（部分符号）
- [飞花宋体 FlyFlowerSong](https://github.com/Skr-ZERO/FlyFlowerSong) — 本 README 的排版结构参考了该项目；标点方案亦与其做过对照。**未使用飞花宋体的任何字形数据。**


---
*Insomnia FangSong（不寐仿宋）is an independent derivative and is not affiliated with
or endorsed by the authors of HZ Socho, GlyphWiki, or Computer Modern Unicode.*
