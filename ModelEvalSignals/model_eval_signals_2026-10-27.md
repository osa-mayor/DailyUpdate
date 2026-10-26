# Model & Eval Signals (2026-10-27)

## 오늘의 요약
Hugging Face를 중심으로 새로운 멀티모달 및 대규모 언어 모델(LLM)들이 트렌드에 진입하였으며, LiveCodeBench 벤치마크에서는 Gemini 시리즈와 O4-Mini 모델이 상위권 성적을 기록하며 코딩 능력을 입증했습니다.

### 오늘의 핵심 포인트
- MiniMax-M3.1-Flash 등 멀티모달 및 대규모 파라미터 모델의 Hugging Face 트렌드 진입
- DeepSeek-V4.1-Flash 및 Nanbeige4.3-33B 모델의 높은 다운로드 수 기록
- LiveCodeBench 벤치마크에서 Gemini-2.5 시리즈와 O4-Mini 모델의 우수한 성능 확인

**오늘의 태그**: HuggingFace, LLM, LiveCodeBench, Multi-modal, Benchmark

## 1. [MiniMaxAI/MiniMax-M3.1-Flash](https://huggingface.co/MiniMaxAI/MiniMax-M3.1-Flash)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
MiniMaxAI에서 출시한 MiniMax-M3.1-Flash 모델이 Hugging Face에서 주목받고 있습니다. 이 모델은 이미지와 텍스트를 동시에 처리하는 멀티모달 기능을 제공합니다.

### 핵심 포인트
- MiniMaxAI의 새로운 모델인 MiniMax-M3.1-Flash가 공개되었습니다.
- 8,782회의 다운로드와 381개의 likes를 기록하며 트렌딩 모델로 부상했습니다.
- image-text-to-text 파이프라인을 지원하는 멀티모달 모델입니다.

**태그**: MiniMax-M3.1-Flash, Multi-modal, Hugging Face

**Metrics**: {"likes": 381, "downloads": 8782, "num_parameters": 220490854016, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=381, downloads=8782, pipeline_tag=image-text-to-text

---

## 2. [ISTA-DASLab/DeepSeek-V4.1-Flash-1017-GSQ-RCO-GGUF](https://huggingface.co/ISTA-DASLab/DeepSeek-V4.1-Flash-1017-GSQ-RCO-GGUF)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
DeepSeek-V4.1-Flash-1017-GSQ-RCO-GGUF 모델이 Hugging Face에서 높은 다운로드 수를 기록하며 주목받고 있습니다. 약 196B 파라미터를 가진 이 모델은 text-generation 파이프라인을 지원합니다.

### 핵심 포인트
- DeepSeek-V4.1-Flash-1017-GSQ-RCO-GGUF 모델의 높은 사용자 유입 확인
- 891,147회의 다운로드와 335개의 likes 기록
- 약 196.6B 규모의 파라미터를 보유한 text-generation 모델

**태그**: DeepSeek-V4.1-Flash-1017-GSQ-RCO-GGUF, text-generation, Hugging Face

**Metrics**: {"likes": 335, "downloads": 891147, "num_parameters": 196613849600, "pipeline_tag": "text-generation"}

### 원문 설명
likes=335, downloads=891147, pipeline_tag=text-generation

---

## 3. [Nanbeige/Nanbeige4.3-33B](https://huggingface.co/Nanbeige/Nanbeige4.3-33B)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Nanbeige/Nanbeige4.3-33B 모델이 Hugging Face에서 텍스트 생성 태그와 함께 주목받고 있습니다. 약 33B 파라미터를 가진 이 모델은 최근 높은 다운로드 수를 기록하며 트렌드에 진입했습니다.

### 핵심 포인트
- Nanbeige/Nanbeige4.3-33B 모델의 Hugging Face 트렌드 진입
- 약 33B 규모의 파라미터를 보유한 text-generation 모델
- 2,787회의 다운로드와 578개의 likes를 기록하며 사용자 관심을 확보

**태그**: Nanbeige, text-generation, LLM

**Metrics**: {"likes": 578, "downloads": 2787, "num_parameters": 33118977024, "pipeline_tag": "text-generation"}

### 원문 설명
likes=578, downloads=2787, pipeline_tag=text-generation

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

