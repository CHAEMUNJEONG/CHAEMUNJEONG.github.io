# 진출로 임박 위험 예방 서비스 - 웹사이트

2025 한신 AI·SW 페스티벌 창업경진대회 부문 프로젝트 웹사이트

## 프로젝트 소개

**'찰나의 부주의'를 5초 먼저 예측하다: DMS-V2V 융합 기반 진출로 사전 위험 차단 시스템**

고속도로 진출로에서 발생하는 급차선 변경 사고를 예방하기 위한 3-in-1 통합 예측 시스템을 소개하는 웹사이트입니다.

## 팀 정보

- **팀명**: 가던 길 안전하게 가세요 (가 안가)
- **팀장**: 정채문 (컴퓨터공학부, 202158099)
- **문의**: a8275151@hs.ac.kr

## 웹사이트 구조

```
ai_festival/
├── index.html          # 메인 페이지 (홈)
├── problem.html        # 문제 제기
├── solution.html       # 솔루션
├── technology.html     # 기술 구현
├── market.html         # 시장 분석
├── business.html       # 비즈니스 모델
├── team.html           # 팀 소개
├── styles.css          # 전체 스타일시트
├── images/             # 이미지 폴더
│   └── dms-60-degree.jpg  # DMS 60도 측정 이미지 (필요시 추가)
└── README.md           # 이 파일
```

## 사용 방법

1. **로컬에서 실행**
   - 모든 HTML 파일을 웹 브라우저에서 열면 됩니다
   - `index.html`을 먼저 열어주세요

2. **이미지 추가**
   - DMS 60도 측정 이미지는 `images/dms-60-degree.jpg` 경로에 추가하세요
   - 이미지가 없으면 이미지 영역이 표시되지 않을 수 있습니다
   - 다른 이미지를 추가하려면 HTML 파일에서 경로를 수정하세요

3. **GitHub Pages 배포**
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin [your-repository-url]
   git push -u origin main
   ```
   - GitHub 저장소 설정에서 Pages 기능을 활성화하세요
   - Source를 `main` 브랜치, `/ (root)`로 설정하세요

## 페이지 구성

### 1. 메인 페이지 (index.html)
- 프로젝트 소개
- 시스템 동작 시나리오
- 주요 특징

### 2. 문제 제기 (problem.html)
- 진출로 사고 통계
- 측면충돌의 위험성
- 반복되는 사고 원인

### 3. 솔루션 (solution.html)
- 3-in-1 통합 예측 시스템
- 특허 비교 및 차별성
- 통신 핵심 성능

### 4. 기술 구현 (technology.html)
- DMS (운전자 모니터링)
- V2V 통신
- 네비게이션 연동
- 실증 환경
- AI 분석 및 모델링

### 5. 시장 분석 (market.html)
- TAM/SAM/SOM
- 시장 성장 전망
- 시장 성장 동인

### 6. 비즈니스 모델 (business.html)
- 수익 구조
- 타겟 시장
- 사회적 가치
- 기대효과

### 7. 팀 소개 (team.html)
- 팀 정보
- 프로젝트 정보
- 참고문헌
- 문의처

## 기술 스택

- HTML5
- CSS3 (반응형 디자인)
- 순수 JavaScript 없이 HTML/CSS만 사용

## 주요 특징

- ✅ 반응형 웹 디자인 (모바일, 태블릿, 데스크톱 지원)
- ✅ 현대적이고 깔끔한 UI/UX
- ✅ 하이퍼텍스트 기반 페이지 네비게이션
- ✅ 일관된 디자인 시스템
- ✅ 접근성 고려

## 커스터마이징

### 색상 변경
`styles.css` 파일의 `:root` 변수에서 색상을 변경할 수 있습니다:

```css
:root {
    --primary-blue: #1e3a8a;
    --accent-orange: #f97316;
    /* ... 기타 색상 */
}
```

### 내용 수정
각 HTML 파일을 열어 내용을 수정하세요.

## 라이센스

이 프로젝트는 2025 한신 AI·SW 페스티벌 창업경진대회를 위한 것으로, 교육 및 학술 목적으로 사용됩니다.

## 문의

프로젝트 관련 문의사항이 있으시면 다음으로 연락주세요:

- **이메일**: a8275151@hs.ac.kr
- **팀명**: 가던 길 안전하게 가세요 (가 안가)

---

© 2025 가던 길 안전하게 가세요 (가 안가). All rights reserved.

