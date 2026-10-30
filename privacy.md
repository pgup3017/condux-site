---
title: Condux 개인정보 처리방침
---

# Condux 개인정보 처리방침

최종 수정: 2026년 10월 31일

## 요약

Condux 는 자체 서버가 없습니다. 앱은 사용자의 정보를 개발자에게 보내지 않습니다. 사용자가 보낸 메시지는 사용자가 선택한 AI 서비스(Anthropic Claude API)로 직접 전송되어 답변을 받는 데에만 쓰입니다.

## 앱이 저장하는 정보 (이 Mac 안에만)

- **대화 기록**: 이 Mac 의 앱 데이터 폴더에만 저장됩니다. 다른 곳으로 전송되지 않습니다.
- **설정**(모델 선택, 예산 등): macOS 사용자 기본값에 저장됩니다.
- **API 키**: 사용자가 직접 입력한 키는 이 앱 전용 macOS 키체인 항목에만 저장됩니다. 앱은 키를 다시 표시하거나 다른 곳으로 보내지 않습니다.

## 외부로 전송되는 정보

사용자가 메시지를 보내면 그 내용은 Anthropic 의 API(api.anthropic.com)로 HTTPS 로 전송됩니다. 이때 적용되는 약관과 개인정보 정책은 Anthropic 의 것입니다.

- Anthropic 개인정보 정책: https://www.anthropic.com/legal/privacy
- Anthropic 이용 약관: https://www.anthropic.com/legal/consumer-terms

앱은 분석(애널리틱스), 광고, 추적 기능을 포함하지 않으며 사용자를 식별하는 정보를 수집하지 않습니다.

## 요금

Condux 는 어떤 결제도 받지 않습니다. API 사용 요금은 사용자가 Anthropic 과 직접 정산합니다.

## 삭제

앱을 지우고 `~/Library/Containers/local.sbyeo.Condux.store` 폴더를 삭제하면 모든 기록과 설정이 사라집니다. 키체인 항목은 앱 설정의 ‘키 삭제’ 또는 키체인 접근 앱에서 지울 수 있습니다.

## 문의

GitHub 이슈: https://github.com/pgup3017/condux-site/issues
