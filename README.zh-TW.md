<div align="center">
  <img src="https://download.alianblank.com/gameframex/gameframex_logo_320.png" alt="Game Frame X Logo" width="160" />
</div>

# Game Frame X DOTween

[![GitHub release](https://img.shields.io/github/v/release/GameFrameX/com.gameframex.unity.demigiant.dotween?style=flat-square)](https://github.com/GameFrameX/com.gameframex.unity.demigiant.dotween/releases)
[![License](https://img.shields.io/github/license/GameFrameX/com.gameframex.unity.demigiant.dotween?style=flat-square)](https://github.com/GameFrameX/com.gameframex.unity.demigiant.dotween/blob/main/LICENSE.md)
[![Documentation](https://img.shields.io/badge/Documentation-Online-blue?style=flat-square)](https://gameframex.doc.alianblank.com)

**獨立遊戲前後端一體化解決方案 · 獨立遊戲開發者的圓夢大使**

[文檔](https://gameframex.doc.alianblank.com) · [快速開始](#快速開始) · [QQ群](https://qm.qq.com/q/5s5e1e6e6e)

**語言**: [English](README.md) | [简体中文](README.zh-CN.md) | **繁體中文** | [日本語](README.ja.md) | [한국어](README.ko.md)

---

## 項目簡介

Game Frame X DOTween 是 [DOTween](http://dotween.demigiant.com) 的 GameFrameX 框架整合包。DOTween 是一個 Unity 動畫插件，用於建立補間動畫。

該庫主要服務於 [GameFrameX](https://github.com/AlianBlank/GameFrameX) 作為子庫使用。

## 改動功能

1. 增加 `link.xml` 的裁剪過濾

## 快速開始

### 系統需求

- Unity 2018.4 或更高版本

### 安裝

任選以下方式之一：

1. 直接在 `manifest.json` 檔案中添加以下內容：
   ```json
   {"com.gameframex.unity.demigiant.dotween": "https://github.com/AlianBlank/com.gameframex.unity.demigiant.dotween.git"}
   ```

2. 在 Unity 的 `Packages Manager` 中使用 `Git URL` 的方式添加庫，地址為：
   ```
   https://github.com/AlianBlank/com.gameframex.unity.demigiant.dotween.git
   ```

3. 直接下載倉庫放置到 Unity 專案的 `Packages` 目錄下，會自動載入識別。

## 使用方法

- 匯入後，從 "Tools/Demigiant" 選單中選擇 DOTween 的 Utility Panel，按下 "Setup DOTween..." 按鈕來啟用/停用模組。
- 在程式碼中，在每個需要使用 DOTween 的類別中添加 `using DG.Tweening`。

## 文檔與資源

- DOTween 文檔: http://dotween.demigiant.com/documentation.php
- DOTween 許可證: http://dotween.demigiant.com/license.php
- GameFrameX 文檔: https://gameframex.doc.alianblank.com
- 倉庫地址: https://github.com/GameFrameX/com.gameframex.unity.demigiant.dotween
- 問題回報: https://github.com/GameFrameX/com.gameframex.unity.demigiant.dotween/issues

## 開源協議

DOTween 和 DOTween Pro 版權所有 (c) 2014-2018 Daniele Giardini - Demigiant。詳細資訊請查看 [LICENSE](LICENSE.md) 檔案。
