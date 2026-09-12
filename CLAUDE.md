# TIL 저장소 규칙

이 저장소는 **공개**다. 매일 실무에서 마주친 개념을 캡처하고, 내 말로 정리한다.

## 내용
- 회사 코드, 내부 용어, 테이블·서비스·프로젝트·계정 실명, 동료 이름을 쓰지 않는다. 도메인은 "물류 배차 시스템" 수준으로 일반화한다.
- 개념 설명을 대신 작성하지 않는다. `## 내가 이해한 것` 은 사용자가 자기 말로 쓴다. Claude 는 질문·점검·커밋만 한다.
- 확인하지 않은 내용에는 `(미검증)` 을 붙인다.
- 하루 2개 캡처가 목표다. 강제하지 않는다.

## 파일
- 주제당 파일 하나: `notes/<slug>.md`. slug 는 영문 kebab-case (`optimistic-lock`).
- frontmatter: `date` (캡처한 날), `status` (`captured` → `written` → `published`).
- 섹션 3개 고정: `## 상황` · `## 내가 이해한 것` · `## 더 알아볼 것`.
- 블로그로 승격하면 `status: published` 와 글 URL 을 frontmatter 에 적는다. 초안은 이 저장소에 두지 않는다.

## 커밋
- 접두어: `capture: <제목>` / `write: <제목>` / `publish: <제목>`. 주제 하나에 커밋 하나.
- 커밋 즉시 push 한다.
- 이 저장소의 author 는 개인 계정으로 자동 설정된다. 커밋 전 `git config user.email` 이 `users.noreply.github.com` 이 아니면 중단한다.

## 스킬
`/til-capture` (어느 프로젝트에서든, 퇴근 전) · `/til-write` (어디서든, 퇴근 후). 정의는 `~/.claude/skills/` 에 있다.
