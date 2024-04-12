#### 송천고의 아이도루 송천-짱을 만들기 위한 여정


## 주요 기능

대화 

입력 : 채팅, 음성

출력 : 텍스트, TTS, Live2D(가능하다면)


### INPUT
채팅 //// 음성

### LLM

model : c4ai-command-r-v01

### STT

model : wisper

### TTS

model : xttsv2

### Live 2D

model : --

### OUTPUT

Text //// Video

### 1차시
LLM 모델 설치 및 실행 테스트

llama.cpp를 이용해 cpu 및 gpu 에서 LLM 구동

### 2차시 
LLM모델 rag 구축, tool 사용 구축 및 검증

벡터 DB 사용, command-r 모델의 기능 중 하나인 tool 사용 기능 이용

### 3차시
TTS 입력 구현

whisper.cpp 프로젝트를 이용해 cpu에서 openai whisper 모델 추론 후 LLM 입력으로 연결

### 4차시
STT 출력 구현

coqui-ai xtts v2 프로젝트를 이용해 LLM 출력을 음성으로도 할 수 있도록 제작

### 5차시
프론트엔드 완성 및 LLM과 결합 테스트

rag, TTS, STT 등을 모두 LLM과 결합하고 프론트엔드를 제작. 설정 및 사용의 용이성을 고려.
