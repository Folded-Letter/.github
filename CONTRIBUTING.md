# Contributing

[한국어](#한국어) | [English](#english)

## 한국어

접어 둔 편지에 관심을 가져 주셔서 고맙습니다. 문서 수정, 버그 제보, 기능 제안 모두 환영합니다. 이슈와 PR은 한국어나 영어로 편하게 써 주세요.

### 시작하기 전에

- 모든 참여자는 [행동 강령](https://github.com/Folded-Letter/.github/blob/HEAD/CODE_OF_CONDUCT.md)을 지켜 주세요.
- 보안 문제는 이슈로 올리지 말고 [보안 정책](https://github.com/Folded-Letter/.github/blob/HEAD/SECURITY.md)을 따라 주세요.
- 오타나 깨진 링크 같은 작은 수정은 바로 PR을 보내 주세요.
- 기능 추가나 요구사항 변경처럼 큰 변경은 먼저 이슈를 열어 방향을 맞춰 주세요.

### 이슈

- 버그: 재현 순서, 기대한 동작, 실제 동작, 기기와 브라우저 또는 앱 버전을 적어 주세요.
- 제안: 풀고 싶은 문제와 관련 요구사항 ID(예: F-07)를 적어 주세요.
- 스크린샷과 로그에 있는 이메일, 편지 내용, 관리 링크는 가려 주세요. 관리 링크가 드러나면 다른 사람이 그 책장을 관리할 수 있습니다.

### PR

1. 브랜치에서 작업합니다. 외부 기여자는 포크한 저장소에서 작업합니다.
2. PR 하나에는 한 가지 변경만 담습니다.
3. 무엇을 왜 바꿨는지와 관련 이슈 번호를 적습니다.

### 커밋 메시지

[Gitmoji](https://gitmoji.dev) 하나와 영어 요약 한 줄로 씁니다. 요약은 명령형으로 쓰고, 첫 글자만 대문자로 씁니다. PR 제목도 같은 형식을 씁니다.

```text
📝 Add requirements docs and update README
```

| Gitmoji | 코드 | 쓰는 경우 |
| --- | --- | --- |
| ✨ | `:sparkles:` | 새 기능 |
| 🐛 | `:bug:` | 버그 수정 |
| 📝 | `:memo:` | 문서 추가·수정 |
| ✏️ | `:pencil2:` | 오타 수정 |
| 💄 | `:lipstick:` | 화면과 스타일 추가·수정 |
| ♻️ | `:recycle:` | 리팩터링 |
| ✅ | `:white_check_mark:` | 테스트 추가·수정 |
| 🔧 | `:wrench:` | 설정 파일 추가·수정 |
| 🔥 | `:fire:` | 코드나 파일 삭제 |
| 🔒️ | `:lock:` | 보안·개인정보 문제 수정 |

### 문서를 고칠 때

- 한국어와 영어 문서는 같은 PR에서 함께 고칩니다. 예: `README.md`와 `README.en.md`
- 요구사항 ID는 바꾸지 않습니다. 새 항목은 다음 번호를 쓰고, 지운 번호는 다시 쓰지 않습니다.
- 외부 서비스의 조건을 적을 때는 출처 링크와 확인한 날짜를 함께 적습니다.

## English

Thank you for your interest in Folded Letter. Documentation fixes, bug reports, and feature ideas are all welcome. Feel free to write issues and pull requests in Korean or English.

### Before you start

- Everyone taking part must follow the [Code of Conduct](https://github.com/Folded-Letter/.github/blob/HEAD/CODE_OF_CONDUCT.md).
- Do not open issues for security problems. Follow the [Security Policy](https://github.com/Folded-Letter/.github/blob/HEAD/SECURITY.md) instead.
- For small fixes such as typos or broken links, send a pull request right away.
- For larger changes such as new features or requirement changes, open an issue first to agree on the direction.

### Issues

- Bugs: include steps to reproduce, expected behavior, actual behavior, and your device and browser or app version.
- Ideas: describe the problem you want to solve and any related requirement IDs (for example, F-07).
- Hide email addresses, letter content, and management links in screenshots and logs. Anyone with a management link can manage that shelf.

### Pull requests

1. Work on a branch. Outside contributors work on a fork.
2. Keep each pull request to one change.
3. Describe what you changed and why, and link the related issue.

### Commit messages

Write one Gitmoji and a one-line English summary. Use the imperative mood and capitalize only the first word. Pull request titles use the same format.

```text
📝 Add requirements docs and update README
```

| Gitmoji | Code | When to use |
| --- | --- | --- |
| ✨ | `:sparkles:` | New feature |
| 🐛 | `:bug:` | Bug fix |
| 📝 | `:memo:` | Add or update documentation |
| ✏️ | `:pencil2:` | Fix typos |
| 💄 | `:lipstick:` | Add or update UI and styles |
| ♻️ | `:recycle:` | Refactor code |
| ✅ | `:white_check_mark:` | Add or update tests |
| 🔧 | `:wrench:` | Add or update configuration files |
| 🔥 | `:fire:` | Remove code or files |
| 🔒️ | `:lock:` | Fix security or privacy issues |

### Editing documents

- Update the Korean and English versions in the same pull request, for example `README.md` and `README.en.md`.
- Do not change requirement IDs. New items take the next number, and deleted numbers are not reused.
- When describing the conditions of an external service, include the source link and the date you checked it.