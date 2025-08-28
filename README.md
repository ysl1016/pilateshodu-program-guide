# 필라테스 호두 강사 교육 포털

![Pilates HODU](https://img.shields.io/badge/Pilates-HODU-navy?style=for-the-badge)
![Instructor Portal](https://img.shields.io/badge/Instructor-Portal-gold?style=for-the-badge)
![Medical Pilates](https://img.shields.io/badge/Medical-Pilates™-green?style=for-the-badge)

## 🎯 프로젝트 개요

**필라테스 호두 강사 교육 포털**은 필라테스 호두의 강사 및 직원을 위한 종합적인 교육 자료 제공 시스템입니다. 웹사이트 리뉴얼과 함께 강화된 프로그램 운영을 위한 가이드와 AI 기반 교육 자료를 제공합니다.

## 🌟 주요 기능

### 📚 프로그램 가이드
- **7가지 맞춤형 케어 프로그램** 상세 가이드
- 각 프로그램별 운영 프로토콜 및 지도안
- 단계별 실행 체크리스트
- 전문적인 블로그 형태의 상세 내용 제공

### 🤖 AI 기반 교육 가이드
- **NotebookLM**을 활용한 인터랙티브 학습
- 팟캐스트: "7가지 맞춤형 케어의 핵심 원리"
- AI와의 상호작용을 통한 질의응답

### 🎭 인터랙티브 요소
- **마우스 추적 눈동자 모듈**: 히어로 섹션의 주의 환기 요소
- 부드러운 스크롤 애니메이션
- 카드 호버 효과 및 페이드인 애니메이션

### 📖 교육 자료 다운로드
- **PDF 가이드**: 상세한 프로그램 안내 및 지도안
- **음성 가이드**: 핵심 원리 학습을 위한 오디오 자료
- 언제든지 접근 가능한 오프라인 학습 자료

## 🏗️ 기술 스택

- **Frontend**: HTML5, CSS3, JavaScript ES6+
- **CSS Framework**: Tailwind CSS (CDN)
- **Icons**: Font Awesome 6.4.0
- **Fonts**: Google Fonts (Manrope, Inter, Noto Sans KR)
- **Responsive Design**: Mobile-first 접근법
- **Animations**: Intersection Observer API, CSS Transitions
- **Interactive Elements**: Mouse tracking, Eye movement simulation

## 🎨 디자인 시스템

### 컬러 팔레트
- **Deep Navy (#001F3F)**: 메인 브랜드 컬러
- **Golden Brown (#996515)**: 보조 액센트 컬러
- **Warm Beige (#F5F1E8)**: 배경 컬러
- **Soft Cream (#FEFCF8)**: 라이트 배경

### 타이포그래피
- **한글**: Noto Sans KR
- **영문**: Manrope (로고 및 주요 텍스트)
- **디스플레이**: Inter (보조 텍스트)

### 로고 디자인
- **PILATES**: Manrope 폰트, Deep Navy 색상, Bold (700)
- **HODU**: Manrope 폰트, Golden Brown 색상, Bold (700)
- **간격**: ml-1 (0.25rem) - 웹사이트와 동일한 간격

## 📱 페이지 구조

```
index.html
├── Header (네비게이션 + PILATES HODU 로고)
├── Hero Section (인터랙티브 눈동자 모듈 + 메인 소개)
├── Programs Overview (7가지 프로그램 상세 카드)
│   ├── 통증재활 필라테스
│   ├── 마네킹톤 필라테스
│   ├── 플랫스콜 프로그램
│   ├── 골프 필라테스
│   ├── 키즈/청소년 성장 필라테스
│   ├── 프리내털&포스트내털 필라테스
│   └── 시니어 필라테스
├── NotebookLM AI Guide (AI 가이드 섹션)
└── Footer (연락처 및 링크)
```

## 🚀 시작하기

### 1. 로컬 개발 환경 설정
```bash
# 프로젝트 클론
git clone [repository-url]
cd pilatesdhodu-program-guide

# 로컬 서버 실행 (Python)
python -m http.server 8000

# 또는 Node.js
npx serve .

# 또는 브라우저에서 직접 열기
open index.html
```

### 2. 브라우저에서 확인
```
http://localhost:8000
```

## 📋 프로그램 상세 가이드

### 1. **통증재활 필라테스**
- **목표**: 만성 통증 완화 및 기능 회복
- **대상**: 척추 질환, 관절염, 근골격계 질환 환자
- **참고문헌**: 프로그램 소개, PART1_통증재활 프로그램의 기초 (2019), 의학적 필라테스의 원리와 적용
- **자문**: 가정의학과/안테에이징 전문의 이용승

### 2. **마네킹톤 필라테스**
- **목표**: 체중감량 및 비만체형관리
- **대상**: 체중관리가 필요한 성인
- **참고문헌**: 프로그램 소개, PART2_마네킹톤 프로그램의 기초 (2019), 건강한 다이어트를 위한 필라테스 운동
- **자문**: 가정의학과/안테에이징 전문의 이용승

### 3. **플랫스콜 프로그램**
- **목표**: 척추측만증 개선 및 체형교정
- **대상**: 척추측만증 환자, 체형 불균형 개선이 필요한 성인
- **참고문헌**: 프로그램 소개, 척추측만증 운동치료, 슈로스 메소드

### 4. **골프 필라테스**
- **목표**: 스윙 개선 및 비거리 향상
- **대상**: 골프 성능 향상을 원하는 골퍼
- **참고문헌**: 프로그램 소개, 골프 생체역학, Medical Pilates™ Golf Master

### 5. **키즈/청소년 성장 필라테스**
- **목표**: 성장촉진 및 체형교정
- **대상**: 성장기 아동청소년
- **참고문헌**: 프로그램 소개, 성장기 운동치료, 청소년 체형교정

### 6. **프리내털&포스트내털 필라테스**
- **목표**: 산전/산후 관리 및 체형교정
- **대상**: 임산부 및 산후 여성
- **참고문헌**: 프로그램 소개, 임산부 운동치료, 산후 회복 운동

### 7. **시니어 필라테스**
- **목표**: 근력 유지 및 균형감 강화
- **대상**: 중장년 및 노인
- **참고문헌**: 프로그램 소개, 노인 운동치료, 낙상 예방 운동

## 🔗 외부 링크

- **NotebookLM AI 가이드**: [AI 가이드 바로가기](https://notebooklm.google.com/notebook/3161dbc2-9c84-4ec6-827f-4c60eb4945ee?artifactId=8d3c9f7b-fa01-44c2-a8a1-01753cf246e0)
- **공식 웹사이트**: [필라테스 호두](https://ysl1016.github.io/pilateshodu/)

## 📁 파일 구조

```
pilatesdhodu-program-guide/
├── index.html              # 메인 랜딩페이지 (최신 디자인)
├── index_backup.html       # 백업 파일
├── README.md              # 프로젝트 문서
├── data/                  # 교육 자료 파일
│   ├── PILATES HODU 프로그램 안내 및 지도안 (Pilates Hodu Program Guides & Lesson Plans).docx.md
│   └── 필라테스,_통증부터_치매_예방까지!_7가지_맞춤형_케어의_핵심_원리_파헤치기.m4a
└── Interactive Eye-Following Card (Community)/  # 디자인 참고 프로젝트
    ├── src/
    │   ├── App.tsx
    │   ├── components/
    │   │   ├── EyeCard.tsx
    │   │   └── Eye.tsx
    │   └── styles/
    │       └── globals.css
    └── vite.config.ts
```

## 🎯 사용 대상

- **필라테스 호두 강사진**
- **신규 입사 직원**
- **프로그램 운영 담당자**
- **교육 및 훈련 담당자**

## 🔧 커스터마이징

### 색상 변경
`index.html`의 CSS 변수를 수정하여 브랜드 컬러를 변경할 수 있습니다:

```css
:root {
    --deep-navy: #001F3F;      /* 메인 컬러 */
    --golden-brown: #996515;   /* 보조 컬러 */
    --warm-beige: #F5F1E8;    /* 배경 컬러 */
    --soft-cream: #FEFCF8;     /* 라이트 배경 */
}
```

### 폰트 변경
Google Fonts 링크를 수정하여 다른 폰트를 사용할 수 있습니다:

```html
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&family=Manrope:wght@300;400;500;600;700&display=swap" rel="stylesheet">
```

### 콘텐츠 수정
각 섹션의 HTML 내용을 직접 수정하여 프로그램 정보나 가이드 내용을 업데이트할 수 있습니다.

## 🆕 최근 업데이트

### v2.0 (2024년)
- **디자인 시스템 완전 재구성**: Interactive Eye-Following Card 프로젝트 기반
- **인터랙티브 눈동자 모듈**: 히어로 섹션에 마우스 추적 기능 추가
- **카드 크기 통일**: 모든 프로그램 섹션의 레이어 크기 통일
- **로고 디자인 개선**: 웹사이트와 동일한 PILATES HODU 로고 적용
- **폰트 시스템**: Manrope, Inter, Noto Sans KR 통합
- **참고문헌 업데이트**: 가정의학과/안테에이징 전문의 이용승 자문 정보 추가

### v1.0 (2024년)
- 기본 프로그램 가이드 구조 구축
- 7가지 프로그램 상세 내용 구현
- AI 가이드 섹션 추가

## 📞 문의 및 지원

- **주소**: 서울특별시 서초구 신반포로 33길 27, 2층
- **전화**: 02-547-3345
- **이메일**: pilateshodu@naver.com

## 📄 라이선스

© 2024 필라테스 호두. 모든 권리 보유.  
메디컬필라테스™는 등록상표입니다.

---

**🏥 의학적 전문성** | **🎯 체계적 교육** | **🤖 AI 기반 학습** | **👁️ 인터랙티브 경험**