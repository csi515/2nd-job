# CRM 시스템 - 에스테틱 샵

에스테틱 샵을 위한 고객 관계 관리(CRM) 시스템입니다.

## 🚀 기능

- **고객 관리**: 고객 정보 등록, 수정, 조회
- **예약 관리**: 예약 등록, 일정 관리, 상태 추적
- **재무 관리**: 매출, 지출, 수익 관리 및 분석
- **상품 관리**: 서비스 상품 등록 및 관리
- **적립금 관리**: 고객 적립금 적립 및 사용 관리
- **설정**: 시스템 설정 및 환경 구성

## 📁 프로젝트 구조

```
src/
├── components/        # 공통 UI 컴포넌트
│   └── Sidebar.tsx   # 사이드바 네비게이션
├── pages/            # 페이지 컴포넌트
│   ├── Dashboard.tsx
│   ├── CustomerManagement.tsx
│   ├── AppointmentManagement.tsx
│   ├── FinanceManagement.tsx
│   ├── PointManagement.tsx
│   └── Settings.tsx
├── types/            # TypeScript 타입 정의
│   └── index.ts
├── utils/            # 유틸리티 함수
│   └── csvHandler.ts
├── data/             # CSV 데이터 파일
├── App.tsx           # 메인 앱 컴포넌트
├── main.tsx          # 앱 진입점
├── App.css           # 앱 스타일
└── index.css         # 전역 스타일
```

## 🛠️ 기술 스택

- **Frontend**: React 18, TypeScript
- **Styling**: Tailwind CSS
- **Build Tool**: Vite
- **Routing**: React Router DOM
- **Data Management**: CSV 파일 기반 로컬 저장

## 📦 설치 및 실행

### 필수 요구사항
- Node.js 16.0.0 이상
- npm 또는 yarn

### 설치
```bash
npm install
```

### 개발 서버 실행
```bash
npm run dev
```

### 빌드
```bash
npm run build
```

### 미리보기
```bash
npm run preview
```

## 🔧 개발

### 스크립트
- `npm run dev`: 개발 서버 실행 (포트 3000)
- `npm run build`: 프로덕션 빌드
- `npm run preview`: 빌드된 앱 미리보기
- `npm run lint`: ESLint 검사
- `npm run type-check`: TypeScript 타입 검사

### 코드 구조
- **컴포넌트**: 재사용 가능한 UI 컴포넌트
- **페이지**: 각 기능별 페이지 컴포넌트
- **타입**: TypeScript 인터페이스 및 타입 정의
- **유틸리티**: 공통 함수 및 헬퍼

## 📊 데이터 관리

시스템은 CSV 파일을 사용하여 데이터를 로컬에 저장합니다:
- `src/data/customers.csv`: 고객 정보
- `src/data/appointments.csv`: 예약 정보
- `src/data/services.csv`: 서비스 정보
- `src/data/finance.csv`: 재무 데이터

## 🎨 UI/UX

- **반응형 디자인**: 모바일, 태블릿, 데스크톱 지원
- **다크/라이트 모드**: 사용자 선호도에 따른 테마 변경
- **직관적 네비게이션**: 사이드바 기반 메뉴 구조
- **모던 UI**: Tailwind CSS 기반 깔끔한 디자인

## 🔒 보안

- 모든 데이터는 로컬에 저장됩니다
- 외부 API 의존성 없음
- 개인정보 보호 준수

## 📝 라이선스

MIT License

## 🤝 기여

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📞 지원

문제가 발생하거나 질문이 있으시면 이슈를 생성해주세요. 