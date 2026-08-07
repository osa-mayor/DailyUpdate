# Model & Eval Signals (2026-08-08)

## 오늘의 요약
Hugging Face의 신규 비디오 생성 및 텍스트 생성 모델 출시와 더불어, 소프트웨어 엔지니어링 에이전트 역량 측정을 위한 새로운 벤치마크 및 성과가 주목받았습니다.

### 오늘의 핵심 포인트
- MiniMax 및 LiquidAI의 신규 모델 출시로 인한 비디오 생성 및 텍스트 생성 분야의 기술적 진보
- SWE-bench의 새로운 평가 방식(CodeClash) 및 에이전트 학습 도구(SWE-smith) 도입을 통한 소프트웨어 엔지니어링 평가 체계 고도화
- LiveCodeBench를 통한 최신 모델(O4-Mini, Gemini 시리즈)의 코딩 성능 지표 확인

**오늘의 태그**: LLM, Video-Generation, Software-Engineering-Agent, Benchmark

## 1. [larryvrh/MiniMax-H3-Turbo-Lora](https://huggingface.co/larryvrh/MiniMax-H3-Turbo-Lora)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
larryvrh/MiniMax-H3-Turbo-Lora 모델이 Hugging Face에서 주목받고 있습니다. 이 모델은 text-to-video 파이프라인을 지원하는 것이 특징입니다.

### 핵심 포인트
- larryvrh/MiniMax-H3-Turbo-Lora 모델의 likes가 402를 기록하며 트렌드에 진입했습니다.
- 해당 모델의 pipeline_tag는 text-to-video로 분류됩니다.
- 현재 downloads는 0으로 기록되어 있습니다.

**태그**: MiniMax-H3-Turbo-Lora, text-to-video, Hugging Face

**Metrics**: {"likes": 402, "downloads": 0, "num_parameters": 0, "pipeline_tag": "text-to-video"}

### 원문 설명
likes=402, downloads=0, pipeline_tag=text-to-video

---

## 2. [LiquidAI/LFM2.5-2.6B](https://huggingface.co/LiquidAI/LFM2.5-2.6B)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
LiquidAI에서 출시한 LFM2.5-2.6B 모델이 Hugging Face에서 높은 다운로드 수를 기록하며 주목받고 있습니다. 약 2.7B 파라미터를 가진 이 모델은 text-generation 태그로 분류된 텍스트 생성 모델입니다.

### 핵심 포인트
- LiquidAI에서 공개한 2.6B 규모의 text-generation 모델입니다.
- 77,973회의 다운로드와 370개의 likes를 기록하며 높은 관심을 받고 있습니다.
- 모델의 파라미터 수는 약 2.69B(2,697,198,592)입니다.

**태그**: LiquidAI, LFM2.5-2.6B, text-generation

**Metrics**: {"likes": 370, "downloads": 77973, "num_parameters": 2697198592, "pipeline_tag": "text-generation"}

### 원문 설명
likes=370, downloads=77973, pipeline_tag=text-generation

---

## 3. [MiniMaxAI/MiniMax-H3](https://huggingface.co/MiniMaxAI/MiniMax-H3)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
MiniMaxAI에서 공개한 MiniMax-H3 모델이 Hugging Face에서 주목받고 있습니다. 이 모델은 image-text-to-video 파이프라인을 지원하는 것이 특징입니다.

### 핵심 포인트
- MiniMax-H3 모델은 image-text-to-video 태그를 가진 비디오 생성 모델입니다.
- 약 33.1B(33,122,992,896) 규모의 파라미터를 보유하고 있습니다.
- 높은 다운로드 수(18,112)와 좋아요(2,925)를 기록하며 트렌드 모델로 부상했습니다.

**태그**: MiniMax-H3, image-text-to-video, MiniMaxAI

**Metrics**: {"likes": 2925, "downloads": 18112, "num_parameters": 33122992896, "pipeline_tag": "image-text-to-video"}

### 원문 설명
likes=2925, downloads=18112, pipeline_tag=image-text-to-video

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

