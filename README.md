# 🌫️ Streamlit 공공데이터 웹앱

공공데이터를 활용하여 **서울시 자치구별 미세먼지 현황을 시각화**하는 Streamlit 기반 웹 애플리케이션입니다.

공공데이터를 수집하고 전처리한 뒤, 다양한 시각화와 지도를 통해 서울시 미세먼지 현황을 한눈에 확인할 수 있도록 구현했습니다. 또한 `st.cache_data`를 적용하여 데이터 로딩 속도를 개선하고 앱의 성능을 향상시켰습니다.

---

## 📌 프로젝트 소개

* **프로젝트명** : Streamlit 공공데이터 웹앱
* **개발 인원** : 1명

---

## 🚀 주요 기능

* 공공데이터 불러오기
* 데이터 전처리
* 서울시 자치구별 미세먼지 데이터 분석
* 지도(Folium) 시각화
* Plotly 그래프 시각화
* Cache를 이용한 데이터 로딩 속도 향상

---

## 🛠️ 사용 기술

### Language

* Python

### Library

* Streamlit
* Pandas
* Plotly
* Folium
* streamlit-folium

---

## 📂 프로젝트 구조

```text
public_app/
│── public_app.py
│── seoul_gu.geojson
│── requirements.txt
│── .gitignore
└── ...
```

---

## 📊 구현 내용

### 1. 공공데이터 수집

공공데이터포털에서 제공하는 서울시 미세먼지 데이터를 활용하였습니다.

---

### 2. 데이터 전처리

* 필요한 컬럼 선택
* 결측치 처리
* 자치구별 데이터 정리
* 시각화를 위한 데이터 가공

---

### 3. 데이터 시각화

* Plotly를 이용한 그래프
* Folium을 이용한 서울시 지도 시각화
* 자치구별 미세먼지 현황 확인

---

### 4. Cache 적용

`st.cache_data`를 활용하여 데이터를 한 번만 불러오도록 구현하였습니다.

**적용 효과**

* 데이터 재사용
* 앱 실행 속도 향상
* 불필요한 데이터 로딩 감소

---

## 💻 실행 방법

### 1. 프로젝트 다운로드

```bash
git clone https://github.com/khrkhr316/streamlit_webapp.git

cd streamlit_webapp
```

### 2. 패키지 설치

```bash
pip install -r requirements.txt
```

### 3. 실행

```bash
streamlit run public_app.py
```

---

## 📷 실행 화면

> 실행 화면 이미지를 추가하면 프로젝트 이해도가 더욱 높아집니다.

* 메인 화면
* 서울시 지도
* 미세먼지 그래프

---

## 📚 학습 내용

* 공공데이터 활용 방법
* 데이터 전처리
* Streamlit 웹앱 개발
* Plotly 시각화
* Folium 지도 시각화
* Cache를 활용한 성능 최적화

---

## 🔗 GitHub Repository

https://github.com/khrkhr316/streamlit_webapp
