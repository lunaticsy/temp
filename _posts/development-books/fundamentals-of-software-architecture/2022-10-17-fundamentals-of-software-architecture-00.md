---
title: 소프트웨어 아키텍처 101 - 책 소개
author: June
date: 2022-10-17 02:27:00 +0900
categories: [개발 책, 리팩터링 2판]
tags: [공부, 책, 리팩터링 2판, 마틴 파울러]
toc: true
math: true
mermaid: true
comments: true
---
## 표지

![cover](/posts/development-books/fundamentals-of-software-architecture/cover.jpg)

## 책 소개

**막막했던 아키텍처가 쉬워지는 실무 지침서**

소프트웨어 아키텍트는 전 세계 연봉 10위 안에 드는 직업이지만, 지금까지 ‘개발자가 아키텍트’로 전향하는 데 실질적으로 도움이 될 만한 지침이 없었다. 이 책은 소프트웨어 아키텍처의 다양한 부분을 포괄적으로 개괄한다. 장차 아키텍트가 될 사람과 현직 아키텍트 모두 이 책을 통해 아키텍처 특성, 아키텍처 패턴, 컴포넌트 결정, 아키텍처 도식화 및 프레젠테이션, 진화적 아키텍처 등 다양한 주제를 살펴볼 수 있다.

마크 리처즈와 닐 포드는 수년간 전문적으로 소프트웨어 아키텍처를 강의한 잔뼈가 굵은 실무자로서 이 책에 모든 기술 스택에 고루 적용되는 아키텍처 원칙을 담았다. 이 책으로 지난 10년 동안 이룩한 모든 혁신과 현대적인 관점에서 바라본 소프트웨어 아키텍처를 배우길 바란다.

주요 내용

- 아키텍처 패턴: 수많은 아키텍처 결정을 내리는 기술적인 근간
- 컴포넌트: 식별, 커플링, 응집, 분할, 세분도
- 소프트 스킬: 효과적인 팀 관리, 회의, 협상, 프레젠테이션 등
- 현대성: 지난 수년 동안 근본적으로 변화한 엔지니어링 프랙티스와 운영 방식
- 엔지니어링으로서의 아키텍처: 소프트웨어 아키텍처를 더욱 탄탄하게 만들어주는 반복 가능한 결과, 메트릭, 구체적인 평가

추천사

당신이 경험 많은 아키텍트든, 이제 새로 시작한 아키텍트든, 이 책은 여러분을 더 나은 아키텍트로 만들어줄 겁니다. 제가 커리어를 시작할 즈음에 이런 책이 나왔다면 얼마나 좋았을까요!   - 너새니얼 슈타, VMWare 아키텍트

이 책은 소프트웨어 아키텍처를 섭렵할 수 있도록 충실하게 안내하는 가이드북이 될 것입니다.   - 레베카 J. 파슨스, 쏘우트웍스 최고 기술 책임자(CTO)

## 책 정보

### 원서

- 제목
  - Fundamentals of Software Architecture: An Engineering Approach
- 지은이
  - 마크 리처즈(Mark Richards), 닐 포드(Neal Ford)
- 출판사
  - O'Reilly Media
- 출간일
  - March 3, 2020

### 번역서

- 제목
  - 소프트웨어 아키텍처 101: 엔지니어링 접근 방식으로 배우는 소프트웨어 아키텍처 기초
- 옮긴이
  - 이일웅
- 출판사
  - 한빛미디어
- 출간일
  - 2021년 11월 01일
- 쪽수
  - 472쪽

## 목차

- CHAPTER 1 서론
  - 1.1 소프트웨어 아키텍처란?
  - 1.2 아키텍트에 대한 기대치
  - 1.3 아키텍처의 교차점 그리고...
  - 1.4 소프트웨어 아키텍처 법칙

[PART I 기초]

- CHAPTER 2 아키텍처 사고
  - 2.1 아키텍처 대 설계
  - 2.2 기술 폭
  - 2.3 트레이드오프 분석
  - 2.4 비즈니스 동인의 이해
  - 2.5 아키텍처와 코딩 실무 간 균형 맞추기

- CHAPTER 3 모듈성
  - 3.1 정의
  - 3.2 모듈성 측정
  - 3.3 모듈에서 컴포넌트로

- CHAPTER 4 아키텍처 특성 정의
  - 4.1 아키텍처 특성 (일부) 목록
  - 4.2 트레이드오프 및 나쁜 것 중에서 제일 나은 아키텍처

- CHAPTER 5 아키텍처 특성 식별
  - 5.1 도메인 관심사에서 아키텍처 특성 도출
  - 5.2 요구사항에서 아키텍처 특성 도출
  - 5.3 사례 연구: 실리콘 샌드위치

- CHAPTER 6 아키텍처 특성의 측정 및 거버넌스
  - 6.1 아키텍처 특성 측정
  - 6.2 거버넌스와 피트니스 함수

- CHAPTER 7 아키텍처 특성 범위
  - 7.1 커플링과 커네이선스
  - 7.2 아키텍처 퀀텀과 세분도

- CHAPTER 8 컴포넌트 기반 사고
  - 8.1 컴포넌트 범위
  - 8.2 아키텍트 역할
  - 8.3 개발자 역할
  - 8.4 컴포넌트 식별 흐름
  - 8.5 컴포넌트 세분도
  - 8.6 컴포넌트 설계
  - 8.7 컴포넌트 발굴 사례 연구: GGG
  - 8.8 아키텍처 퀀텀 딜레마: 모놀리식이냐, 분산 아키텍처냐

[PART II 아키텍처 스타일]

- CHAPTER 9 기초
  - 9.1 기초 패턴
  - 9.2 모놀리식 대 분산 아키텍처

- CHAPTER 10 레이어드 아키텍처 스타일
  - 10.1 토폴로지
  - 10.2 레이어 격리
  - 10.3 레이어 추가
  - 10.4 기타 고려 사항
  - 10.5 왜 이 아키텍처 스타일을 사용하는가
  - 10.6 아키텍처 특성 등급

- CHAPTER 11 파이프라인 아키텍처 스타일
  - 11.1 토폴로지
  - 11.2 예제
  - 11.3 아키텍처 특성 등급

- CHAPTER 12 마이크로커널 아키텍처 스타일
  - 12.1 토폴로지
  - 12.2 레지스트리
  - 12.3 계약
  - 12.4 실제 용례
  - 12.5 아키텍처 특성 등급

- CHAPTER 13 서비스 기반 아키텍처 스타일
  - 13.1 토폴로지
  - 13.2 토폴로지 변형
  - 13.3 서비스 설계 및 세분도
  - 13.4 데이터베이스 분할
  - 13.5 아키텍처 예시
  - 13.6 아키텍처 특성 등급
  - 13.7 언제 이 아키텍처 스타일을 사용하는가

- CHAPTER 14 이벤트 기반 아키텍처 스타일
  - 14.1 토폴로지
  - 14.2 브로커 토폴로지
  - 14.3 중재자 토폴로지
  - 14.4 비동기 통신
  - 14.5 에러 처리
  - 14.6 데이터 소실 방지
  - 14.7 브로드캐스팅
  - 14.8 요청-응답
  - 14.9 요청 기반이냐, 이벤트 기반이냐
  - 14.10 하이브리드 이벤트 기반 아키텍처
  - 14.11 아키텍처 특성 등급

- CHAPTER 15 공간 기반 아키텍처 스타일
  - 15.1 토폴로지
  - 15.2 데이터 충돌
  - 15.3 클라우드 대 온프레미스 구현
  - 15.4 복제 캐시 대 분산 캐시
  - 15.5 니어 캐시
  - 15.6 구현 예시
  - 15.7 아키텍처 특성 등급

- CHAPTER 16 오케스트레이션 기반 서비스 지향 아키텍처 스타일
  - 16.1 역사와 철학
  - 16.2 토폴로지
  - 16.3 택소노미
  - 16.4 재사용… 그리고 커플링
  - 16.5 아키텍처 특성 등급

- CHAPTER 17 마이크로서비스 아키텍처 스타일
  - 17.1 역사
  - 17.2 토폴로지
  - 17.3 분산
  - 17.4 경계 콘텍스트
  - 17.5 API 레이어
  - 17.6 운영 재사용
  - 17.7 프런트엔드
  - 17.8 통신
  - 17.9 아키텍처 특성 등급
  - 17.10 더 읽을거리

- CHAPTER 18 최적의 아키텍처 스타일 선정
  - 18.1 아키텍처 ‘유행’은 계속 변한다
  - 18.2 결정 기준
  - 18.3 모놀리스 사례 연구: 실리콘 샌드위치
  - 18.4 분산 아키텍처 사례 연구: GGG

[PART III 테크닉과 소프트 스킬]

- CHAPTER 19 아키텍처 결정
  - 19.1 아키텍처 결정 안티패턴
  - 19.2 아키텍처적으로 중요한
  - 19.3 아키텍처 결정 레코드

- CHAPTER 20 아키텍처 리스크 분석
  - 20.1 리스크 매트릭스
  - 20.2 리스크 평가
  - 20.3 리스크 스토밍
  - 20.4 애자일 스토리 리스크 분석
  - 20.5 리스크 스토밍 예시

- CHAPTER 21 아키텍처 도식화 및 프레젠테이션
  - 21.1 도식화
  - 21.2 프레젠테이션

- CHAPTER 22 개발팀을 효율적으로
  - 22.1 팀 경계
  - 22.2 아키텍트 성향
  - 22.3 얼마나 제어해야 하나?
  - 22.4 팀의 이상 징후
  - 22.5 체크리스트 활용
  - 22.6 지침 제시
  - 22.7 마치며

- CHAPTER 23 협상과 리더십 스킬
  - 23.1 협상과 조정
  - 23.2 소프트웨어 아키텍트는 리더다
  - 23.3 개발팀과의 융합
  - 23.4 마치며

- CHAPTER 24 커리어패스 개발
  - 24.1 20분 규칙
  - 24.2 개인 레이더 개발
  - 24.3 소셜 미디어 활용
  - 24.4 종언

- Appendix A 자율 평가 문제