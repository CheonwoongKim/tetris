# 🎮 Vue Tetris Game

Vue.js 3와 Vuetify를 사용하여 제작한 모던한 테트리스 게임입니다.

## ✨ 특징

### 🎨 Modern Material Design
- **Vuetify 3** 컴포넌트 기반 UI
- **다크 테마**와 아름다운 그라디언트
- **Material Design 아이콘**과 부드러운 애니메이션
- **백드롭 블러 효과**로 현대적인 느낌

### 🎯 게임 기능
- **완전한 테트리스 게임플레이**
- **7가지 블록 타입** (I, O, T, S, Z, J, L)
- **스마트 점수 시스템** (라인별 점수 차등 지급)
- **레벨별 난이도 조절** (속도 증가)
- **다음 블록 미리보기**
- **게임 통계 대시보드**

### 📱 반응형 디자인
- **데스크톱/태블릿/모바일** 완벽 지원
- **터치 컨트롤** (모바일용)
- **적응형 레이아웃**
- **다양한 화면 크기 최적화**

### 🎮 조작법
- **←→**: 좌우 이동
- **↓**: 빠른 낙하 (점수 +1)
- **↑**: 블록 회전
- **스페이스**: 하드 드롭 (점수 +2)
- **P**: 일시정지/재개

## 🚀 빠른 시작

### 1. 기본 버전 (HTML + CSS + JS)
```bash
# tetris.html 파일을 브라우저에서 열기
open tetris.html
```

### 2. Vuetify 버전 (Vue.js 3 + Vuetify)
```bash
# tetris-vuetify.html 파일을 브라우저에서 열기
open tetris-vuetify.html
```

## 🎯 점수 시스템

| 라인 수 | 점수 공식 | 예시 (레벨 1) |
|---------|-----------|---------------|
| 1줄 | 40 × 레벨 | 40점 |
| 2줄 | 100 × 레벨 | 100점 |
| 3줄 | 300 × 레벨 | 300점 |
| 4줄 | 1200 × 레벨 | 1200점 |

- **빠른 낙하**: +1점
- **하드 드롭**: +2점
- **레벨 업**: 10줄 클리어할 때마다
- **속도 증가**: 레벨업 시 블록 낙하 속도 증가

## 🛠 기술 스택

### 기본 버전
- **HTML5**
- **CSS3** (Flexbox, Grid, 애니메이션)
- **Vanilla JavaScript** (ES6+)

### Vuetify 버전
- **Vue.js 3** (Composition API)
- **Vuetify 3** (Material Design)
- **Material Design Icons**
- **CDN 기반** (별도 빌드 불필요)

## 📱 화면 미리보기

### 데스크톱
- 사이드바와 함께 표시되는 풀 레이아웃
- 게임 보드, 점수, 다음 블록이 한 눈에
- 키보드 조작 가이드 포함

### 모바일
- 세로 화면 최적화 레이아웃
- 터치 컨트롤 버튼 제공
- 반응형 그리드와 적응형 크기

## 🎨 시각적 효과

- **점수 글로우 애니메이션**
- **레벨 뱃지 펄스 효과**
- **블록별 고유 그라디언트**
- **부드러운 트랜지션**
- **Material Design 리플 효과**

## 🏆 게임 목표

1. **떨어지는 블록**을 조작하여 **가로줄을 완성**
2. **완성된 줄이 사라지며** 점수 획득
3. **높은 점수**와 **오랜 생존**이 목표
4. **블록이 맨 위에 닿으면** 게임 오버

## 📄 라이선스

이 프로젝트는 MIT 라이선스 하에 배포됩니다.

## 🤝 기여하기

버그 리포트, 기능 제안, 코드 기여를 환영합니다!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

🎮 **즐거운 테트리스 게임을 즐겨보세요!** 🎮