# 중앙청 거래실적 대시보드

2021년 이후 중앙청과 거래실적 데이터를 시각화한 인터랙티브 대시보드입니다.

## 기능

- 📊 **실시간 데이터 시각화**: 월별, 연도별 거래량 및 금액 추이
- 📈 **다양한 차트**: 선형 차트, 막대 차트, 도넛 차트, 산점도
- 🔍 **필터링 기능**: 연도, 카테고리, 지표별 필터링
- 📱 **반응형 디자인**: 모바일, 태블릿, 데스크톱 지원
- 💰 **통계 요약**: 총 거래량, 금액, 수수료, 월평균 등

## 데이터 구조

- **채소**: 물량(kg), 금액(원), 수수료(원)
- **과일**: 물량(kg), 금액(원), 수수료(원)
- **합계**: 총 물량, 총 금액, 총 수수료

## 배포 방법

### 1. 정적 호스팅 (추천)

#### GitHub Pages
1. GitHub 저장소 생성
2. `index.html` 파일 업로드
3. Settings > Pages에서 배포 설정

#### Netlify
1. [Netlify](https://netlify.com) 접속
2. 드래그 앤 드롭으로 `index.html` 업로드
3. 자동 배포 완료

#### Vercel
1. [Vercel](https://vercel.com) 접속
2. 프로젝트 폴더 업로드
3. 자동 배포 완료

### 2. 로컬 서버

```bash
# Python 3
python -m http.server 8000

# Node.js (http-server 설치 필요)
npx http-server

# PHP
php -S localhost:8000
```

## 기술 스택

- **HTML5**: 시맨틱 마크업
- **CSS3**: Flexbox, Grid, 애니메이션
- **JavaScript**: ES6+, Chart.js
- **Chart.js**: 데이터 시각화
- **반응형 디자인**: 모바일 퍼스트

## 브라우저 지원

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 라이선스

MIT License
