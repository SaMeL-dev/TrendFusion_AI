<p align="right">
🇰🇷 [한국어 버전](./README.md) | 🇺🇸 [English Version](./README_EN.md)
</p>

# TrendFusion AI

**TrendFusion AI**는 실시간 웹 크롤링과 생성형 AI를 결합하여  
빠르게 변화하는 온라인 트렌드와 커뮤니티의 흐름을 한눈에 파악할 수 있도록 도와주는 프로젝트입니다.

---

## 🔍 프로젝트 배경

지금도 뉴스, 커뮤니티, 소셜 미디어 등 다양한 채널에서 매일 수많은 정보가 쏟아지는 있습니다.  
그 흐름을 따라가기 위해 하나하나 검색하고 비교하는 작업은 많은 시간과 노력을 소모하게 만듭니다.  

**TrendFusion AI는 “정보 소비의 피로감”을 줄이기 위해 탄생했습니다.**  
사용자가 요청한 특정 주제에 대해 웹 크롤링으로 최신 콘텐츠를 수집합니다.
수집한 콘텐츠들은 생성형 AI가 매끄럽게 번역 및 요약해줌으로서 사용자는 특정 주제의 최신 반응을 한 번에 비교할 수 있게 됩니다.

---

## 🎯 주요 기능

- 다양한 웹사이트에서 실시간 크롤링
- GPT 기반 트렌드 요약 및 번역
- 향후 감성 분석 및 이슈 흐름 시각화 기능 추가 예정
- 추가로 GPT의 RAG를 이용한 신뢰 기반 정보를 이용한 **병렬 응답 구조** 또한 기획 중

---

## 🛠 사용 기술

- Python
- Playwright / BeautifulSoup (웹 크롤링)
- GPT API (텍스트 요약)
- (예정) FAISS or Chroma (벡터 DB)
- (예정) Streamlit or Flask (웹 인터페이스)

---

## 🧪 개발 상태

- [x] GitHub 연동 및 기본 구조 세팅
- [x] `.gitignore`, LICENSE, README 구성
- [ ] 크롤러 개발 시작
- [ ] 요약기 연동
- [ ] 사용자 인터페이스 구현

---

## 📄 라이선스

이 프로젝트는 **GNU General Public License v3.0**(GPL-3.0)에 따라 배포됩니다.  
프로젝트를 자유롭게 사용할 수 있지만, 수정하거나 재배포할 경우에도 동일한 라이선스 조건을 유지해야 합니다.