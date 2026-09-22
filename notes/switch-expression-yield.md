---
date: 2026-09-22
status: captured
---
# switch 표현식의 yield (switch expression yield)

## 상황
물류 배차 시스템의 정산 금액 산정 로직을 읽다가, 단가 기준 enum 을 전수 switch 하는
메서드에서 한 갈래만 블록 `{}` 으로 열려 있고 그 안에 `yield` 로 시작하는 줄이 있었다.
타입 이름처럼 보여서 무엇인지 몰랐다.

## 내가 이해한 것

## 더 알아볼 것
- 어떤 case 에 yield 가 필요하고, 어떤 case 에는 필요 없나
- switch 문(statement)과 switch 표현식(expression)의 차이
- return 과는 무엇이 다른가
