# Model & Eval Signals (2026-07-31)

## 오늘의 요약
Hugging Face의 신규 모델 트렌드와 소프트웨어 엔지니어링 에이전트 및 코딩 성능을 측정하는 다양한 벤치마크 업데이트가 주요 흐름을 형성했습니다.

### 오늘의 핵심 포인트
- Hugging Face에서 TTS 및 멀티모달(image-text-to-text) 기능을 지원하는 GGUF 양자화 모델들이 높은 관심을 받고 있습니다.
- SWE-bench 팀은 목표 지향적 개발자 역량 측정을 위한 CodeClash를 소개하고, 에이전트 학습 도구인 SWE-smith를 출시했습니다.
- LiveCodeBench 결과, O4-Mini 및 Gemini 시리즈 모델들이 상위권 성적을 기록하며 코딩 성능 경쟁이 지속되고 있습니다.

**오늘의 태그**: HuggingFace, SWE-bench, LiveCodeBench, AI_Agents, LLM_Evaluation

## 1. [owensong/Inflect-Micro-v2](https://huggingface.co/owensong/Inflect-Micro-v2)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
owensong/Inflect-Micro-v2 모델이 Hugging Face에서 주목받고 있습니다. 이 모델은 text-to-speech 태스크를 위한 모델입니다.

### 핵심 포인트
- 모델명은 owensong/Inflect-Micro-v2입니다.
- pipeline_tag는 text-to-speech로 분류됩니다.
- likes 308회, downloads 1100회를 기록하며 트렌딩 중입니다.

**태그**: text-to-speech, Hugging Face, TTS

**Metrics**: {"likes": 308, "downloads": 1100, "num_parameters": 0, "pipeline_tag": "text-to-speech"}

### 원문 설명
likes=308, downloads=1100, pipeline_tag=text-to-speech

---

## 2. [unsloth/Kimi-K3-GGUF](https://huggingface.co/unsloth/Kimi-K3-GGUF)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
unsloth에서 공개한 Kimi-K3-GGUF 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 image-text-to-text 파이프라인을 지원하는 것이 특징입니다.

### 핵심 포인트
- unsloth에서 배포한 Kimi-K3-GGUF 모델의 트렌딩 확인
- 12,178회의 다운로드와 203개의 likes를 기록
- image-text-to-text 파이프라인을 지원하는 멀티모달 모델

**태그**: unsloth, Kimi-K3-GGUF, image-text-to-text

**Metrics**: {"likes": 203, "downloads": 12178, "num_parameters": 2779483135584, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=203, downloads=12178, pipeline_tag=image-text-to-text

---

## 3. [DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF](https://huggingface.co/DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
DavidAU에서 공개한 Qwen3.6-27B 기반의 GGUF 양자화 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 image-text-to-text 파이프라인을 지원하는 것이 특징입니다.

### 핵심 포인트
- Qwen3.6-27B 모델을 기반으로 제작된 GGUF 포맷의 모델입니다.
- 약 95만 회 이상의 다운로드와 1,000개 이상의 likes를 기록하며 높은 관심을 받고 있습니다.
- pipeline_tag는 image-text-to-text로 분류됩니다.

**태그**: Qwen3.6, GGUF, image-text-to-text

**Metrics**: {"likes": 1011, "downloads": 955767, "num_parameters": 26895998464, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=1011, downloads=955767, pipeline_tag=image-text-to-text

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

