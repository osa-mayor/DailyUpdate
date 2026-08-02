# Model & Eval Signals (2026-08-03)

## 오늘의 요약
DeepSeek 및 Qwen 기반의 고성능 모델들이 Hugging Face에서 높은 관심을 받고 있으며, SWE-bench와 LiveCodeBench를 중심으로 소프트웨어 엔지니어링 및 코딩 능력을 측정하는 새로운 벤치마크와 에이전트 학습 도구들이 주목받고 있습니다.

### 오늘의 핵심 포인트
- DeepSeek-V4-Flash 및 Qwen3.6 기반 모델들이 높은 다운로드 수를 기록하며 모델 트렌드를 주도함
- CodeClash와 같은 목표 지향적 개발자 평가 방식 및 mini-SWE-agent의 성과 등 소프트웨어 엔지니어링 에이전트 분야의 발전
- LiveCodeBench에서 O4-Mini 및 Gemini 시리즈 모델들이 상위권 성적을 기록하며 코딩 성능 경쟁 심화

**오늘의 태그**: LLM, DeepSeek, SWE-bench, LiveCodeBench, AI Agents

## 1. [unsloth/DeepSeek-V4-Flash-0731-GGUF](https://huggingface.co/unsloth/DeepSeek-V4-Flash-0731-GGUF)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
unsloth에서 공개한 DeepSeek-V4-Flash-0731-GGUF 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 해당 모델은 GGUF 포맷으로 제공되어 다양한 환경에서의 활용이 가능할 것으로 보입니다.

### 핵심 포인트
- unsloth에서 배포한 DeepSeek-V4-Flash-0731-GGUF 모델의 트렌딩 현황
- 48,707회의 높은 downloads 기록
- GGUF 포맷을 통한 모델 배포

**태그**: DeepSeek-V4-Flash-0731-GGUF, unsloth, GGUF

**Metrics**: {"likes": 325, "downloads": 48707, "num_parameters": 284334567511, "pipeline_tag": ""}

### 원문 설명
likes=325, downloads=48707, pipeline_tag=

---

## 2. [deepseek-ai/DeepSeek-V4-Flash-0731](https://huggingface.co/deepseek-ai/DeepSeek-V4-Flash-0731)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
DeepSeek-V4-Flash-0731 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 텍스트 생성 작업을 위한 모델로, 약 304B 규모의 파라미터를 보유하고 있습니다.

### 핵심 포인트
- DeepSeek-V4-Flash-0731 모델의 높은 사용자 관심도 반영 (downloads 156,173회)
- 약 304B 규모의 파라미터를 가진 text-generation 모델
- 1,646개의 likes를 기록하며 모델 트렌드 형성

**태그**: DeepSeek-V4-Flash-0731, text-generation, LLM

**Metrics**: {"likes": 1646, "downloads": 156173, "num_parameters": 304180418494, "pipeline_tag": "text-generation"}

### 원문 설명
likes=1646, downloads=156173, pipeline_tag=text-generation

---

## 3. [DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF](https://huggingface.co/DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Qwen3.6-27B 기반의 Uncensored 모델인 DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 image-text-to-text 파이프라인을 지원하는 27B 규모의 모델입니다.

### 핵심 포인트
- 1,372,285회의 높은 다운로드 수를 기록하며 모델 트렌드에 진입함
- 26.9B 규모의 파라미터를 가진 image-text-to-text 파이프라인 모델임
- GGUF 포맷으로 제공되는 Qwen3.6 기반의 Uncensored 모델임

**태그**: Qwen3.6, GGUF, image-text-to-text

**Metrics**: {"likes": 1309, "downloads": 1372285, "num_parameters": 26895998464, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=1309, downloads=1372285, pipeline_tag=image-text-to-text

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

