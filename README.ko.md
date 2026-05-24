<div align="center">
  <img src="https://download.alianblank.com/gameframex/gameframex_logo_320.png" alt="Game Frame X Logo" width="160" />
</div>

# Game Frame X DOTween

[![GitHub release](https://img.shields.io/github/v/release/GameFrameX/com.gameframex.unity.demigiant.dotween?style=flat-square)](https://github.com/GameFrameX/com.gameframex.unity.demigiant.dotween/releases)
[![License](https://img.shields.io/github/license/GameFrameX/com.gameframex.unity.demigiant.dotween?style=flat-square)](https://github.com/GameFrameX/com.gameframex.unity.demigiant.dotween/blob/main/LICENSE.md)
[![Documentation](https://img.shields.io/badge/Documentation-Online-blue?style=flat-square)](https://gameframex.doc.alianblank.com)

**인디 게임 개발자를 위한 올인원 솔루션 · 인디 개발자의 꿈을 실현**

[문서](https://gameframex.doc.alianblank.com) · [빠른 시작](#빠른-시작) · [QQ 그룹](https://qm.qq.com/q/5s5e1e6e6e)

**언어**: [English](README.md) | [简体中文](README.zh-CN.md) | [繁體中文](README.zh-TW.md) | [日本語](README.ja.md) | **한국어**

---

## 프로젝트 개요

Game Frame X DOTween은 [DOTween](http://dotween.demigiant.com)의 GameFrameX 프레임워크 통합 패키지입니다. DOTween은 트윈 애니메이션 제작을 위한 Unity 애니메이션 플러그인입니다.

이 라이브러리는 주로 [GameFrameX](https://github.com/AlianBlank/GameFrameX)의 서브모듈로 사용됩니다.

## 변경 사항

1. `link.xml` 스트리핑 필터 추가

## 빠른 시작

### 시스템 요구 사항

- Unity 2018.4 이상

### 설치

다음 방법 중 하나를 선택하세요:

1. 프로젝트의 `manifest.json` 파일에 다음 내용을 추가:
   ```json
   {"com.gameframex.unity.demigiant.dotween": "https://github.com/AlianBlank/com.gameframex.unity.demigiant.dotween.git"}
   ```

2. Unity의 Package Manager에서 `Git URL`을 사용하여 추가:
   ```
   https://github.com/AlianBlank/com.gameframex.unity.demigiant.dotween.git
   ```

3. 저장소를 다운로드하여 Unity 프로젝트의 `Packages` 디렉토리에 배치하면 자동으로 로드됩니다.

## 사용 방법

- 임포트 후, "Tools/Demigiant" 메뉴에서 DOTween의 Utility Panel을 선택하고 "Setup DOTween..." 버튼을 눌러 모듈을 활성화/비활성화합니다.
- 코드에서 DOTween을 사용할 각 클래스에 `using DG.Tweening`을 추가합니다.

## 문서 및 자료

- DOTween 문서: http://dotween.demigiant.com/documentation.php
- DOTween 라이선스: http://dotween.demigiant.com/license.php
- GameFrameX 문서: https://gameframex.doc.alianblank.com
- 저장소: https://github.com/GameFrameX/com.gameframex.unity.demigiant.dotween
- 이슈: https://github.com/GameFrameX/com.gameframex.unity.demigiant.dotween/issues

## 라이선스

DOTween and DOTween Pro are copyright (c) 2014-2018 Daniele Giardini - Demigiant. 자세한 내용은 [LICENSE](LICENSE.md)를 참조하세요.
