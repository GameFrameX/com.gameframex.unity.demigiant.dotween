<div align="center">

<img src="https://download.alianblank.com/gameframex/gameframex_logo_320.png" alt="Game Frame X Logo" width="160" />

# Game Frame X DOTween

[![GitHub release](https://img.shields.io/github/v/release/GameFrameX/com.gameframex.unity.demigiant.dotween?style=flat-square)](https://github.com/GameFrameX/com.gameframex.unity.demigiant.dotween/releases)
[![License](https://img.shields.io/github/license/GameFrameX/com.gameframex.unity.demigiant.dotween?style=flat-square)](https://github.com/GameFrameX/com.gameframex.unity.demigiant.dotween/blob/main/LICENSE.md)
[![Documentation](https://img.shields.io/badge/Documentation-Online-blue?style=flat-square)](https://gameframex.doc.alianblank.com)

**インディゲーム開発者向けオールインワンソリューション · インディ開発者の夢を支援**

[ドキュメント](https://gameframex.doc.alianblank.com) · [クイックスタート](#クイックスタート) · [QQグループ](https://qm.qq.com/q/5s5e1e6e6e)

**言語**: [English](README.md) | [简体中文](README.zh-CN.md) | [繁體中文](README.zh-TW.md) | **日本語** | [한국어](README.ko.md)


</div>

---

## プロジェクト概要

Game Frame X DOTween は [DOTween](http://dotween.demigiant.com) の GameFrameX フレームワーク統合パッケージです。DOTween はトゥイーンアニメーション作成用の Unity アニメーションプラグインです。

このライブラリは主に [GameFrameX](https://github.com/AlianBlank/GameFrameX) のサブモジュールとして使用されます。

## 変更内容

1. `link.xml` ストリッピングフィルターを追加

## クイックスタート

### 動作環境

- Unity 2018.4 以上

### インストール

以下のいずれかの方法を選択してください：

1. プロジェクトの `manifest.json` ファイルに以下を追加：
   ```json
   {"com.gameframex.unity.demigiant.dotween": "https://github.com/AlianBlank/com.gameframex.unity.demigiant.dotween.git"}
   ```

2. Unity の Package Manager で `Git URL` を使用：
   ```
   https://github.com/AlianBlank/com.gameframex.unity.demigiant.dotween.git
   ```

3. リポジトリをダウンロードして Unity プロジェクトの `Packages` ディレクトリに配置。自動的にロードされます。

## 使用方法

- インポート後、"Tools/Demigiant" メニューから DOTween の Utility Panel を選択し、"Setup DOTween..." ボタンを押してモジュールの有効化/無効化を行います。
- コード内で DOTween を使用する各クラスに `using DG.Tweening` を追加します。

## ドキュメントとリソース

- DOTween ドキュメント: http://dotween.demigiant.com/documentation.php
- DOTween ライセンス: http://dotween.demigiant.com/license.php
- GameFrameX ドキュメント: https://gameframex.doc.alianblank.com
- リポジトリ: https://github.com/GameFrameX/com.gameframex.unity.demigiant.dotween
- イシュー: https://github.com/GameFrameX/com.gameframex.unity.demigiant.dotween/issues

## ライセンス

DOTween and DOTween Pro are copyright (c) 2014-2018 Daniele Giardini - Demigiant. 詳細は [LICENSE](LICENSE.md) をご覧ください。
