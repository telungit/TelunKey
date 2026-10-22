<div align="center">

<img src="./images/icon.png" width="112" alt="TelunKey 아이콘" />

# TelunKey

**macOS 윈도우 전환 · 키보드와 트랙패드**

트리거 키를 누른 채 1~3개 키로 앱과 윈도우에 바로 도착하고, 트랙패드를 한 번 쓸어 윈도우를 배치하세요.

[![최신 릴리스](https://img.shields.io/github/v/release/telungit/TelunKey?label=release)](https://github.com/telungit/TelunKey/releases/latest)
![macOS 14+](https://img.shields.io/badge/macOS-14%2B-black?logo=apple)

[telunkey.shop](https://www.telunkey.shop)

[설치](#install) · [피드백](#feedback)

[简体中文](./README.md) | [繁體中文](./README.zh-Hant.md) | [English](./README.en.md) | [日本語](./README.ja.md) | 한국어 | [Español](./README.es.md) | [Português](./README.pt.md) | [हिन्दी](./README.hi.md) | [Русский](./README.ru.md) | [Français](./README.fr.md) | [Deutsch](./README.de.md) | [العربية](./README.ar.md)

</div>

## 키로 바로 이동

트리거 키(왼쪽 / 오른쪽 Command, 왼쪽 / 오른쪽 Option 또는 Space)를 누른 채 앱에 지정한 키 1~3개를 입력합니다. 앱이 실행 중이 아니면 열고, 윈도우가 하나면 앞으로 가져오며, 여러 개면 선택기를 표시합니다. 트리거 키를 누르고 있는 동안 모든 할당을 확인할 수 있습니다.

<img src="./images/en/hint.png" width="100%" alt="트리거 키를 누르고 있을 때 모든 할당을 보여 주는 힌트 메뉴" />

## 키 배열 선택기

선택기는 윈도우 썸네일을 키보드 순서(1–0, Q–P, A–L, Z–M)로 배치하며 페이지당 최대 36개를 표시합니다. 해당 숫자나 문자 키로 선택합니다.

- 스페이스: 마지막으로 쓴 윈도우로
- 다른 데스크탑의 윈도우는 어느 데스크탑인지 표시
- [ 와 ]로 페이지 이동, Esc로 취소, 클릭해도 됩니다

<img src="./images/en/picker.png" width="100%" alt="윈도우 선택기" />

## 트리거 제스처

트리거 키를 누른 채 활성화한 한 손가락, 두 손가락 또는 세 손가락으로 밀어 포인터 아래 창을 절반, 사분면 또는 최대화로 배치합니다.

- 상하좌우: 절반. 대각선 네 방향: 1/4
- 손을 떼지 않고 위로 갔다 아래로: 최대화(메뉴 막대와 Dock 유지)
- 취소 영역에 들어가면 취소, 되돌아오면 다시 선택

<p align="center"><img src="./images/en/gestures.png" width="380" alt="트리거 제스처 설정" /></p>

## 세 손가락과 네 손가락 전역 제스처

트리거 키 없이 사용합니다. 세 손가락 쓸기와 왕복, 세 손가락 또는 네 손가락 탭, 이중 탭, 물리적 클릭에 단축키, 단일 키, 가운데 클릭 또는 윈도우 작업을 지정할 수 있으며, 길게 터치는 화면 이동 전용입니다. 모든 동작은 포인터 아래에 고정된 윈도우에 적용되며, 실행 없이 미리 보는 연습 모드를 제공합니다.

시스템의 세 손가락 쓸기, 드래그 또는 찾아보기와 충돌하면 켜져 있는 항목만 표시하고 해당 시스템 설정 페이지로 바로 안내하며, 돌아오면 자동으로 다시 확인합니다(시스템 설정을 임의로 변경하지 않음). 충돌이 해결되기 전까지 세 손가락 쓸기와 길게 터치는 작동하지 않으며, 탭과 클릭은 그대로 사용할 수 있습니다.

## 길게 터치하여 화면 이동

왼쪽, 오른쪽, 아니면 위쪽? 길게 터치하면 macOS 디스플레이 배치와 일치하는 지도가 열립니다. 원하는 화면으로 밀고 손을 떼면 사용 가능 영역의 비율을 유지한 채 윈도우를 옮깁니다.

- 네 손가락을 길게 터치해 화면 선택(일반 네 손가락 쓸기는 macOS가 처리). 준비된 세 손가락, 또는 트리거 키를 누른 채 활성화된 한~세 손가락도 지원합니다
- 대상 디스플레이에 현재 표시된 데스크탑으로 이동하며, 전체 화면 윈도우나 전체 화면 앱을 표시 중인 디스플레이는 제외됩니다
- 확정 전에는 언제든 되돌릴 수 있으며, 원래 화면이나 빈 공간에서 손을 떼거나 트리거 키를 먼저 놓거나 Esc를 눌러 취소할 수 있습니다

## 실행 및 설정

순수 Swift로 작성되어 서드파티 의존성이 없고 메뉴 막대에 상주합니다. 설정은 Mac에 저장되며 가져오기와 내보내기가 가능하고, 인터페이스는 12개 언어를 지원합니다.

https://github.com/user-attachments/assets/bf6afeee-3813-410c-87db-9696f364cea7

<a id="install"></a>

## 시작하기

macOS 14 이상과 [Homebrew](https://brew.sh/)가 필요합니다:

```bash
brew install --cask telungit/tap/telunkey
```

처음 실행하면 설정 가이드가 권한, 트리거 키, 단축키, 제스처 설정을 안내합니다. 업데이트는 앱 안에서 하거나 다음을 실행하세요:

```bash
brew upgrade --cask --greedy telungit/tap/telunkey
```

## 권한

| 권한 | 용도 |
| --- | --- |
| 손쉬운 사용(필수) | 트리거 키와 제스처 감지, 윈도우 전환과 배치 |
| 화면 기록(선택) | 윈도우 썸네일 생성. 허용하지 않으면 앱 아이콘을 표시하며 전환은 그대로 동작 |

<a id="feedback"></a>

## 피드백

- [GitHub Issues](https://github.com/telungit/TelunKey/issues)
- [Telegram](https://t.me/telungram)
