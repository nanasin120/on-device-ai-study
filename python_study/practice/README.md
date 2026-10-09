# 🐍 Python Practice (연습문제 & 최종 종합 평가)

파이썬 핵심 문법 및 실무 활용 능력을 단계별로 체화할 수 있는 연습문제와 최종 평가 공간입니다.  
각 문제의 **[Open In Colab]** 배지를 클릭하면 브라우저에서 별도 환경 설정 없이 바로 코드를 실행하고 실습할 수 있습니다.

---

## 💡 난이도 및 학습 단계 구분

문제를 성격과 난이도에 따라 **Step 1(빈칸 채우기)**, **Step 2(직접 구현)**, **Final Exam(종합 평가)** 3가지로 구분하여 체계적인 학습이 가능합니다.

| 구분 | 단계 | 유형 | 학습 목표 |
| :---: | :---: | :---: | :--- |
| 🟢 | **Step 1** | 빈칸 채우기 (`______`) | 문법의 형태와 실행 흐름을 파악하고 핵심 키워드/연산자 숙지 |
| 🟡 | **Step 2** | TODO 직접 구현 | 문제 명세와 주석 가이드를 바탕으로 전체 로직을 스스로 작성 |
| 🔴 | **Final** | 종합 프로젝트 평가 | Day 1~4 과정을 아우르는 실제 데이터 처리 파이프라인 구현 |

---

## 📋 전체 연습문제 & 종합 평가 목록

| 구분 | 단계 | 핵심 주제 | 세부 내용 | 파일 | Colab 링크 |
| :---: | :---: | :--- | :--- | :--- | :---: |
| **Day 1** | 🟢 Step 1 | 기초 문법 & 데이터 전처리 | 문자열 분리, 형변환, 비트 마스크, 조건문 판정 | [`Day1_practice_step1.ipynb`](Day1/Day1_practice_step1.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nanasin120/on-device-ai-study/blob/main/python_study/practice/Day1/Day1_practice_step1.ipynb) |
| **Day 1** | 🟡 Step 2 | 기초 문법 & 데이터 전처리 | 문자열 분리, 형변환, 비트 마스크, 조건문 직접 구현 | [`Day1_practice_step2.ipynb`](Day1/Day1_practice_step2.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nanasin120/on-device-ai-study/blob/main/python_study/practice/Day1/Day1_practice_step2.ipynb) |
| **Day 2** | 🟢 Step 1 | 자료구조 심화 & 함수 활용 | 튜플 언패킹, 집합(Set), 딕셔너리, 다중 반환, 컴프리헨션 | [`Day2_practice_step1.ipynb`](Day2/Day2_practice_step1.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nanasin120/on-device-ai-study/blob/main/python_study/practice/Day2/Day2_practice_step1.ipynb) |
| **Day 2** | 🟡 Step 2 | 자료구조 심화 & 함수 활용 | 튜플 언패킹, 통계 계산 함수, 조건부 필터링 직접 구현 | [`Day2_practice_step2.ipynb`](Day2/Day2_practice_step2.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nanasin120/on-device-ai-study/blob/main/python_study/practice/Day2/Day2_practice_step2.ipynb) |
| **Day 3** | 🟢 Step 1 | 파일 I/O & 객체지향(OOP) | 파일 읽기, 클래스 기본(`__init__`), 문자열 표현(`__repr__`), 상속 | [`Day3_practice_step1.ipynb`](Day3/Day3_practice_step1.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nanasin120/on-device-ai-study/blob/main/python_study/practice/Day3/Day3_practice_step1.ipynb) |
| **Day 3** | 🟡 Step 2 | 파일 I/O & 객체지향(OOP) | 파일 파싱, Sensor/AlertSensor 클래스 및 상속 직접 구현 | [`Day3_practice_step2.ipynb`](Day3/Day3_practice_step2.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nanasin120/on-device-ai-study/blob/main/python_study/practice/Day3/Day3_practice_step2.ipynb) |
| **Day 4** | 🟢 Step 1 | 데이터 분석 (NumPy & Pandas) | NumPy 배열/벡터 연산, 불리언 마스킹, 결측치(`fillna`), `groupby` 집계 | [`Day4_practice_step1.ipynb`](Day4/Day4_practice_step1.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nanasin120/on-device-ai-study/blob/main/python_study/practice/Day4/Day4_practice_step1.ipynb) |
| **Day 4** | 🟡 Step 2 | 데이터 분석 (NumPy & Pandas) | NumPy 연산식 및 Pandas 전처리/그룹 집계 로직 직접 구현 | [`Day4_practice_step2.ipynb`](Day4/Day4_practice_step2.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nanasin120/on-device-ai-study/blob/main/python_study/practice/Day4/Day4_practice_step2.ipynb) |
| **Final** | 🔴 평가 | 스마트 팩토리 센서 데이터 분석기 | 로그 파싱, 클래스 모델링, 예외 방어 I/O, 센서별 통계 산출 | [`Final_exam.ipynb`](Final_exam.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nanasin120/on-device-ai-study/blob/main/python_study/practice/Final_exam.ipynb) |

---

## 📂 Day별 세부 학습 내용

<details open>
<summary><b>📅 Day 1 — 기초 문법 & 데이터 전처리</b></summary>

- **주요 내용**: 문자열 조작, 타입 캐스팅, 비트 마스크, 분기문
  - 1단계: 문자열 공백 제거(`strip`) 및 구분자 분리(`split`)
  - 2단계: 문자열 형변환(`int`, `float`)과 f-string 소수점 포맷팅
  - 3단계: 비트 마스크 연산(`&`)을 통한 센서 상태 플래그 확인
  - 4단계: 다중 조건문(`if-elif-else`)을 이용한 센서 상태 분류
- **실습 링크**:
  - [🟢 Day 1 Step 1 (빈칸 채우기)](Day1/Day1_practice_step1.ipynb) &nbsp;|&nbsp; [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nanasin120/on-device-ai-study/blob/main/python_study/practice/Day1/Day1_practice_step1.ipynb)
  - [🟡 Day 1 Step 2 (TODO 구현)](Day1/Day1_practice_step2.ipynb) &nbsp;|&nbsp; [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nanasin120/on-device-ai-study/blob/main/python_study/practice/Day1/Day1_practice_step2.ipynb)
</details>

<br>

<details open>
<summary><b>📅 Day 2 — 자료구조 심화 & 함수 활용</b></summary>

- **주요 내용**: 컬렉션 자료형(Tuple, Set, Dict), 패킹/언패킹, 다중 반환 함수, 리스트 컴프리헨션
  - 1단계: 튜플 언패킹과 슬라이싱(`[:]`)
  - 2단계: `set`을 활용한 고유 센서 ID 추출 및 딕셔너리 구조화
  - 3단계: 최소값, 최대값, 평균을 계산하여 다중 반환하는 함수 작성
  - 4단계: 조건식을 포함한 리스트 컴프리헨션 데이터 필터링
- **실습 링크**:
  - [🟢 Day 2 Step 1 (빈칸 채우기)](Day2/Day2_practice_step1.ipynb) &nbsp;|&nbsp; [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nanasin120/on-device-ai-study/blob/main/python_study/practice/Day2/Day2_practice_step1.ipynb)
  - [🟡 Day 2 Step 2 (TODO 구현)](Day2/Day2_practice_step2.ipynb) &nbsp;|&nbsp; [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nanasin120/on-device-ai-study/blob/main/python_study/practice/Day2/Day2_practice_step2.ipynb)
</details>

<br>

<details open>
<summary><b>📅 Day 3 — 파일 I/O & 객체지향 프로그래밍 (OOP)</b></summary>

- **주요 내용**: 파일 읽기/쓰기, 클래스 생성, 매직 메소드, 클래스 상속
  - 1단계: `with open(...)` 기반 텍스트 파일 읽기 및 빈 줄 건너뛰기
  - 2단계: `Sensor` 기본 클래스 정의 (`__init__`, 인스턴스 변수 바인딩)
  - 3단계: `__repr__` 문자열 표현 및 딕셔너리 변환 메서드(`to_dict`)
  - 4단계: `AlertSensor` 클래스 상속(`super().__init__`) 및 이상치 경고 로직 구현
- **실습 링크**:
  - [🟢 Day 3 Step 1 (빈칸 채우기)](Day3/Day3_practice_step1.ipynb) &nbsp;|&nbsp; [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nanasin120/on-device-ai-study/blob/main/python_study/practice/Day3/Day3_practice_step1.ipynb)
  - [🟡 Day 3 Step 2 (TODO 구현)](Day3/Day3_practice_step2.ipynb) &nbsp;|&nbsp; [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nanasin120/on-device-ai-study/blob/main/python_study/practice/Day3/Day3_practice_step2.ipynb)
</details>

<br>

<details open>
<summary><b>📅 Day 4 — 데이터 분석 기초 (NumPy & Pandas)</b></summary>

- **주요 내용**: 수치 연산 라이브러리(NumPy), 데이터 분석 프레임워크(Pandas)
  - 1단계: NumPy ndarray 생성 및 반복문 없는 벡터화 연산
  - 2단계: 조건부 불리언 마스킹(Boolean Masking)을 통한 데이터 추출
  - 3단계: Pandas DataFrame 생성 및 결측치(`NaN`) 대체(`fillna`)
  - 4단계: `groupby()`를 이용한 센서별 그룹화 및 집계 연산(평균값 계산)
- **실습 링크**:
  - [🟢 Day 4 Step 1 (빈칸 채우기)](Day4/Day4_practice_step1.ipynb) &nbsp;|&nbsp; [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nanasin120/on-device-ai-study/blob/main/python_study/practice/Day4/Day4_practice_step1.ipynb)
  - [🟡 Day 4 Step 2 (TODO 구현)](Day4/Day4_practice_step2.ipynb) &nbsp;|&nbsp; [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nanasin120/on-device-ai-study/blob/main/python_study/practice/Day4/Day4_practice_step2.ipynb)
</details>

<br>

<details open>
<summary><b>🏆 Final Exam — 최종 종합 실기 평가</b></summary>

- **프로젝트명**: IoT 스마트 팩토리 센서 데이터 분석기
- **평가 내용**: Day 1 ~ Day 4에서 배운 모든 파이썬 핵심 기술을 융합하여 센서 로그 파일 파싱부터 분석까지 완성
  - 1단계: 센서 데이터 한 줄 파싱 (타입 변환 및 비트 연산)
  - 2단계: `SensorRecord` 클래스 및 이상 감지 메서드 구현
  - 3단계: 파일 읽기 및 결측치/이상 데이터 예외 처리(`try-except`) 방어
  - 4단계: 센서별 정상 데이터 통계 집계 및 리포트 출력
- **실습 링크**:
  - [🔴 Final Exam (최종 종합 평가)](Final_exam.ipynb) &nbsp;|&nbsp; [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nanasin120/on-device-ai-study/blob/main/python_study/practice/Final_exam.ipynb)
</details>

---

## 💡 Colab 실습 시 팁

1. **사본 저장 후 실행 권장**:
   - 상단 메뉴의 **[파일] → [Drive에 사본 저장]**을 누르면 본인 구글 드라이브에 저장되어 코드 수정 내역이 영구 보존됩니다.
2. **단축키 안내**:
   - `Shift + Enter`: 현재 셀 실행 후 다음 셀로 이동
   - `Ctrl + Enter`: 현재 셀 실행
   - `Ctrl + M B`: 아래에 새 코드 셀 추가
