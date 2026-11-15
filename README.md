<div align="center">

<img src="https://raw.githubusercontent.com/dex-ovo-studio/DEX-Rider/main/assets/banner.svg" alt="Rovelio — D.E.X Studio" width="100%">

# Rovelio · 驭途
**摩托车智能座舱 · Motorcycle dashboard & voice interaction**

Raspberry Pi · **Rebuild 01** · 开发原型 / Development prototype

[开发状态 / Development status](https://github.com/dex-ovo-studio/DEX-Rider/blob/main/STATUS.md) · [项目目录 / Project directory](https://github.com/dex-ovo-studio/DEX-Studio-Software-Status)

</div>

---

## 项目介绍 · Overview

**Rovelio（驭途）是 D.E.X Studio 旗下的车机项目。**  
**Rovelio is a motorcycle dashboard project by D.E.X Studio.**

Rovelio 是面向摩托车场景的车机原型，探索音乐、位置、地图与“戴克”语音交互。界面以 720 × 720 布局为基础，保留 D.E.X 的橙色视觉元素。

Rovelio is a motorcycle dashboard prototype exploring music, location, maps and the “戴克” voice assistant. Its interface uses a 720 × 720 layout with D.E.X orange accents.

## 版本与下载 · Releases & downloads

**Rebuild 01 · 开发原型 / Development prototype**

目前没有公开安装包或车机镜像，公开发行时间尚未确定。请通过[项目状态](https://github.com/dex-ovo-studio/DEX-Rider/blob/main/STATUS.md)了解开发进度。  
No public installer or device image is available, and no public release date is set. Follow the [project status](https://github.com/dex-ovo-studio/DEX-Rider/blob/main/STATUS.md) for development progress.

## 功能与进展 · Features & progress

以下根据 **2026-09-06 的开发对话与设备反馈**整理，当前设备状态尚未重新验收。  
Based on the **2026-09-06 development conversation and device feedback**. The current device has not been revalidated.

| 模块 / Area | 进展 / Progress |
| :--- | :--- |
| 界面 / Interface | Rebuild 01 已运行，重做位置、天气、音乐卡片 / Rebuild 01 ran with redesigned location, weather and music cards |
| 音乐 / Music | 设备反馈确认车机音乐可播放出声 / Device feedback confirmed audible music playback |
| GPS 与地图 / GPS & maps | 已有诊断、地图搜索与路线预览代码；完整设备验收待补 / Diagnostics, search and route-preview code exists; full device validation remains pending |
| 语音 / Voice | 手动唤醒下，已验证识别报时指令并播放回答 / Manual activation demonstrated time-query recognition and spoken replies |
| 自动唤醒 / Wake word | “戴克戴克”识别仍有漏唤醒与误识别问题 / Wake-word recognition still has missed detections and recognition errors |

### 下一阶段 · Next milestones

1. 提升专用关键词唤醒的可靠性。Improve dedicated wake-word detection.
2. 分别验证语音指令、地图与设备交互。Validate voice commands, maps and hardware interactions separately.
3. 补全真实环境测试与安装说明。Complete real-world testing and installation documentation.

音乐、导航、天气的语音控制仍未完成，不能将界面入口视为已打通的语音功能。  
Voice control for music, navigation and weather remains incomplete; visible interface entries do not imply working voice integration.

## 文档与支持 · Docs & support

目前仅公开项目介绍与开发状态，尚无公开安装包或车机镜像。`docs/` 为后续公开文档预留。  
This repository currently publishes the overview and development status. No public installer or device image is available; `docs/` is reserved for future documentation.

<div align="center">

<sub>[D.E.X Studio](https://github.com/dex-ovo-studio) · [软件目录 / Software directory](https://github.com/dex-ovo-studio/DEX-Studio-Software-Status)</sub>

</div>
