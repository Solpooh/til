---
date: 2026-09-12
status: captured
---
# gh CLI 다중 계정과 git credential helper (gh auth git-credential)

## 상황
한 맥북에서 회사·개인 GitHub 계정을 함께 쓰려고 git 의 HTTPS 인증을 gh CLI 로 일원화했다. gh 에 계정 두 개를 로그인해 두었는데, git 이 credential helper 로 `gh auth git-credential` 을 호출하면 active 계정의 토큰만 돌려주고, 다른 계정의 username 을 넘기면 빈 응답이 왔다.

## 내가 이해한 것

## 더 알아볼 것
