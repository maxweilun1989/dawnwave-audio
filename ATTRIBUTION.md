# Dawn W2 音频资产来源与许可

> 生成日期：2026-11-13。配套清单：`docs/audio-prompts-W2.md`。
> 素材均为「下载源素材 + 脚本后处理（循环化 / 渐强包络 / 响度归一 / CAF）」产出，
> 管线脚本：`dawn-audio/process.py`（工作区快照）。

## 一、商用免署名（Mixkit License）

Mixkit License：免费商用、无需署名、可修改。
来源：https://mixkit.co/free-sound-effects/

| 资产 | Mixkit ID | 原始名称 |
|---|---|---|
| birds (ramp/steady) | 2472 | Morning birds |
| bell (ramp/steady) | 3109 | Relaxing bell chime |
| rain-light | 2474 | Light rain atmosphere |
| rain-heavy | 1262 | Heavy rain ambience |
| fan | 1813 | Stove extractor fan |
| waves | 1195 | Close sea waves loop |
| stream | 2454 | River water flowing |
| forest-night | 2414 | Night forest with insects |
| wind | 2427 | Breeze through the trees |

## 二、需要署名（Wikimedia Commons）

**⚠️ 以下两个文件发布 App 时必须在「关于/设置」页加入署名信息。**

### bowl（bowl-ramp-* / bowl-steady）

- 文件：Tibetan Singing Bowl hit 11inch.flac
- 来源：https://commons.wikimedia.org/wiki/File:Tibetan_Singing_Bowl_hit_11inch.flac
- 作者：דג בלי מלח (commons user)
- 许可：**CC BY-SA 4.0** — https://creativecommons.org/licenses/by-sa/4.0
- 注意 ShareAlike 条款：修改后的音频（本管线做了裁切/循环/包络）需以同协议发布衍生文件。
  若介意，可换 CC0 素材重跑管线（`process.py` 改一行映射即可）。

### piano（piano-ramp-* / piano-steady）

- 文件：68448 pinkyfinger Piano G.ogg
- 作者：pinkyfinger（freesound.org）
- 原始：https://freesound.org/people/pinkyfinger/sounds/68448/
- 许可：**CC BY 2.5** — https://creativecommons.org/licenses/by/2.5

## 三、纯合成（无第三方权利）

- brown-noise：FFT 周期化滤波噪声，脚本内合成。
