# ETF 투자 보고서 PWA

## 파일 구조
```
etf-report-app/
├── public/
│   ├── index.html      ← 메인 앱
│   └── manifest.json   ← PWA 설정
└── vercel.json         ← 배포 설정
```

## 배포 순서

### 1. GitHub 가입 & 리포지토리 생성
1. github.com 가입
2. New repository → 이름: etf-report-app
3. Public 선택 → Create repository

### 2. 파일 업로드
1. 리포지토리 페이지에서 "uploading an existing file" 클릭
2. 폴더째 드래그 앤 드롭 (public 폴더 + vercel.json)
3. Commit changes 클릭

### 3. Vercel 배포
1. vercel.com 가입 (GitHub 계정으로 로그인)
2. New Project → Import → etf-report-app 선택
3. Deploy 클릭
4. 배포 완료 후 URL 확인 (예: etf-report-app.vercel.app)

### 4. Claude API 키 발급
1. console.anthropic.com 접속
2. API Keys → Create Key
3. 앱 설정(⚙️)에 입력

### 5. Android 홈화면 설치
1. Chrome에서 배포된 URL 접속
2. 우상단 메뉴(⋮) → "홈 화면에 추가"
3. 설치 완료 → 앱처럼 실행됨

## 사용법
1. ETF 종가 입력 (MTS에서 확인 후 입력)
2. 이란 시나리오 슬라이더 조정
3. 장전/장중/마감 버튼 탭
4. 보고서 확인 후 📧 메일 버튼으로 Gmail 발송
