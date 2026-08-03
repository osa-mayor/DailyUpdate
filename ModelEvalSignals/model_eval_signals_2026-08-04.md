# Model & Eval Signals (2026-08-04)

## 오늘의 요약
Hugging Face의 신규 모델 트렌드와 소프트웨어 엔지니어링 에이전트 및 코딩 능력을 측정하는 새로운 벤치마크들의 업데이트가 주를 이루었습니다.

### 오늘의 핵심 포인트
- MiniMax-H3 및 DeepSeek-V4-Flash-GGUF 등 특정 기능과 포맷을 갖춘 모델들이 Hugging Face에서 높은 관심을 받음
- CodeClash, SWE-smith 등 소프트웨어 엔지니어링 에이전트의 목표 지향적 능력과 학습을 위한 새로운 벤치마크/도구 등장
- LiveCodeBench를 통해 O4-Mini 및 Gemini 시리즈 모델들의 코딩 성능이 상위권에서 경쟁 중

**오늘의 태그**: LLM_Trending, Software_Engineering_Agents, Coding_Benchmarks

## 1. [MiniMaxAI/MiniMax-H3](https://huggingface.co/MiniMaxAI/MiniMax-H3)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
MiniMaxAI에서 공개한 MiniMax-H3 모델이 Hugging Face에서 주목받고 있습니다. 이 모델은 image-text-to-video 파이프라인을 지원하는 것이 특징입니다.

### 핵심 포인트
- MiniMax-H3 모델은 1,327개의 likes를 기록하며 트렌딩 모델로 부상했습니다.
- 해당 모델의 주요 기능은 image-text-to-video 파이프라인입니다.
- 모델의 파라미터 규모는 약 33.1B입니다.

**태그**: MiniMax-H3, image-text-to-video, MiniMaxAI

**Metrics**: {"likes": 1327, "downloads": 0, "num_parameters": 33122992896, "pipeline_tag": "image-text-to-video"}

### 원문 설명
likes=1327, downloads=0, pipeline_tag=image-text-to-video

---

## 2. [Comfy-Org/MiniMax-H3](https://huggingface.co/Comfy-Org/MiniMax-H3)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Comfy-Org에서 공개한 MiniMax-H3 모델이 Hugging Face에서 주목받고 있습니다. 해당 모델은 418개의 likes를 기록하며 사용자들의 관심을 끌고 있습니다.

### 핵심 포인트
- Comfy-Org에서 배포한 MiniMax-H3 모델
- 418개의 likes를 기록하며 트렌딩 중
- 현재 다운로드 수는 2회로 초기 단계임

**태그**: MiniMax-H3, Comfy-Org, Model Trending

**Metrics**: {"likes": 418, "downloads": 2, "num_parameters": 0, "pipeline_tag": ""}

### 원문 설명
likes=418, downloads=2, pipeline_tag=

---

## 3. [unsloth/DeepSeek-V4-Flash-0731-GGUF](https://huggingface.co/unsloth/DeepSeek-V4-Flash-0731-GGUF)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
unsloth에서 공개한 DeepSeek-V4-Flash-0731-GGUF 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 해당 모델은 GGUF 포맷으로 제공되어 다양한 환경에서의 활용이 가능합니다.

### 핵심 포인트
- unsloth에서 배포한 DeepSeek-V4-Flash-0731-GGUF 모델의 트렌딩 현황
- 69,656회의 높은 downloads를 기록하며 사용자들의 관심을 받음
- 약 19.8B 규모의 파라미터를 가진 모델

**태그**: DeepSeek-V4-Flash-0731-GGUF, unsloth, GGUF

**Metrics**: {"likes": 420, "downloads": 69656, "num_parameters": 19845850983, "pipeline_tag": ""}

### 원문 설명
likes=420, downloads=69656, pipeline_tag=

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

