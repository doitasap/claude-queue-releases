---
name: 버그 신고 / Bug report
about: 앱에서 발생한 문제를 신고합니다. / Report a problem with the app.
title: "[버그] 여기에 문제의 간단한 제목을 작성해주세요 / Briefly summarize the problem"
labels: "bug"
assignees: ""
---

## 🐞 문제 설명 / Description
발생한 문제를 간단히 설명해주세요.
Briefly describe the problem.

예시: **자동 큐에 넣은 명령이 실행되지 않고 계속 대기 상태로 남습니다.**
Example: **A command added to the auto queue never runs and stays waiting.**

---

## ⚙️ 재현 방법 / Steps to reproduce
문제가 발생하는 과정을 단계별로 작성해주세요.
List the steps that lead to the problem.

1. **어떤 화면** 또는 **어떤 상황**에서 발생했는지 작성해주세요.
   Which **screen** or **situation** it happened in.
2. **어떤 동작**을 했을 때 문제가 발생했는지 작성해주세요.
   Which **action** triggered the problem.

예시:
Example:
1. 프로젝트 경로를 고르고 명령을 자동 큐에 등록함.
   Picked a project path and added a command to the auto queue.
2. 앞 항목이 완료된 뒤에도 다음 항목이 시작되지 않음.
   The next item did not start after the previous one finished.
3. ▶ 버튼을 눌러도 "대기 중 · 세션 사용 중" 안내만 표시됨.
   Pressing ▶ only showed the "대기 중 · 세션 사용 중" (waiting · session in use) notice.

---

## 🖥 환경 정보 / Environment
사용 중인 환경 정보를 작성해주세요.
Tell us about your environment.

- **ClaudeQueue 버전 / version**: (예: v0.1.0 — 메뉴 막대 → 정보에서 확인 / e.g. v0.1.0 — see menu bar → About)
- **macOS 버전 / version**: (예: macOS 14.5 Sonoma / e.g. macOS 14.5 Sonoma)
- **아키텍처 / Architecture**: (예: aarch64 또는 x86_64 / e.g. aarch64 or x86_64)
- **Claude Code CLI 버전 / version**: (터미널에서 `claude --version` 실행 결과 / output of `claude --version` in a terminal)
- **실행 대상 / Target**: (경로 대상 / 세션 대상 / 하위 항목 중 해당하는 것 / one of: path target, session target, sub-item)

---

## 📋 추가 정보 / Additional info
문제와 관련된 스크린샷이나 로그가 있다면 첨부해주세요. (선택 사항)
Attach any related screenshots or logs. (Optional)

로그는 아래 경로에 날짜별로 쌓입니다.
Logs are saved by date in the folder below.

```
~/Library/Application Support/com.doitasap.claudequeue/logs/
```

> ⚠️ 로그와 스크린샷에 **경로·명령 내용이 그대로 담길 수 있습니다.** 공개하기 곤란한
> 정보가 있다면 가리고 올려주세요.
> Logs and screenshots **may contain file paths and command text as is.** Please redact
> anything you would rather not share before posting.
