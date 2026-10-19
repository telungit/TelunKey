<div align="center">

<img src="./images/icon.png" width="112" alt="TelunKey 아이콘" />

# TelunKey

**macOS 윈도우 전환 · 키보드와 트랙패드**

트리거 키를 누른 채 1~3개 키로 앱과 윈도우에 바로 도착하고, 트랙패드를 한 번 쓸어 윈도우를 배치하세요.

[![최신 릴리스](https://img.shields.io/github/v/release/telungit/TelunKey?label=release)](https://github.com/telungit/TelunKey/releases/latest)
![macOS 14+](https://img.shields.io/badge/macOS-14%2B-black?logo=apple)

[웹사이트](https://www.telunkey.shop) · [설치](#install) · [피드백](#feedback)

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

트리거 키를 누른 채 트랙패드를 두 손가락으로 쓸어 포인터 아래 윈도우를 절반, 4분의 1 화면 또는 최대화 상태로 배치합니다.

- 상하좌우: 절반. 대각선 네 방향: 1/4
- 손을 떼지 않고 위로 갔다 아래로: 최대화(메뉴 막대와 Dock 유지)
- 취소 영역에 들어가면 취소, 되돌아오면 다시 선택

### 세 손가락 전역 제스처

켜면 세 손가락의 8방향 쓸기, 왕복, 탭, 더블 탭, 길게 터치, 누르기마다 단축키, 단일 키, 가운데 클릭 또는 윈도우 동작을 할당할 수 있습니다.

- 기본값은 꺼짐. 시스템 세 손가락 제스처와 충돌하면 설정 화면에 목록과 설정 바로가기를 표시
- 디스플레이 간 이동: 세 손가락 제스처로 취소 영역을 지나 계속 바깥쪽으로 쓸면 윈도우 비율을 유지한 채 다른 디스플레이로 이동합니다.
- 모든 제스처는 다시 지정할 수 있으며, 실행하지 않고 미리 보기만 하는 연습 모드도 있습니다.

<p align="center"><img src="./images/en/gestures.png" width="380" alt="트리거 제스처 설정" /></p>

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

## 권한과 개인정보

| 권한 | 용도 |
| --- | --- |
| 손쉬운 사용(필수) | 트리거 키와 제스처 감지, 윈도우 전환과 배치 |
| 화면 기록(선택) | 윈도우 썸네일 생성. 허용하지 않으면 앱 아이콘을 표시하며 전환은 그대로 동작 |

TelunKey는 로컬 우선 설계를 따르며, 키 입력 내용이나 윈도우 동작 텔레메트리를 수집하지 않습니다.

Dodo Payments가 결제, 구매 이메일, 라이선스 키와 기기 활성화를 처리합니다. 활성화 시 키와 기기 이름을 보내 2대 제한을 관리합니다. 키와 활성화 기록은 시스템 키체인에 저장됩니다. 카드 정보를 저장하거나 웹사이트 계정을 만들지 않습니다.

## 무료 버전과 평생 업데이트 플랜

무료 버전은 앱을 최대 5개까지 할당할 수 있으며, 모든 기능을 시간제한이나 계정 등록 없이 사용할 수 있습니다. 평생 업데이트 플랜은 US$3.99를 한 번 결제하며, 앱 수 제한이 없고 이후 업데이트가 포함됩니다.

결제를 마친 뒤 Dodo Payments에서 보낸 라이선스 키 이메일을 확인하고 TelunKey 설정의 '라이선스' 페이지에 입력하세요. 계정은 필요 없습니다. Mac 2대에서 쓸 수 있으며, 기기를 바꾸기 전에 이전 Mac에서 해제하세요.

[플랜 및 약관](https://www.telunkey.shop/ko/terms)

<a id="feedback"></a>

## 피드백

- [GitHub Issues](https://github.com/telungit/TelunKey/issues)
- [Telegram](https://t.me/telungram)
