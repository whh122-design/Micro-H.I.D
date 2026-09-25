# SCP: Secret Laboratory - Micro H.I.D

[![Minecraft](https://img.shields.io/badge/Minecraft-26.2-blue)](https://minecraft.net/)
[![Fabric](https://img.shields.io/badge/Fabric%20Loader-%3E%3D0.19.3-blue)](https://fabricmc.net/)

> 为 Minecraft 26.2 制作的 Fabric 模组，复刻《SCP: Secret Laboratory》中的标志性武器 **Micro H.I.D**（重型电击炮）。
> A Fabric mod for Minecraft 26.2 that recreates the iconic **Micro H.I.D** weapon from *SCP: Secret Laboratory*.

---

## 功能特性 / Features

- **微型 H.I.D 武器** —— 一把可蓄能的重型电击炮，拥有轻/重两种攻击模式。
- **随机 H.I.D 房间** —— 世界生成时会像掠夺者前哨站一样生成 H.I.D 房间，内有武器箱。
- **轻攻击** —— 按住左键蓄力 2 秒，随后自动释放 3 秒电击光束（30 伤害/秒，2 能量/秒）。
- **重攻击** —— 按住右键蓄力 7 秒，蓄满后按左键发射 6 秒强力光束（400 伤害/秒，5 能量/秒）；发射中再次按左键可提前停止。
- **移动射击** —— 蓄力与发射期间均可自由移动。
- **能量与自动冷却** —— 能量 0–100，耗尽后进入 30 秒冷却，冷却结束后自动回满至 100。
- **音效与特效** —— 使用 SCP:SL 原版音效；光束与电火花从电炮前部射出。
- **无近战挥拳** —— 手持电炮时左键不再触发原版近战攻击动画。

---

## 安装要求 / Requirements

- Minecraft **26.2**
- Fabric Loader **≥ 0.19.3**
- Fabric API **0.155.2+26.2** 或更高
- Java **≥ 25**

将 `scpsl-microhid-*.jar` 放入 `.minecraft/mods` 即可。

Drop the `scpsl-microhid-*.jar` into `.minecraft/mods`.

---

## 操作说明 / Controls

| 按键 | 中文说明 | English |
|---|---|---|
| 左键按住 | 轻蓄力，蓄满自动开火 | Hold to light-charge; fires automatically when charged |
| 右键按住 | 重蓄力，蓄满后不自动发射 | Hold to heavy-charge; does **not** auto-fire when full |
| 左键（重蓄满后）| 开始重攻击 | Start heavy attack after heavy charge is full |
| 左键（重攻击中）| 停止重攻击 | Stop heavy attack early |
| 移动键 | 蓄力/开火期间均可移动 | Movement allowed while charging/firing |

能量条显示在屏幕右下角。
The energy bar is shown at the bottom-right of the screen.

---

## 成就 / Advancement

- **控制，收容，保护** —— 在一次电炮重蓄攻击（重攻击光束期间）连续击杀至少 3 只监守者。
- **Control. Contain. Protect.** —— Kill at least 3 Wardens during a single heavy H.I.D beam.

---

## 授权 / License

本模组采用 MIT 协议发布。
This mod is released under the MIT License.

武器模型、音效与视觉效果经授权引用自 SCP:SL 相关资源。
Weapon model, sounds and visual effects are used with authorization from SCP:SL-related resources.

作者 / Author: CyberQuQu Dev
