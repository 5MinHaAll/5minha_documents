# Git Rules

## 📝 커밋 메시지 컨벤션

커밋 메시지 구조:
```
<type>: <description>
```

### Development 저장소

주요 커밋 타입:
- Init: 프로젝트 초기 설정, 새로운 파일 추가
- Feat: 새로운 기능 추가
- Fix: 버그 수정
- Refactor: 코드 리팩토링
- Style: 코드 포맷팅, 세미콜론 누락 등 (코드 변경 없음)
- Design: 사용자 UI 디자인 변경
- Test: 테스트 코드 추가
- Chore: 빌드 작업 수정, 패키지 매니저 설정 등

예시:
```
Init: team_intro_2 기반 프로젝트 초기 설정
Feat: 로그인 기능 구현
Fix: 회원가입 시 이메일 중복 체크 오류 수정
Refactor: 사용자 인증 로직 개선
Style: 들여쓰기 통일
Test: 로그인 기능 단위 테스트 추가
Chore: package.json 의존성 업데이트
```

### Documents 저장소

주요 커밋 타입:
- Add: 새로운 문서 추가
- Update: 기존 문서 내용 업데이트
- Delete: 문서 삭제

예시:
```
Add: 프로젝트 설정 가이드 문서 추가
Update: README 파일 프로젝트 소개 섹션 업데이트
Delete: 사용하지 않는 API 문서 삭제
```

### 커밋 메시지 작성 규칙:
- 한글로 작성
- 현재 시제 사용
- 간결하고 명확하게 작성

## 🌿 브랜치 전략

- main: 제품 출시 버전
- develop: 개발 중인 버전
- feature: 기능 개발

### 브랜치 명명 규칙:
- feature 브랜치: `feature/기능이름`

예시:
```
main
develop
feature/login
feature/signup
```
## 🚀 Pull Request 규칙

1. PR을 생성하기 전에 최신 `develop` 브랜치 내용 반영
2. PR 제목은 커밋 메시지 컨벤션을 따름
3. 변경 사항에 대한 간단한 설명 포함
4. 코드 리뷰어 지정
5. 리뷰어 승인 후 병합 진행
