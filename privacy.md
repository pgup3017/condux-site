---
title: Condux 개인정보 처리방침
---

# Condux 개인정보 처리방침

최종 수정: 2026년 10월 31일

## 요약

Condux 는 자체 서버가 없습니다. 앱은 사용자의 정보를 개발자에게 보내지 않습니다. 사용자가 보낸 메시지는 사용자가 선택한 AI 서비스(Anthropic Claude API 또는 OpenAI API)로 직접 전송되어 답변을 받는 데에만 쓰입니다.

## 앱이 저장하는 정보 (이 Mac 안에만)

- **대화 기록**: 이 Mac 의 앱 데이터 폴더에만 저장됩니다. 다른 곳으로 전송되지 않습니다.
- **설정**(모델 선택, 예산 등): macOS 사용자 기본값에 저장됩니다.
- **API 키**: 사용자가 직접 입력한 키는 이 앱 전용 macOS 키체인 항목에만 저장됩니다. 앱은 키를 다시 표시하거나 다른 곳으로 보내지 않습니다.

## 외부로 전송되는 정보

사용자가 메시지를 보내면 그 내용은 사용자가 고른 서비스의 API(api.anthropic.com 또는 api.openai.com)로 HTTPS 로 전송됩니다. 이때 적용되는 약관과 개인정보 정책은 각 서비스의 것입니다.

웹 검색을 켜 두면(기본값) AI 가 필요할 때 검색어를 만들어 웹을 검색하고, 대화에 나온 링크의 페이지를 읽습니다. 이 동작은 앱이 아니라 사용자가 고른 AI 서비스의 서버에서 이루어지며, 해당 웹사이트에 요청 정보가 남을 수 있습니다. 연결 관리 ▸ 일반 ▸ 웹 검색에서 끌 수 있습니다.

- Anthropic 개인정보 정책: https://www.anthropic.com/legal/privacy
- Anthropic 이용 약관: https://www.anthropic.com/legal/consumer-terms
- OpenAI 개인정보 정책: https://openai.com/policies/privacy-policy
- OpenAI 이용 약관: https://openai.com/policies/terms-of-use

OpenAI 요청은 `store: false` 로 보내 OpenAI 서버가 대화를 보관하지 않도록 요청합니다.

앱은 분석(애널리틱스), 광고, 추적 기능을 포함하지 않으며 사용자를 식별하는 정보를 수집하지 않습니다.

## 요금

Condux 는 어떤 결제도 받지 않습니다. API 사용 요금은 사용자가 Anthropic 또는 OpenAI 와 직접 정산합니다.

## 삭제

앱을 지우고 `~/Library/Containers/local.sbyeo.Condux.store` 폴더를 삭제하면 모든 기록과 설정이 사라집니다. 키체인 항목은 앱 설정의 ‘키 삭제’ 또는 키체인 접근 앱에서 지울 수 있습니다.

## 문의

GitHub 이슈: https://github.com/pgup3017/condux-site/issues
