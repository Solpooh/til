---
date: 2026-10-26
status: captured
---
# 분산 스케줄러 잠금 (ShedLock)

## 상황
물류 배차 시스템의 배치는 `@Scheduled` 로 도는데, 배치 메서드마다 `@SchedulerLock` 이 붙어 있었다.
blue/green 두 JVM 이 함께 떠 있을 때, 잠금을 잡은 JVM 인스턴스만 배치를 실행할 수 있도록
구성한 구조인지를 짚어둘 것.

## 내가 이해한 것

## 더 알아볼 것
