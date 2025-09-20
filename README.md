# FastAPI To-Do App

간단한 To-Do List 관리 웹 애플리케이션입니다.  
FastAPI 백엔드와 HTML/JavaScript 프론트엔드로 구현되었습니다.  

---

## 🚀 Version
**Version 2.0.0**  
(2025-09-20 릴리즈)

---

## 📋 Release Note

### ✨ 기능 추가
- 완료된 할 일 / 진행 중인 할 일 필터 버튼 추가 (`Show Completed`, `Show Active`)
- 할 일 상태 토글 버튼 추가 (`Mark Complete / Mark Incomplete`)
- 개별 할 일 수정(Edit) 기능 추가 (제목, 설명, 완료 여부 변경 가능)

### 🐛 버그 수정
- 신규 To-Do 추가 시 입력창 초기화 안 되던 문제 수정
- 삭제 후 목록이 즉시 반영되지 않던 문제 수정

### ⚡ 개선 사항
- 전체 UI를 더 직관적으로 개선 (버튼 및 라벨 정리)
- 코드 리팩토링: API 호출 중복 제거, fetch 함수 최적화

---

## 📦 설치 및 실행 방법

### 1. 저장소 클론
```bash
git clone https://github.com/baegseoyeon99-collab/FastApi_Todos.git
cd FastApi_Todos
