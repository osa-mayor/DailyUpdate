# Model & Eval Signals (2026-08-23)

## 오늘의 요약
Qwen 27B 계열 모델들의 높은 다운로드 수와 LiveCodeBench 벤치마크에서의 상위 모델 성적이 두드러진 하루였습니다.

### 오늘의 핵심 포인트
- Qwen 27B 파라미터 규모의 다양한 변형 모델(OBLITERATED, Uncensored-MLX, GGUF)이 Hugging Face에서 높은 관심을 받음
- LiveCodeBench 벤치마크에서 O4-Mini(High) 및 Gemini 시리즈 모델들이 상위권 성적을 기록
- 양자화(GGUF) 및 특정 파이프라인(MLX) 등 목적에 따른 모델 최적화 수요 확인

**오늘의 태그**: Qwen, LiveCodeBench, LLM_Trending

## 1. [OBLITERATUS/Qwen3.8-27B-OBLITERATED](https://huggingface.co/OBLITERATUS/Qwen3.8-27B-OBLITERATED)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
OBLITERATUS/Qwen3.8-27B-OBLITERATED 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 27B 규모의 파라미터를 가진 text-generation 태그의 모델입니다.

### 핵심 포인트
- OBLITERATUS/Qwen3.8-27B-OBLITERATED 모델의 높은 트래픽 기록
- 약 164,950회의 downloads와 516개의 likes를 기록
- 26.9B 규모의 파라미터를 보유한 text-generation 모델

**태그**: Qwen3.8-27B-OBLITERATED, text-generation, LLM

**Metrics**: {"likes": 516, "downloads": 164950, "num_parameters": 26895998464, "pipeline_tag": "text-generation"}

### 원문 설명
likes=516, downloads=164950, pipeline_tag=text-generation

---

## 2. [orcarouter/Qwen3.8-27B-Uncensored-MLX](https://huggingface.co/orcarouter/Qwen3.8-27B-Uncensored-MLX)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Qwen3.8-27B-Uncensored-MLX 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 image-text-to-text 파이프라인을 지원하는 것이 특징입니다.

### 핵심 포인트
- orcarouter/Qwen3.8-27B-Uncensored-MLX 모델의 높은 사용자 관심도 확인
- 34,909회의 다운로드와 875개의 likes 기록
- image-text-to-text 파이프라인을 지원하는 모델

**태그**: Qwen3.8-27B-Uncensored-MLX, MLX, image-text-to-text

**Metrics**: {"likes": 875, "downloads": 34909, "num_parameters": 4665462000, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=875, downloads=34909, pipeline_tag=image-text-to-text

---

## 3. [unsloth/Qwen3.8-27B-GGUF](https://huggingface.co/unsloth/Qwen3.8-27B-GGUF)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
unsloth/Qwen3.8-27B-GGUF 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 약 27B 파라미터를 가진 Qwen 기반의 GGUF 양자화 모델입니다.

### 핵심 포인트
- unsloth/Qwen3.8-27B-GGUF 모델의 누적 다운로드 수가 6,320,542회를 기록함
- 약 27.3B 파라미터를 보유한 모델로 2,602개의 likes를 확보함
- GGUF 포맷을 통해 배포되는 Qwen 기반 모델임

**태그**: Qwen, GGUF, unsloth

**Metrics**: {"likes": 2602, "downloads": 6320542, "num_parameters": 27320697856, "pipeline_tag": ""}

### 원문 설명
likes=2602, downloads=6320542, pipeline_tag=

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

