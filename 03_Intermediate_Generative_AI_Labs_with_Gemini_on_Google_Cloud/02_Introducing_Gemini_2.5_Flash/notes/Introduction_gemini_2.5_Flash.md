## Lab_02. Gemini 2.5 Flash 소개
> [Gemini 2.5 Flash 모델](https://deepmind.google/models/gemini/flash/)을 활용해 복잡한 문제를 다단계 전략과 반복적 해결 방식으로 처리하는 실습 과정.
> 
> 명시적으로 사고 과정을 보여주는 하이브리드 추론 모델인 Gemini 2.5 Flash의 역량을 확인하고, 다양한 데이터 유형을 다루는 방법을 학습.

### 주요 내용
* [Gemini](https://deepmind.google/models/gemini/): 텍스트, 코드, 이미지, 오디오, 비디오 등 다양한 형태의 콘텐츠를 이해하고 생성하는 Google DeepMind의 생성형 AI 모델.
* [Vertex AI의 Gemini API](https://cloud.google.com/vertex-ai/generative-ai/docs/learn/models?hl=ko#gemini-models): Gemini 모델을 애플리케이션에 통합하는 통일된 인터페이스 제공. 최신 정보는 공식 Gemini 문서를 통해 확인 가능.
Gemini 모델 종류:
* [Gemini Pro](https://deepmind.google/technologies/gemini/pro/): 
  * 복잡한 추론에 최적화된 모델 
  * 대량 정보 분석/요약, 정교한 크로스 모달 추론
  * 복잡한 코드베이스를 사용한 효과적인 문제 해결
* [Gemini Flash](https://deepmind.google/models/gemini/flash/): 
  * 속도와 효율성에 최적화된 모델 
  * 초고속 응답, 저비용, 향상된 Multimodal 기능, Google 검색 같은 도구 사용

### 사전 준비 및 요구 사항
* 사전 지식:
  * 기본적인 Python 프로그래밍.
  * 일반적인 API 개념.
  * [Vertex AI Workbench](https://cloud.google.com/vertex-ai/docs/workbench/introduction?hl=ko) Jupyter 노트북 환경에서의 Python 코드 실행 경험.
실습 환경: 
    * `Google Cloud 콘솔`에서 제공하는 임시 계정 사용. 
    * 개인 계정 사용 시 추가 비용 발생 가능성에 유의.

### 학습 목표
* `Gemini 2.5 Flash 모델`을 활용하여 복잡한 문제 해결.
* 사고 예산 구성, 다중 턴 채팅, 토큰 수 계산, 모델 매개변수 구성 등 `Gemini 2.5 Flash`의 다양한 기능 사용.
* `Multimodal` (오디오, 코드, 문서, 이미지, 비디오) 데이터 처리.
* `Gemini 2.5 Flash`의 `사고 모드(thinking mode)` 활용 사례 이해.

### 실습 세부 내용
* 1.` Vertex AI Workbench`에서 노트북 열기 및 설정
  * `Vertex AI 메뉴에서 Workbench` 인스턴스를 열어 `JupyterLab `인터페이스 접근.
  * 제공된 노트북 파일을 열고 `Python 3 커널` 선택.
  * 노트북의 `Getting Started` 및 `Import libraries 섹션` 실행.

* 2. `Gemini 2.5 Flash` 모델 사용
  * `사고 예산(thinking budget)` 구성: 특정 작업에 필요한 추론 토큰 수 동적 설정.
  * `다중 턴 채팅(multi-turn chat)` 시작: 여러 번의 상호 작용을 통해 자유로운 대화 진행.
  * `Google Cloud Storage`의 문서 전송: 특정 PDF 문서를 읽고 문서 이해 수행.

* 3. `Gemini 2.5 Flash`의 추론 탐구
  * `코드 생성`: 단일 프롬프트로 실행 가능한 비디오 게임을 만드는 Gemini 2.5 Flash의 추론 능력 확인.
  * `Multimodal` 추론(기하학): 텍스트와 이미지를 넘나드는 추론 능력 활용.
  * `수학 및 문제 해결`: 복잡한 수수께끼를 해결하고 각 결정에 대한 추론 과정 확인.
