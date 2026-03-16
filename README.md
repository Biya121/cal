# ✦ BG3 Arcane Arithmetician ✦

Baldur's Gate 3 테마의 중세 판타지 스타일 웹 계산기입니다.

## 실행 방법

### 방법 1 — 파일 직접 열기 (가장 간단)
`index.html` 파일을 브라우저로 드래그하거나, 파일 탐색기에서 더블클릭합니다.

### 방법 2 — VS Code Live Server (추천)
1. VS Code에서 **Live Server** 확장 설치
2. `index.html` 파일을 열고 우하단 `Go Live` 클릭
3. 브라우저에서 `http://127.0.0.1:5500` 자동 오픈

### 방법 3 — Python 내장 서버
```powershell
# 프로젝트 폴더에서 실행
python -m http.server 8080
# 브라우저에서 http://localhost:8080 접속
```

### 방법 4 — Node.js (npx serve)
```powershell
npx serve .
# 브라우저에서 출력된 URL 접속
```

## 키보드 단축키

| 키 | 동작 |
|---|---|
| `0` ~ `9` | 숫자 입력 |
| `.` | 소수점 |
| `+` `-` `*` `/` | 사칙 연산자 |
| `Enter` 또는 `=` | 계산 |
| `Escape` | 전체 초기화 (AC) |
| `Backspace` | 현재 입력 초기화 (CE) |
| `%` | 퍼센트 |

## 기술 스택
- **HTML5** — 시맨틱 마크업, ARIA 접근성 속성
- **CSS3** — CSS Variables, Flexbox/Grid, 반응형 레이아웃
- **JavaScript (ES6+)** — `eval()` 미사용, 상태 머신 기반 안전한 계산 로직

## 디자인
- 폰트: [Cinzel / Cinzel Decorative](https://fonts.google.com/specimen/Cinzel) (Google Fonts)
- 중세 판타지 양피지·석재 UI 컨셉
- 버튼 색상 구분: 숫자(갈색), 연산자(심홍), 등호(금색), 클리어(녹색)
