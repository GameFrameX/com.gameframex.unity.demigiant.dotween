<div align="center">
  <img src="https://download.alianblank.com/gameframex/gameframex_logo_320.png" alt="Game Frame X Logo" width="160" />
</div>

# Game Frame X DOTween

[![GitHub release](https://img.shields.io/github/v/release/GameFrameX/com.gameframex.unity.demigiant.dotween?style=flat-square)](https://github.com/GameFrameX/com.gameframex.unity.demigiant.dotween/releases)
[![License](https://img.shields.io/github/license/GameFrameX/com.gameframex.unity.demigiant.dotween?style=flat-square)](https://github.com/GameFrameX/com.gameframex.unity.demigiant.dotween/blob/main/LICENSE.md)
[![Documentation](https://img.shields.io/badge/Documentation-Online-blue?style=flat-square)](https://gameframex.doc.alianblank.com)

**独立游戏前后端一体化解决方案 · 独立游戏开发者的圆梦大使**

[文档](https://gameframex.doc.alianblank.com) · [快速开始](#快速开始) · [QQ群](https://qm.qq.com/q/5s5e1e6e6e)

**语言**: [English](README.md) | **简体中文** | [繁體中文](README.zh-TW.md) | [日本語](README.ja.md) | [한국어](README.ko.md)

---

## 项目简介

Game Frame X DOTween 是 [DOTween](http://dotween.demigiant.com) 的 GameFrameX 框架集成包。DOTween 是一个 Unity 动画插件，用于创建补间动画。

该库主要服务于 [GameFrameX](https://github.com/AlianBlank/GameFrameX) 作为子库使用。

## 改动功能

1. 增加 `link.xml` 的裁剪过滤

## 快速开始

### 系统要求

- Unity 2018.4 或更高版本

### 安装

任选以下方式之一：

1. 直接在 `manifest.json` 文件中添加以下内容：
   ```json
   {"com.gameframex.unity.demigiant.dotween": "https://github.com/AlianBlank/com.gameframex.unity.demigiant.dotween.git"}
   ```

2. 在 Unity 的 `Packages Manager` 中使用 `Git URL` 的方式添加库，地址为：
   ```
   https://github.com/AlianBlank/com.gameframex.unity.demigiant.dotween.git
   ```

3. 直接下载仓库放置到 Unity 项目的 `Packages` 目录下，会自动加载识别。

## 使用方法

- 导入后，从 "Tools/Demigiant" 菜单中选择 DOTween 的 Utility Panel，按下 "Setup DOTween..." 按钮来激活/停用模块。
- 在代码中，在每个需要使用 DOTween 的类中添加 `using DG.Tweening`。

## 文档与资源

- DOTween 文档: http://dotween.demigiant.com/documentation.php
- DOTween 许可证: http://dotween.demigiant.com/license.php
- GameFrameX 文档: https://gameframex.doc.alianblank.com
- 仓库地址: https://github.com/GameFrameX/com.gameframex.unity.demigiant.dotween
- 问题反馈: https://github.com/GameFrameX/com.gameframex.unity.demigiant.dotween/issues

## 开源协议

DOTween 和 DOTween Pro 版权所有 (c) 2014-2018 Daniele Giardini - Demigiant。详细信息请查看 [LICENSE](LICENSE.md) 文件。
