# 포켓몬 피규어 시장조사 대시보드 — 배포 가이드

## GitHub Pages로 배포 (무료, 5분 소요)

### 1단계: GitHub 계정 만들기
https://github.com/signup (이미 있으면 패스)

### 2단계: 새 저장소 만들기
1. github.com 로그인 후 우상단 "+" → "New repository"
2. Repository name: `pokemon-market` (원하는 이름)
3. ✅ Public 선택
4. ✅ Add a README file 체크
5. "Create repository" 클릭

### 3단계: 파일 업로드
1. 저장소 페이지에서 "Add file" → "Upload files"
2. `pokemon_market.html` 파일을 드래그 앤 드롭
3. ⚠️ 파일명을 `index.html`로 변경하거나,
   커밋 메시지 입력 후 "Commit changes"

### 4단계: GitHub Pages 활성화
1. 저장소 → "Settings" → 왼쪽 "Pages"
2. Source: "Deploy from a branch"
3. Branch: "main" / "(root)" 선택
4. "Save" 클릭

### 5단계: 링크 확인 (1~2분 후)
```
https://[내GitHub아이디].github.io/pokemon-market/pokemon_market.html
```

### 카톡으로 공유
위 링크를 카카오톡에 붙여넣기하면 미리보기 포함해서 공유됩니다!

---

## 앱 사용 방법

1. 링크 열기 → API 키 입력창 나타남
2. Anthropic API 키 입력 (sk-ant-api03-...)
   → https://console.anthropic.com 에서 발급 (무료 $5 크레딧 제공)
3. "홈" 탭의 빠른 분석 버튼 클릭하거나
   검색창에 직접 입력 후 "분석" 버튼
4. Claude가 웹 검색 후 실시간 분석 결과 표시

## API 키 안전성
- 키는 브라우저 sessionStorage에만 저장
- 탭 닫으면 자동 삭제
- 외부 서버로 전송되지 않음
- Anthropic API에만 직접 연결

