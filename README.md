# 🧠 상식 퀴즈 게임 - 서비스 설명서

이 리포지토리는 **상식 퀴즈 게임**의 공식 서비스 설명서 웹사이트입니다.

## 🌐 Live Demo

배포된 사이트: [https://junotech-labs.github.io/game-about/](https://junotech-labs.github.io/game-about/)

## 📖 소개

현대적이고 인터랙티브한 웹 디자인으로 상식 퀴즈 게임의 모든 기능과 사용법을 설명합니다.

### 주요 기능

- ✨ 현대적인 그라디언트 배경과 애니메이션
- 🎨 인터랙티브한 카드 효과와 호버 애니메이션
- 📱 완벽한 반응형 디자인
- 🎯 스크롤 애니메이션과 부드러운 전환
- 📊 시각적인 등급 시스템 테이블
- 🚀 빠른 로딩과 최적화된 성능

## 🛠️ 기술 스택

- HTML5
- CSS3 (Custom animations, Gradients, Flexbox, Grid)
- Vanilla JavaScript (Intersection Observer, Smooth Scroll)

## 📁 프로젝트 구조

```
quiz-game-page/
├── .github/
│   └── workflows/
│       └── deploy.yml          # GitHub Actions CI/CD
├── docs/
│   └── index.html              # 메인 페이지
└── README.md                   # 프로젝트 설명
```

## 🚀 배포

이 프로젝트는 GitHub Actions를 통해 자동으로 배포됩니다.

### 배포 트리거

- `main` 브랜치에 Push할 때
- Pull Request가 생성될 때
- 수동으로 workflow 실행

### GitHub Pages 설정

1. 리포지토리 Settings로 이동
2. Pages 섹션 선택
3. Source를 "GitHub Actions"로 설정

## 💻 로컬 개발

```bash
# 저장소 클론
git clone https://github.com/junotech-labs/game-about.git
cd game-about

# 로컬 서버 실행 (Python 사용)
python -m http.server 8000

# 또는 Node.js 사용
npx serve docs
```

브라우저에서 [http://localhost:8000/docs/](http://localhost:8000/docs/)를 열어 확인하세요.

## 🎨 디자인 특징

### 색상 팔레트

- Primary: `#6366f1` (Indigo)
- Secondary: `#ec4899` (Pink)
- Accent: `#14b8a6` (Teal)
- Background: Dark theme with gradients

### 애니메이션

- Hero section의 그라디언트 애니메이션
- 스크롤 기반 섹션 페이드인
- 카드 호버 효과
- 진행 상황 바
- 패럴랙스 효과

## 📝 업데이트

내용을 수정하려면 `docs/index.html` 파일을 편집하고 main 브랜치에 커밋하세요.
GitHub Actions가 자동으로 변경사항을 배포합니다.

## 🔗 관련 링크

- [게임 웹 애플리케이션](https://github.com/junotech-labs/game-web)
- [Quiz API 서버](https://github.com/junotech-labs/quiz-api)

## 📄 라이선스

MIT License

---

<div align="center">
Made with ❤️ by Quiz Team
</div>
