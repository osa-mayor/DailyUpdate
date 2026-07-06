# Model & Eval Signals (2026-07-07)

## 오늘의 요약
Hugging Face의 대규모 언어 모델(LLM) 공개와 더불어, 소프트웨어 엔지니어링 에이전트의 역량을 측정하고 학습시키기 위한 새로운 벤치마크 및 도구들이 등장하며 에이전트 중심의 평가 체계가 고도화되고 있습니다.

### 오늘의 핵심 포인트
- Tencent, DeepSeek 등 주요 기업의 대규모 언어 모델(LLM) 및 표 형식 데이터 분류 모델 공개
- 목표 지향적 개발자 역량 측정을 위한 CodeClash 및 에이전트 학습 도구 SWE-smith 등 새로운 벤치마크/프레임워크 등장
- mini-SWE-agent의 높은 효율성 입증 및 LiveCodeBench를 통한 모델별 코딩 성능 순위 업데이트

**오늘의 태그**: LLM, Software Engineering Agent, Benchmark, Hugging Face

## 1. [tencent/Hy3](https://huggingface.co/tencent/Hy3)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Tencent에서 공개한 text-generation 태그의 Hy3 모델이 Hugging Face에서 주목받고 있습니다. 해당 모델은 약 298B 규모의 파라미터를 보유하고 있습니다.

### 핵심 포인트
- Tencent에서 공개한 text-generation 모델인 Hy3가 출시되었습니다.
- 모델의 파라미터 규모는 약 298,786,155,776개입니다.
- 현재 Hugging Face에서 295개의 likes를 기록하며 트렌딩 중입니다.

**태그**: Tencent, Hy3, text-generation

**Metrics**: {"likes": 295, "downloads": 2, "num_parameters": 298786155776, "pipeline_tag": "text-generation"}

### 원문 설명
likes=295, downloads=2, pipeline_tag=text-generation

---

## 2. [google/tabfm-1.0.0-pytorch](https://huggingface.co/google/tabfm-1.0.0-pytorch)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Google에서 공개한 tabular-classification 태그의 google/tabfm-1.0.0-pytorch 모델이 Hugging Face에서 주목받고 있습니다. 해당 모델은 표 형식 데이터 분류를 위한 파이프라인을 제공합니다.

### 핵심 포인트
- google/tabfm-1.0.0-pytorch 모델이 Hugging Face에서 트렌딩 중입니다.
- 해당 모델의 주요 작업은 tabular-classification입니다.
- 현재까지 7,036회의 다운로드와 253개의 likes를 기록하고 있습니다.

**태그**: google/tabfm-1.0.0-pytorch, tabular-classification, Hugging Face

**Metrics**: {"likes": 253, "downloads": 7036, "num_parameters": 0, "pipeline_tag": "tabular-classification"}

### 원문 설명
likes=253, downloads=7036, pipeline_tag=tabular-classification

---

## 3. [deepseek-ai/DeepSeek-V4-Pro-DSpark](https://huggingface.co/deepseek-ai/DeepSeek-V4-Pro-DSpark)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
DeepSeek-AI에서 공개한 DeepSeek-V4-Pro-DSpark 모델이 Hugging Face에서 주목받고 있습니다. 해당 모델은 text-generation 파이프라인을 지원하는 대규모 언어 모델입니다.

### 핵심 포인트
- DeepSeek-AI의 text-generation 모델인 DeepSeek-V4-Pro-DSpark가 공개되었습니다.
- 약 889B(889,484,881,098) 파라미터를 보유한 대규모 모델입니다.
- 14,276회의 downloads와 407개의 likes를 기록하며 트렌딩 중입니다.

**태그**: DeepSeek-V4-Pro-DSpark, text-generation, LLM

**Metrics**: {"likes": 407, "downloads": 14276, "num_parameters": 889484881098, "pipeline_tag": "text-generation"}

### 원문 설명
likes=407, downloads=14276, pipeline_tag=text-generation

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

