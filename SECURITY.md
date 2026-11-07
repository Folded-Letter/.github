# Security Policy

[한국어](#한국어) | [English](#english)

## 한국어

접어 둔 편지는 친구들이 보낸 편지와 이메일 같은 개인정보를 다룹니다. 보안 문제를 발견하면 공개하지 말고 비공개로 알려 주세요.

### 제보 방법

공개 이슈, PR, SNS에 올리지 말고 [비공개 취약점 제보 양식](https://github.com/Folded-Letter/.github/security/advisories/new)을 써 주세요. 아래 내용을 함께 적어 주시면 빠르게 확인할 수 있습니다.

- 문제가 있는 주소, 화면 또는 저장소
- 재현 순서
- 예상되는 영향
- 사용한 기기와 브라우저 또는 앱 버전

### 지원 범위

최신 버전의 웹과 앱, Folded-Letter 조직의 저장소를 대상으로 합니다. 아래와 같은 문제를 알려 주세요.

- 열리기 전 편지의 본문이나 추천 작품이 보이는 문제
- 관리 링크나 연결 토큰을 추측하거나 가로채는 문제
- 다른 사람의 편지나 책장을 보거나, 바꾸거나, 가져가는 문제
- 이메일, 푸시 토큰 같은 개인정보가 노출되는 문제
- 편지 내용이나 링크로 스크립트를 실행하는 문제(XSS)
- 친구가 붙인 링크로 서버가 내부 주소를 열게 하는 문제(SSRF)
- 저장소에 올라간 비밀번호, API 키, 토큰

### 제보 대상이 아닌 것

- 사칭 편지나 부적절한 편지: 편지 화면의 신고 기능을 써 주세요.
- YouTube, 카카오 같은 외부 서비스 자체의 문제: 해당 서비스에 알려 주세요.
- 재현 방법이나 실제 영향이 없는 자동 스캐너 결과

### 시험할 때 지켜 주세요

- 본인이 만든 책장과 편지로만 시험합니다.
- 다른 사람의 편지나 개인정보를 보게 되면 바로 멈추고, 저장하거나 공유하지 말고 제보에 그 사실만 적습니다.
- 서비스를 멈추게 하는 공격(DoS), 부하 테스트, 스팸 발송을 하지 않습니다.
- 수정이 끝나기 전에는 내용을 공개하지 않습니다.

### 처리 과정

1. 7일 안에 접수 여부를 답합니다.
2. 문제를 확인하면 심각도와 수정 계획을 알려 드립니다.
3. 수정이 끝나면 결과를 알려 드리고, 원하시면 제보자 이름을 남깁니다.

현재 포상금 제도는 없습니다.

## English

Folded Letter handles letters from friends and personal data such as email addresses. If you find a security issue, please report it privately instead of making it public.

### How to report

Please do not post it in a public issue, pull request, or on social media. Use the [private vulnerability report form](https://github.com/Folded-Letter/.github/security/advisories/new) and include the following so it can be checked quickly:

- The affected URL, screen, or repository
- Steps to reproduce
- The expected impact
- Your device and browser or app version

### Scope

This policy covers the latest version of the web and apps, and repositories in the Folded-Letter organization. Please report issues such as:

- The body or recommended work of an unopened letter becoming visible
- Guessing or intercepting management links or link tokens
- Viewing, changing, or taking someone else's letters or shelf
- Exposure of personal data such as email addresses or push tokens
- Running scripts through letter content or links (XSS)
- Making the server open internal addresses through a pasted link (SSRF)
- Passwords, API keys, or tokens committed to a repository

### Out of scope

- Impersonation or inappropriate letters: please use the report feature on the letter screen.
- Problems in external services such as YouTube or Kakao: please report them to that service.
- Automated scanner results without reproduction steps or real impact

### While testing

- Test only with shelves and letters you created.
- If you come across someone else's letters or personal data, stop right away, do not save or share it, and mention only that fact in your report.
- Do not run denial-of-service attacks or load tests, and do not send spam.
- Do not disclose details until the fix is complete.

### What happens next

1. You will get a reply within 7 days.
2. Once the issue is confirmed, you will hear its severity and the fix plan.
3. When the fix is complete, you will hear the result and can be credited if you wish.

There is currently no bug bounty.