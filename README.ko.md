# TelunKey
[简体中文](./README.md) | [繁體中文](./README.zh-Hant.md) | [English](./README.en.md) | [日本語](./README.ja.md) | [한국어](./README.ko.md) | [Español](./README.es.md) | [Português](./README.pt.md) | [हिन्दी](./README.hi.md) | [Русский](./README.ru.md) | [Français](./README.fr.md) | [Deutsch](./README.de.md) | [العربية](./README.ar.md)

TelunKey는 한 번의 키 입력 흐름으로 앱 활성화와 창 선택을 완료하는 macOS 네이티브 단축키 런처입니다.

- 네이티브 Swift 구현으로 빠른 응답, 낮은 오버헤드, 적은 방해
- 좌/우 Command(0 지연 또는 사용자 지정 지연), 좌/우 Option(0 지연 또는 사용자 지정 지연), Space 트리거(일상 입력에 영향을 주지 않도록 최소 0.2초 지연) 지원
- 고빈도 워크플로를 위한 창 전환 경험 최적화
- 로컬 우선 설계로 기본적으로 클라우드 행동 분석에 의존하지 않음

## 웹사이트

- Zeabur 홈페이지: https://telunkey.zeabur.app

> [!IMPORTANT]
> Zeabur에 지속적으로 접속할 수 없다면 현재 환경에서는 TelunKey가 적합하지 않을 수 있습니다. 네트워크 문제를 해결할 수 있다면 TelunKey를 시도해 볼 가치가 있습니다.

## 화면 미리보기

https://github.com/user-attachments/assets/bf6afeee-3813-410c-87db-9696f364cea7

<img alt="트리거 힌트" src="./images/datishi.png?v=20260329" width="100%" />
<img alt="Chrome 시나리오" src="./images/chrome.png?v=20260329" width="100%" />
<img alt="설정 화면" src="./images/shezhi.png?v=20260329" width="100%" />

## 시스템 요구사항

- macOS 14.0 이상

## 다운로드

- 최신 버전(DMG): https://github.com/telungit/TelunKey/releases/latest/download/TelunKey.dmg
- 전체 버전: https://github.com/telungit/TelunKey/releases

## 설치

1. `TelunKey.dmg`를 다운로드하고 엽니다
2. `TelunKey.app`를 응용 프로그램 폴더로 드래그합니다
3. 앱은 아직 실행하지 말고, DMG 안의 `一键修复.command`를 먼저 더블클릭합니다
4. 복구가 끝난 뒤 TelunKey를 실행합니다
5. 스크립트가 실패할 때만 터미널에서 아래 명령을 수동으로 실행합니다

```bash
xattr -dr com.apple.quarantine /Applications/TelunKey.app
```

## 권한 안내

TelunKey의 전체 기능 사용을 위해 아래 권한이 필요합니다.

- 손쉬운 사용(Accessibility): 전역 키보드 이벤트 수신
- 화면 기록(Screen Recording): 창 썸네일 생성

## 개인정보

TelunKey는 로컬 우선 전략을 따르며 핵심 데이터는 로컬 기기에 저장됩니다.

## 피드백

- Telegram: https://t.me/telungram
