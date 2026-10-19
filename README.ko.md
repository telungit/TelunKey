<div align="center">

<img src="./images/icon.png" width="112" alt="TelunKey 아이콘" />

# TelunKey

**키보드로 윈도우에 바로, 제스처로 배치까지**

키 하나를 누른 채 한두 글자만 입력하면 어떤 앱의 어떤 윈도우로든 바로 이동합니다. 트랙패드를 한 번 쓸면 윈도우가 제자리를 찾습니다.

[![최신 릴리스](https://img.shields.io/github/v/release/telungit/TelunKey?label=release)](https://github.com/telungit/TelunKey/releases/latest)
![macOS 14+](https://img.shields.io/badge/macOS-14%2B-black?logo=apple)

[웹사이트](https://www.telunkey.shop) · [설치](#install) · [피드백](#feedback)

[简体中文](./README.md) | [繁體中文](./README.zh-Hant.md) | [English](./README.en.md) | [日本語](./README.ja.md) | 한국어 | [Español](./README.es.md) | [Português](./README.pt.md) | [हिन्दी](./README.hi.md) | [Русский](./README.ru.md) | [Français](./README.fr.md) | [Deutsch](./README.de.md) | [العربية](./README.ar.md)

</div>

## 두세 번의 키 입력으로 앱에 바로

트리거 키(왼쪽 / 오른쪽 Command, 왼쪽 / 오른쪽 Option 또는 Space)를 누른 채 한 글자에서 세 글자를 입력하세요. 앱이 실행 중이 아니면 열고, 윈도우가 하나면 바로 앞으로 가져오며, 여러 개면 선택기를 띄웁니다. 키를 누르고 있는 동안 모든 바인딩이 표시되므로 외울 필요가 없습니다.

<img src="./images/en/hint.png" width="100%" alt="트리거 키를 누르고 있을 때 모든 바인딩을 보여 주는 힌트 메뉴" />

## 한눈에 윈도우 선택

선택기는 앱의 모든 윈도우를 썸네일로 보여 줍니다. 숫자나 문자 키 하나로 고르고, Space로 가장 최근에 사용한 윈도우로 돌아갑니다. 윈도우가 여러 데스크탑에 흩어져 있으면 카드마다 어느 데스크탑인지 표시됩니다.

<img src="./images/en/picker.png" width="100%" alt="썸네일이 있는 윈도우 선택기" />

## 트랙패드를 쓸면 윈도우가 제자리에

- **트리거 제스처**: 트리거 키를 누른 채 트랙패드를 쓸어 포인터 아래 윈도우를 절반, 4분의 1 화면 또는 최대 크기로 배치합니다.
- **전역 제스처**: 세 손가락 쓸기, 탭, 누르기에 윈도우 동작, 키보드 단축키 또는 단일 키를 지정합니다.
- **디스플레이 간 이동**: 전역 제스처를 가장자리 너머까지 밀면 비율을 유지한 채 윈도우를 다른 디스플레이로 옮깁니다.
- 모든 제스처는 다시 지정할 수 있으며, 실행하지 않고 미리 보기만 하는 연습 모드도 있습니다.

## 네이티브, 가볍게

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

설정은 Mac에, 라이선스 정보는 키체인에 저장됩니다. TelunKey는 라이선스 확인과 업데이트 확인 때만 인터넷에 연결하며 사용 데이터를 수집하지 않습니다.

## 무료와 라이선스

무료 버전에서는 앱을 5개까지 바인딩할 수 있고 나머지 기능은 모두 사용할 수 있습니다. [웹사이트](https://www.telunkey.shop)에서 영구 라이선스를 구매하면 제한이 없어집니다.

<a id="feedback"></a>

## 피드백

- [GitHub Issues](https://github.com/telungit/TelunKey/issues)
- [Telegram](https://t.me/telungram)
