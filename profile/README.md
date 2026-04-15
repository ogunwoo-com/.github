# 오건우닷컴 (Ogunwoo.com)

<div style="display: flex">
<img src="https://img.shields.io/badge/dart-0175C2?style=for-the-badge&logo=dart&logoColor=white">
<img src="https://img.shields.io/badge/flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white">
<img src="https://img.shields.io/badge/go-00ADD8?style=for-the-badge&logo=go&logoColor=white">
<img src="https://img.shields.io/badge/gin-008ECF?style=for-the-badge&logo=gin&logoColor=white">
<img src="https://img.shields.io/badge/firebase-DD2C00?style=for-the-badge&logo=firebase&logoColor=white">
<img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
</div>

> 개씹상남자 오건우의 사진을 실시간으로 확인하고 관리할 수 있는
> **모바일 이미지 피드 서비스**

---

## 프로젝트 소개

오건우닷컴은 오건우에 대한 이미지를
모바일 환경에서 빠르고 직관적으로 확인할 수 있도록 만든
**이미지 아카이빙 & 피드형 앱 서비스**입니다.

기존 SNS처럼 분산된 이미지가 아니라,
하나의 플랫폼에서 최신 사진을 **즉시 확인**하고
과거 데이터까지 체계적으로 탐색할 수 있도록 설계되었습니다.

---

## 핵심 기능

### 홈 피드

* 최신 이미지 우선 노출
* 무한 스크롤 기반 피드
* Pull-to-refresh 지원

### 갤러리

* Grid 형태 이미지 목록
* 태그 기반 필터링

### 이미지 상세

* 전체 화면 이미지 뷰
* 설명 및 업로드 정보 확인

### 관리자 기능

* 이미지 업로드 (갤러리 / 카메라)
* 설명 및 태그 입력
* 이미지 삭제 및 관리

---

## 기술 스택

### 📱 Frontend

* Flutter
* Dio (HTTP Client)
* Riverpod (State Management)

### Backend

* Golang (Gin)
* GORM

### Infrastructure (예정)

* AWS S3 (이미지 저장)
* AWS EC2 (서버 배포)

---

## 아키텍처

```
Flutter App
     ↓
REST API
     ↓
Golang Server
     ↓
PostgreSQL + S3
```

---

## 주요 특징

* 📱 모바일 최적화된 UX (빠른 스크롤 & 로딩)
* ⚡ 최신 이미지 실시간 반영
* 🧩 확장 가능한 구조 (다중 인물, SNS화 가능)
* 🗂 이미지 기반 콘텐츠 관리 시스템 (CMS)

---

## 보안

* JWT 기반 인증
* HTTPS 통신
* 파일 업로드 검증 (MIME 타입, 확장자 제한)

---

## 성능 최적화

* 이미지 Lazy Loading
* CDN 캐싱 (S3 + CloudFront)
* Pagination 처리
* Flutter 이미지 캐싱

---

## 프로젝트 목적

이 프로젝트는 단순한 이미지 앱이 아닌,
다음과 같은 이유 때문에 진행하는 프로젝트 입니다:

* 오건우를 더 많은 사람들이 알았으면 하기에
* 오건우란 남자는 사진 **한장**으론 담을 수 없는 남자기에
* 걍 놀리고 싶어서

---

## 개발자

* 김세환(front(mobile), back, design)

---

## 한 줄 요약

> “오건우의, 오건우를 위한, 오건우에 의한 개쩌는 프로젝트”
