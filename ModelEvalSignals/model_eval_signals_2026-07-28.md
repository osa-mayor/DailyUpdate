# Model & Eval Signals (2026-07-28)

## 오늘의 요약
Hugging Face의 대규모 파라미터 모델(Upstage, Poolside) 및 멀티모달 모델(MoonshotAI)의 등장과 함께, 소프트웨어 엔지니어링 에이전트 역량 측정을 위한 새로운 벤치마크(CodeClash, SWE-smith) 및 코드 생성 성능 평가(LiveCodeBench)가 주요 동향으로 나타났습니다.

### 오늘의 핵심 포인트
- Hugging Face 내 대규모 파라미터(250B) 및 멀티모달 모델(Kimi-K3)의 주목
- 목표 지향적 개발자 역량 평가를 위한 CodeClash 및 에이전트 학습 도구 SWE-smith 출시
- LiveCodeBench를 통한 Gemini 및 O4-Mini 등 주요 모델의 코드 생성 성능 확인

**오늘의 태그**: LLM, Multimodal, Software Engineering Agent, Benchmark, Hugging Face

## 1. [moonshotai/Kimi-K3](https://huggingface.co/moonshotai/Kimi-K3)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Moonshot AI에서 공개한 Kimi-K3 모델이 Hugging Face에서 주목받고 있습니다. 이 모델은 이미지와 텍스트를 동시에 처리하는 멀티모달 기능을 제공합니다.

### 핵심 포인트
- Moonshot AI의 Kimi-K3 모델이 높은 likes(5562)와 downloads(2850)를 기록하며 트렌딩 중입니다.
- pipeline_tag는 image-text-to-text로, 시각 정보와 텍스트를 결합한 작업에 특화되어 있습니다.
- 모델의 파라미터 규모는 약 2.78T로 확인됩니다.

**태그**: MoonshotAI, Kimi-K3, Multimodal

**Metrics**: {"likes": 5562, "downloads": 2850, "num_parameters": 2779931837184, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=5562, downloads=2850, pipeline_tag=image-text-to-text

---

## 2. [poolside/Laguna-S-2.1](https://huggingface.co/poolside/Laguna-S-2.1)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
poolside/Laguna-S-2.1 모델이 Hugging Face에서 높은 다운로드 수를 기록하며 주목받고 있습니다. 약 117B 파라미터를 보유한 text-generation 태그의 모델입니다.

### 핵심 포인트
- poolside/Laguna-S-2.1 모델의 높은 사용자 관심도 확인
- 약 117.5B 파라미터를 가진 대규모 text-generation 모델
- 63,605회의 다운로드와 741개의 likes 기록

**태그**: poolside/Laguna-S-2.1, text-generation, LLM

**Metrics**: {"likes": 741, "downloads": 63605, "num_parameters": 117561977600, "pipeline_tag": "text-generation"}

### 원문 설명
likes=741, downloads=63605, pipeline_tag=text-generation

---

## 3. [upstage/Solar-Open2-250B](https://huggingface.co/upstage/Solar-Open2-250B)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Upstage에서 공개한 250B 규모의 대형 언어 모델인 upstage/Solar-Open2-250B가 Hugging Face에서 주목받고 있습니다. 해당 모델은 text-generation 태그를 사용하는 대규모 파라미터 모델입니다.

### 핵심 포인트
- upstage/Solar-Open2-250B 모델의 Hugging Face 트렌딩 기록
- 약 250B 규모의 파라미터를 보유한 대형 모델
- 626개의 likes와 3,761회의 downloads를 기록하며 높은 관심을 받음

**태그**: upstage/Solar-Open2-250B, text-generation, LLM

**Metrics**: {"likes": 626, "downloads": 3761, "num_parameters": 250287810304, "pipeline_tag": "text-generation"}

### 원문 설명
likes=626, downloads=3761, pipeline_tag=text-generation

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

