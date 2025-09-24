# 푸른싹수: 로컬 소상공인을 위한 생성형 AI 마케팅 자동화 플랫폼

<p align="center">
  <img src="images/로컬Grow_logo.png" alt="LocalGrow Banner" width="150"/>
</p>

**푸른싹수(LocalGrow)** 는 지역 소상공인의 디지털 마케팅 역량 부족 문제를 해결하기 위해  
**생성형 AI**, **LLM**, **RAG**, **LangChain** 등의 기술을 활용하여  
상품 브랜딩 스토리, 홍보 이미지, 채널별 마케팅 콘텐츠를 자동으로 생성해주는 **로컬 농수산물 Grow 플랫폼**입니다.

## 주요 목표
  - 지역 소상공인의 매출 증대
  - 지역 경제 활성화
  - 디지털 마케팅 격차 해소

## 기술 스택

- **주요 기술:** OpenAI API (GPT-4o, DALL·E 3, Whisper API), Tavily API(RAG), LangChain, Pillow, Runway Gen-4 API, Streamlit

| 구분       | 사용 기술 |
|-----------|-----------|
| 언어       | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) |
| 주요 기술   | ![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white) ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat) ![Tavily](https://img.shields.io/badge/Tavily_API-FF6F00?style=flat) ![Pillow](https://img.shields.io/badge/Pillow-92C1F0?style=flat) ![Runway](https://img.shields.io/badge/Runway_Gen--4-FF007F?style=flat) |
| 프레임워크/플랫폼 | ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white) |

## 시스템 아키텍처

![아키텍처](images/로컬Grow_아키텍처.png)

## 서비스 구성

1. **브랜딩 스토리 생성**
   - Whisper API로 음성 → 텍스트 변환(STT)
   - GPT-4o, LangChain, RAG를 통해 지역 특색 스토리 생성

2. **상품 이미지 생성**
   - DALL·E 3, Pillow, LangChain 기반으로 상품 홍보 이미지 자동 생성

3. **마케팅 콘텐츠 생성**
   - 생성된 스토리·이미지를 기반으로 Runway Gen-4 API로 인스타그램, 유튜브, 블로그 채널별 최적화 콘텐츠 생성

4. **웹 서비스**
   - Streamlit으로 웹 데모 제공 (체험 프로그램 & 베타 서비스)

## ✨ 주요 기능

### 1. 상품 정보 업로드
판매자가 상품 정보, 지역 정보, 생산자 스토리를 텍스트/음성으로 업로드합니다.

<p align="center">
  <img src="images/사용자입력1.png" width="200"/>
  <img src="images/사용자입력2.png" width="200"/>
  <img src="images/사용자입력3.png" width="200"/>
</p>

| 입력 화면 1 | 입력 화면 2 | 입력 화면 3 |
|-------------|-------------|-------------|
| <img src="images/사용자입력1.png" width="200"/> | <img src="images/사용자입력2.png" width="200"/> | <img src="images/사용자입력3.png" width="200"/> |

---

### 2. 브랜드 스토리 생성
RAG + LLM을 활용하여 브랜드 소개문, 슬로건, 핵심 키워드, 스토리를 자동 생성합니다.

<img src="images/브랜드_스토리_생성.png" width="600"/>

---

### 3. 상품 홍보 이미지 생성
DALL·E 3 + Pillow를 통해 상품 우수성과 지역 특성을 반영한 이미지 생성

<img src="images/상품_홍보_이미지_생성.png" width="600"/>

---

### 4. 채널별 맞춤 마케팅 콘텐츠 제공
인스타그램, 유튜브, 블로그 등 채널에 최적화된 콘텐츠를 자동으로 생성합니다.

| 블로그 | 유튜브 | 인스타그램 |
|--------|--------|------------|
| <img src="images/플랫폼_맞춤_마케팅_콘텐츠(블로그).png" width="200"/> | <img src="images/플랫폼_맞춤_마케팅_콘텐츠(유튜브).png" width="200"/> | <img src="images/플랫폼_맞춤_마케팅_콘텐츠(인스타).png" width="200"/> |



