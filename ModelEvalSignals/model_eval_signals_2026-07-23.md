# Model & Eval Signals (2026-07-23)

## 오늘의 요약
Hugging Face의 신규 모델 트렌드와 소프트웨어 엔지니어링 에이전트 및 코딩 성능을 측정하는 다양한 벤치마크 업데이트가 주요 흐름을 형성했습니다.

### 오늘의 핵심 포인트
- Hugging Face에서 117B 규모의 Laguna-S-2.1 및 krea2-identity-edit 등 다양한 목적의 모델들이 트렌드에 진입함
- SWE-bench 팀이 목표 지향적 개발자 역량 측정을 위한 CodeClash를 소개하고, mini-SWE-agent의 성과 및 SWE-smith 출시가 이어짐
- LiveCodeBench에서 O4-Mini 및 Gemini 시리즈 모델들이 상위권 성적을 기록하며 코딩 성능 경쟁이 지속됨

**오늘의 태그**: LLM, HuggingFace, SWE-bench, LiveCodeBench, AI_Agents

## 1. [poolside/Laguna-S-2.1](https://huggingface.co/poolside/Laguna-S-2.1)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
poolside에서 공개한 text-generation 태그의 모델인 Laguna-S-2.1이 Hugging Face에서 주목받고 있습니다. 약 117B 파라미터를 보유한 대규모 모델로, 최근 다운로드 수가 증가하며 트렌드에 진입했습니다.

### 핵심 포인트
- poolside에서 공개한 Laguna-S-2.1 모델의 등장
- 약 117.5B 규모의 파라미터를 가진 text-generation 모델
- 3,000회 이상의 다운로드와 369개의 likes를 기록하며 트렌드 형성

**태그**: Laguna-S-2.1, text-generation, Hugging Face

**Metrics**: {"likes": 369, "downloads": 3056, "num_parameters": 117561977600, "pipeline_tag": "text-generation"}

### 원문 설명
likes=369, downloads=3056, pipeline_tag=text-generation

---

## 2. [conradlocke/krea2-identity-edit](https://huggingface.co/conradlocke/krea2-identity-edit)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
conradlocke/krea2-identity-edit 모델이 Hugging Face에서 주목받고 있습니다. 해당 모델은 490개의 likes를 기록하며 사용자들의 관심을 끌고 있습니다.

### 핵심 포인트
- conradlocke/krea2-identity-edit 모델의 Hugging Face 트렌딩 발생
- 490개의 likes를 기록하며 사용자 관심을 확보
- 현재 downloads 및 파라미터 정보는 제공되지 않음

**태그**: conradlocke/krea2-identity-edit, Model Trending, Hugging Face

**Metrics**: {"likes": 490, "downloads": 0, "num_parameters": 0, "pipeline_tag": ""}

### 원문 설명
likes=490, downloads=0, pipeline_tag=

---

## 3. [Nanbeige/Nanbeige4.2-3B](https://huggingface.co/Nanbeige/Nanbeige4.2-3B)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Nanbeige/Nanbeige4.2-3B 모델이 Hugging Face에서 텍스트 생성(text-generation) 태그로 주목받고 있습니다. 해당 모델은 약 4.17B 파라미터를 보유하고 있습니다.

### 핵심 포인트
- Nanbeige/Nanbeige4.2-3B 모델의 Hugging Face 트렌드 발생
- 약 4.17B 규모의 파라미터를 가진 text-generation 모델
- 212개의 likes를 기록하며 사용자 관심을 유도 중

**태그**: Nanbeige, text-generation, LLM

**Metrics**: {"likes": 212, "downloads": 0, "num_parameters": 4169800704, "pipeline_tag": "text-generation"}

### 원문 설명
likes=212, downloads=0, pipeline_tag=text-generation

---

## 4. [Introducing CodeClash, our new eval of LMs as goal (not task) oriented developers! [ Link ]](https://codeclash.ai)
**Source**: SWE-bench | **Signal Type**: benchmark_update | **Category**: Benchmark News

### 요약
SWE-bench 팀이 언어 모델을 단순 작업 수행자가 아닌 목표 지향적 개발자로 평가하기 위한 새로운 벤치마크인 CodeClash를 소개합니다. 이 평가는 모델이 주어진 과제를 넘어 최종 목표를 달성하는 능력을 측정하는 데 중점을 둡니다.

### 핵심 포인트
- 새로운 벤치마크인 CodeClash 도입
- 단순 task 수행이 아닌 goal-oriented 개발자로서의 능력을 평가
- LLM의 소프트웨어 엔지니어링 역량 측정 방식의 변화 시도

**태그**: SWE-bench, CodeClash, LLM_Evaluation

### 원문 설명
Introducing CodeClash, our new eval of LMs as goal (not task) oriented developers! [ Link ]

---

## 5. [mini-SWE-agent scores 65% on SWE-bench Verified in 100 lines of python code. [ Link ]](https://github.com/SWE-agent/mini-swe-agent)
**Source**: SWE-bench | **Signal Type**: benchmark_update | **Category**: Benchmark News

### 요약
mini-SWE-agent가 SWE-bench Verified 벤치마크에서 65%의 점수를 기록했습니다. 이 성과는 단 100라인의 Python 코드로 달성되었습니다.

### 핵심 포인트
- mini-SWE-agent가 SWE-bench Verified에서 65% 점수 달성
- 단 100라인의 Python 코드로 구현된 효율성
- SWE-bench Verified 벤치마크 성능 입증

**태그**: mini-SWE-agent, SWE-bench, Software Engineering Agent

### 원문 설명
mini-SWE-agent scores 65% on SWE-bench Verified in 100 lines of python code. [ Link ]

---

## 6. [SWE-smith is out! Train your own models for software engineering agents. [ Link ]](https://swesmith.com)
**Source**: SWE-bench | **Signal Type**: benchmark_update | **Category**: Benchmark News

### 요약
소프트웨어 엔지니어링 에이전트 학습을 위한 SWE-smith가 출시되었습니다. 사용자가 직접 모델을 학습시킬 수 있는 환경을 제공합니다.

### 핵심 포인트
- SWE-smith 프레임워크 출시
- 소프트웨어 엔지니어링 에이전트 특화 모델 학습 지원
- 사용자 맞춤형 모델 학습 가능

**태그**: SWE-smith, Software Engineering, AI Agents

### 원문 설명
SWE-smith is out! Train your own models for software engineering agents. [ Link ]

---

## 7. [LiveCodeBench top model: O4-Mini (High)](https://livecodebench.github.io/leaderboard.html)
**Source**: LiveCodeBench | **Signal Type**: benchmark_snapshot | **Category**: Benchmark Leaderboard

### 요약
LiveCodeBench 벤치마크에서 O4-Mini (High) 모델이 상위 성적을 기록했습니다. 해당 모델은 4개의 문제를 대상으로 테스트를 진행했습니다.

### 핵심 포인트
- LiveCodeBench 벤치마크 결과 O4-Mini (High) 모델이 상위권을 기록함
- 테스트에 사용된 문제 수는 총 4개임
- avg_pass@1 지표는 25.0을 기록함

**태그**: LiveCodeBench, O4-Mini (High), benchmark_snapshot

**Metrics**: {"avg_pass_at_1": 25.0, "problem_count": 4, "model": "O4-Mini (High)"}

### 원문 설명
avg_pass@1=25.0, problems=4

---

## 8. [LiveCodeBench top model: Gemini-2.5-Pro-06-05](https://livecodebench.github.io/leaderboard.html)
**Source**: LiveCodeBench | **Signal Type**: benchmark_snapshot | **Category**: Benchmark Leaderboard

### 요약
LiveCodeBench 벤치마크에서 Gemini-2.5-Pro-06-05 모델이 상위 성적을 기록했습니다. 해당 모델은 4개의 문제를 대상으로 테스트를 진행했습니다.

### 핵심 포인트
- Gemini-2.5-Pro-06-05 모델이 LiveCodeBench에서 top model로 기록됨
- 테스트 결과 avg_pass@1 지표에서 25.0을 달성함
- 총 4개의 문제를 대상으로 벤치마크가 수행됨

**태그**: LiveCodeBench, Gemini-2.5-Pro-06-05, benchmark_snapshot

**Metrics**: {"avg_pass_at_1": 25.0, "problem_count": 4, "model": "Gemini-2.5-Pro-06-05"}

### 원문 설명
avg_pass@1=25.0, problems=4

---

## 9. [LiveCodeBench top model: Gemini-2.5-Flash-04-17](https://livecodebench.github.io/leaderboard.html)
**Source**: LiveCodeBench | **Signal Type**: benchmark_snapshot | **Category**: Benchmark Leaderboard

### 요약
LiveCodeBench 벤치마크에서 Gemini-2.5-Flash-04-17 모델이 상위 성적을 기록했습니다. 해당 모델은 4개의 문제를 대상으로 avg_pass@1 25.0%를 달성했습니다.

### 핵심 포인트
- LiveCodeBench 벤치마크 결과 Gemini-2.5-Flash-04-17 모델이 상위권을 기록함
- 4개의 문제를 대상으로 테스트가 진행됨
- avg_pass@1 지표에서 25.0%의 성능을 보임

**태그**: LiveCodeBench, Gemini-2.5-Flash-04-17, benchmark_snapshot

**Metrics**: {"avg_pass_at_1": 25.0, "problem_count": 4, "model": "Gemini-2.5-Flash-04-17"}

### 원문 설명
avg_pass@1=25.0, problems=4

---

