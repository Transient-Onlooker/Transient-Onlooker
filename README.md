# 👋 Transient-Onlooker

<div align="center">

<img width="100%" alt="english_black" src="https://github.com/user-attachments/assets/e1341020-7916-41a0-bead-fe3ca6030ef8" />

<br/>

### 고등학생 개발자 | 시스템 설계 · 역학 모델링 · 앱 개발

Kotlin, TypeScript, Python을 중심으로  
과학 모델링과 실사용 도구를 만드는 개발자입니다.

<br/>

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Transient-Onlooker)
[![Projects](https://img.shields.io/badge/🎯%20Projects-111111?style=for-the-badge)](#-대표-프로젝트)
[![Contact](https://img.shields.io/badge/Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)](#-연결)

</div>

---

## 🚀 About Me

항공우주공학과 시스템 설계에 관심이 많은 고등학생 개발자입니다.

수학·과학 모델을 코드로 구현하고, 실제로 사용할 수 있는 앱과 자동화 도구로 확장하는 데 집중하고 있습니다.  
안드로이드 앱 개발, 전염병 확산 모델링, OMR 자동화, AI 기반 단어장 생성기 등 다양한 아이디어를 직접 프로젝트로 구체화하고 있습니다.

---

## 🎯 대표 프로젝트

### 1. [openflight4and](https://github.com/Transient-Onlooker/openflight4and)

안드로이드 기반 집중 타이머 앱입니다.  
FocusFlight를 벤치마킹하여, 사용자가 집중 시간을 관리하고 몰입을 유지할 수 있도록 설계했습니다.

최근에는 Firebase 계정 연동, Google Sign-In, Google Maps / Maps 3D SDK, AdMob 보상형 광고, CI 빌드 파이프라인 등을 통합하며 실제 앱 서비스에 가까운 구조로 확장하고 있습니다.

**주요 특징**

- Kotlin + Jetpack Compose 기반 안드로이드 앱
- Firebase Auth 기반 계정 연동
- Google Sign-In 통합
- Google Maps SDK / Maps 3D SDK 연동
- AdMob rewarded ad 통합
- Room, DataStore, Kotlin Serialization 기반 로컬 데이터 관리
- GitHub Actions 기반 CI 빌드 흐름 구성

**Tech**

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-DD2C00?style=flat-square&logo=firebase&logoColor=white)
![Google Maps](https://img.shields.io/badge/Google%20Maps-4285F4?style=flat-square&logo=googlemaps&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle%20KTS-02303A?style=flat-square&logo=gradle&logoColor=white)

---

### 2. SIR Model Series

전염병 확산을 수학적 모델로 분석하고 시각화한 프로젝트 시리즈입니다.  
고전 SIR 모델부터 미분방정식 기반 모델, 웹 기반 SEIRS 시뮬레이터까지 확장했습니다.

**Repositories**

- [sir-model-classic](https://github.com/Transient-Onlooker/sir-model-classic.git)  
  고전 SIR 모델을 GUI 기반으로 구현한 기초 시뮬레이터

- [sir-model-differential-equations](https://github.com/Transient-Onlooker/sir-model-differential-equations.git)  
  SIR / SEIRS 미분방정식 기반 감염 확산 분석 프로젝트

- [sir-model-diff-web](https://github.com/Transient-Onlooker/sir-model-diff-web.git)  
  TypeScript + Vite 기반 웹 시뮬레이터  
  [Demo](https://sir-model.mcv.kr/)

**주요 특징**

- SIR / SEIRS 감염병 확산 모델 구현
- 미분방정식 기반 수치 시뮬레이션
- 파라미터 변화에 따른 감염 곡선 분석
- Python GUI 버전과 TypeScript 웹 버전으로 확장
- NumPy, Matplotlib, SciPy 기반 분석 흐름 구현

**Tech**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square&logo=python&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)

---

### 3. Vocab Generator Series

AI를 활용해 영어 단어장을 생성하는 프로젝트 시리즈입니다.  
Gemini API 기반 Python GUI 버전과 OpenAI API 기반 Go TUI 버전으로 나누어 실험했습니다.

**Repositories**

- [gemini-vocab-generator](https://github.com/Transient-Onlooker/gemini-vocab-generator.git)  
  Gemini API 기반 영어 단어장 생성기

- [chatgpt-vocab-generator](https://github.com/Transient-Onlooker/chatgpt-vocab-generator.git)  
  OpenAI API 기반 Go TUI 단어장 생성기

**주요 특징**

- AI 기반 영어 단어장 자동 생성
- Gemini API / OpenAI API 연동 경험
- Python Tkinter GUI 구현
- Go Bubble Tea 기반 TUI 구현
- 실제 학습 보조 도구로 사용할 수 있는 구조 실험

**Tech**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Tkinter](https://img.shields.io/badge/Tkinter-FFD43B?style=flat-square&logo=python&logoColor=black)
![Gemini API](https://img.shields.io/badge/Gemini%20API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![OpenAI API](https://img.shields.io/badge/OpenAI%20API-412991?style=flat-square&logo=openai&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)

---

### 4. [newomr](https://github.com/Transient-Onlooker/newomr)

OMR, 즉 광학 마크 인식을 자동화하는 웹 기반 프로젝트입니다.  
기존 OMR 프로젝트를 개선하여 3모서리식 인식 알고리즘을 도입한 버전입니다.

[Demo](https://autoomr.mcv.kr)

**주요 특징**

- React + TypeScript 기반 OMR 채점 웹앱
- 3모서리식 인식 알고리즘 도입
- 그리드 확대경 모드 구현
- 일괄 수정 및 선택 그룹 답안 편집 기능
- 기존 `autoomr` 프로젝트를 대체하는 개선 버전
- GitHub Pages 기반 배포 흐름 구성

**Tech**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)

---

### 5. [WorldWords](https://github.com/Transient-Onlooker/WorldWords)

영어 단어 학습을 위한 안드로이드 앱입니다.  
단어 학습 경험을 모바일 환경에서 더 편하게 만들기 위해 개발한 프로젝트입니다.

**주요 특징**

- Kotlin 기반 안드로이드 앱
- Jetpack Compose 계열 구조 활용
- 영어 단어 학습 기능 구현
- 모바일 앱 UI/UX 설계
- 학습 도구로 사용할 수 있는 앱 구조 설계

**Tech**

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white)

---

## 🛠️ Tech Stack & Tools

### Main Languages

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

### Frontend / App

![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tkinter](https://img.shields.io/badge/Tkinter-FFD43B?style=flat-square&logo=python&logoColor=black)

### Backend / Cloud / API

![Firebase](https://img.shields.io/badge/Firebase-DD2C00?style=flat-square&logo=firebase&logoColor=white)
![Google Maps SDK](https://img.shields.io/badge/Google%20Maps%20SDK-4285F4?style=flat-square&logo=googlemaps&logoColor=white)
![Cloudflare Workers](https://img.shields.io/badge/Cloudflare%20Workers-F38020?style=flat-square&logo=cloudflareworkers&logoColor=white)
![AdMob](https://img.shields.io/badge/AdMob-EA4335?style=flat-square&logo=googleadmob&logoColor=white)
![Gemini API](https://img.shields.io/badge/Gemini%20API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![OpenAI API](https://img.shields.io/badge/OpenAI%20API-412991?style=flat-square&logo=openai&logoColor=white)

### Scientific / Simulation

![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square&logo=python&logoColor=white)
![SIR Model](https://img.shields.io/badge/SIR%20Model-Scientific%20Modeling-blue?style=flat-square)
![SEIRS Simulation](https://img.shields.io/badge/SEIRS-Simulation-blueviolet?style=flat-square)

### Tools

![Android Studio](https://img.shields.io/badge/Android%20Studio-3DDC84?style=flat-square&logo=androidstudio&logoColor=white)
![Gradle KTS](https://img.shields.io/badge/Gradle%20KTS-02303A?style=flat-square&logo=gradle&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)
![Fusion 360](https://img.shields.io/badge/Fusion%20360-FF6600?style=flat-square&logo=autodesk&logoColor=white)
![Codex CLI](https://img.shields.io/badge/Codex%20CLI-111111?style=flat-square&logo=openai&logoColor=white)
![Gemini CLI](https://img.shields.io/badge/Gemini%20CLI-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)

### Secondary / Used Before

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Bubble Tea](https://img.shields.io/badge/Bubble%20Tea-TUI-FF69B4?style=flat-square)
![Wails](https://img.shields.io/badge/Wails-Go%20GUI-DF0000?style=flat-square)

---

<details>
<summary>📁 Other Projects</summary>

<br/>

| 프로젝트 | 설명 | 기술 |
|---|---|---|
| [se3cdocs](https://github.com/Transient-Onlooker/se3cdocs) | SE3C 동아리 공식 문서 포털. Markdown 기반 문서를 React로 렌더링하고 커스텀 도메인으로 배포한 문서화 웹사이트 | ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white) |
| [openjacks](https://github.com/Transient-Onlooker/openjacks) | React + Express 기반 웹앱. API 서버 연동 구조와 배포 설정을 포함한 웹 프로젝트 | ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white) |
| [chat-application](https://github.com/Transient-Onlooker/chat-application) | WebSocket 기반 실시간 채팅 서버/클라이언트 | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![WebSocket](https://img.shields.io/badge/WebSocket-000000?style=flat-square&logoColor=white) |
| [golf-schedule-generator](https://github.com/Transient-Onlooker/golf-schedule-generator) | JSON 입력 기반 골프 대회 일정 자동 생성 GUI 툴 | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Tkinter](https://img.shields.io/badge/Tkinter-FFD43B?style=flat-square&logo=python&logoColor=black) |
| [personnel-management-spreadsheet](https://github.com/Transient-Onlooker/personnel-management-spreadsheet) | 인원 관리용 Python 데스크탑 앱. 실행 파일 빌드까지 포함한 도구형 프로젝트 | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Tkinter](https://img.shields.io/badge/Tkinter-FFD43B?style=flat-square&logo=python&logoColor=black) |
| [music-box-score-converter](https://github.com/Transient-Onlooker/music-box-score-converter) | 오르골 악보 숫자 표기를 MIDI로 변환하는 Python 스크립트 | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![MIDI](https://img.shields.io/badge/MIDI-5A4FCF?style=flat-square&logoColor=white) |
| [kim-game](https://github.com/Transient-Onlooker/kim-game) | Python 기반 미니 게임 프로젝트 | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) |

</details>

---

<details>
<summary>🧪 Archived / Experimental Projects</summary>

<br/>

| 프로젝트 | 시도한 것 | 배운 점 |
|---|---|---|
| [chatgpt-vocab-generator-wails](https://github.com/Transient-Onlooker/chatgpt-vocab-generator-wails.git) | ChatGPT 단어장 생성기의 Wails GUI 버전 | Go/Wails 기반 GUI 앱의 크로스 컴파일 제약 확인 |
| [chatgpt-vocab-generator-python](https://github.com/Transient-Onlooker/chatgpt-vocab-generator-python.git) | Python 기반 ChatGPT 단어장 생성기 | Python 앱 배포와 크로스 컴파일의 한계 확인 |
| [autoomr](https://github.com/Transient-Onlooker/autoomr.git) | 초기 OMR 자동화 프로젝트 | 3모서리식 알고리즘 도입 후 `newomr`로 구조 개선 |
| [HWPXport](https://github.com/Transient-Onlooker/HWPXport.git) | 시험지를 HWP 형식으로 생성하는 앱 | HWPX 문서 구조의 복잡성과 자동화 한계 이해 |

</details>

---

<details>
<summary>📊 GitHub Activity & Stats</summary>

<br/>

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=Transient-Onlooker&theme=tokyo-night&hide_border=true&area=true)](https://github.com/ashutosh00710/github-readme-activity-graph)

<br/>

[![Tokscale Stats](https://tokscale.ai/api/embed/Transient-Onlooker/svg?compact=1)](https://tokscale.ai/u/Transient-Onlooker)

<br/>

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Transient-Onlooker&layout=donut&theme=codeSTACKr)

</details>

---

## 💡 관심 분야

항공우주공학 · 수치 시뮬레이션 · 안드로이드 개발 · 시스템 설계 · 위성 통신 · AI 자동화

---

## 🔗 연결

[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:junuh145858@gmail.com)
[![Discord](https://img.shields.io/badge/Discord-5865F2?style=flat-square&logo=discord&logoColor=white)](https://discord.com/users/nomoregimal)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Transient-Onlooker)

질문이 있으신가요?  
[Issues](https://github.com/Transient-Onlooker/Transient-Onlooker/issues)를 통해 연락해주세요.

---

> **0.1%의 창의적 인간이 미래를 발명하고, 0.9%의 통찰력 있는 인간이 그것을 사업화하며, 99%의 잉여인간은 역사의 변화를 모른 채 따라갈 뿐이다. (제레미 리프킨)**
