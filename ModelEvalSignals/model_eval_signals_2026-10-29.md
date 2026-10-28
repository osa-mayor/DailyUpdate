# Model & Eval Signals (2026-10-29)

## 오늘의 요약
Hugging Face에서 다양한 규모의 텍스트 생성 모델들이 트렌드로 부상하였으며, LiveCodeBench 벤치마크를 통해 O4-Mini 및 Gemini 시리즈 모델들의 코딩 성능이 확인되었습니다.

### 오늘의 핵심 포인트
- LiquidAI, Nanbeige, DeepSeek 등 다양한 규모(1.7B~33B+)의 텍스트 생성 모델들이 Hugging Face 트렌드에 진입
- LiveCodeBench 벤치마크에서 O4-Mini 및 Gemini 시리즈 모델들이 상위권 성적 기록
- GGUF 포맷 및 특정 파라미터 규모의 모델들에 대한 사용자 관심 증가

**오늘의 태그**: LLM, HuggingFace, LiveCodeBench

## 1. [LiquidAI/LFM3-1.7B](https://huggingface.co/LiquidAI/LFM3-1.7B)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
LiquidAI에서 출시한 1.7B 규모의 text-generation 모델인 LFM3-1.7B가 Hugging Face에서 주목받고 있습니다. 약 8,892회의 다운로드와 354개의 likes를 기록하며 모델 트렌드에 진입했습니다.

### 핵심 포인트
- LiquidAI에서 공개한 1.7B 파라미터 규모의 text-generation 모델입니다.
- Hugging Face에서 8,892회의 다운로드와 354개의 likes를 기록하며 트렌딩 중입니다.
- 텍스트 생성(text-generation) 파이프라인을 지원하는 경량 모델입니다.

**태그**: LiquidAI, LFM3-1.7B, text-generation

**Metrics**: {"likes": 354, "downloads": 8892, "num_parameters": 1728801536, "pipeline_tag": "text-generation"}

### 원문 설명
likes=354, downloads=8892, pipeline_tag=text-generation

---

## 2. [Nanbeige/Nanbeige4.3-33B](https://huggingface.co/Nanbeige/Nanbeige4.3-33B)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Nanbeige/Nanbeige4.3-33B 모델이 Hugging Face에서 주목받으며 높은 다운로드 수를 기록하고 있습니다. 33B 파라미터 규모의 text-generation 모델로, 최근 사용자들의 관심을 끌고 있습니다.

### 핵심 포인트
- Nanbeige/Nanbeige4.3-33B 모델의 Hugging Face 트렌딩 기록
- 7,412회의 다운로드와 711개의 likes를 기록하며 높은 관심을 받음
- 33B 규모의 파라미터를 가진 text-generation 태그 모델

**태그**: Nanbeige, text-generation, LLM

**Metrics**: {"likes": 711, "downloads": 7412, "num_parameters": 33118977024, "pipeline_tag": "text-generation"}

### 원문 설명
likes=711, downloads=7412, pipeline_tag=text-generation

---

## 3. [ISTA-DASLab/DeepSeek-V4.1-Flash-1017-GSQ-RCO-GGUF](https://huggingface.co/ISTA-DASLab/DeepSeek-V4.1-Flash-1017-GSQ-RCO-GGUF)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
DeepSeek-V4.1-Flash-1017-GSQ-RCO-GGUF 모델이 Hugging Face에서 높은 다운로드 수를 기록하며 주목받고 있습니다. 약 1,966억 개의 파라미터를 가진 text-generation 태그의 모델입니다.

### 핵심 포인트
- DeepSeek-V4.1-Flash-1017-GSQ-RCO-GGUF 모델의 높은 인기도 확인
- 누적 다운로드 수 1,377,570회를 기록하며 활발히 사용됨
- 약 196.6B 규모의 파라미터를 보유한 text-generation 모델

**태그**: DeepSeek-V4.1-Flash-1017-GSQ-RCO-GGUF, text-generation, Hugging Face

**Metrics**: {"likes": 430, "downloads": 1377570, "num_parameters": 196613849600, "pipeline_tag": "text-generation"}

### 원문 설명
likes=430, downloads=1377570, pipeline_tag=text-generation

---

## 4. [LiveCodeBench top model: O4-Mini (High)](https://livecodebench.github.io/leaderboard.html)
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

## 5. [LiveCodeBench top model: Gemini-2.5-Pro-06-05](https://livecodebench.github.io/leaderboard.html)
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

## 6. [LiveCodeBench top model: Gemini-2.5-Flash-04-17](https://livecodebench.github.io/leaderboard.html)
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

