# Model & Eval Signals (2026-08-21)

## 오늘의 요약
Qwen 27B 기반의 다양한 양자화(GGUF, FP8, MLX) 모델들이 높은 다운로드 수를 기록하며 트렌드를 주도하고 있으며, LiveCodeBench 벤치마크에서는 O4-Mini와 Gemini 시리즈 모델들이 상위권 성적을 기록했습니다.

### 오늘의 핵심 포인트
- Qwen 27B 규모의 양자화 모델(GGUF, FP8, MLX)들이 Hugging Face에서 높은 주목을 받으며 배포됨
- Uncensored 및 멀티모달(image-text-to-text) 기능을 지원하는 Qwen 기반 모델들의 수요 증가
- LiveCodeBench 벤치마크에서 O4-Mini 및 Gemini 모델들이 상위권 성적을 기록하며 코딩 성능 입증

**오늘의 태그**: Qwen, GGUF, LiveCodeBench, LLM_Quantization, Gemini

## 1. [unsloth/Qwen3.8-27B-GGUF](https://huggingface.co/unsloth/Qwen3.8-27B-GGUF)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
unsloth/Qwen3.8-27B-GGUF 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 약 27B 파라미터를 가진 Qwen 기반의 GGUF 양자화 모델입니다.

### 핵심 포인트
- unsloth/Qwen3.8-27B-GGUF 모델의 누적 다운로드 수가 5,126,652회를 기록함
- 약 27.3B 파라미터를 보유한 모델로, GGUF 포맷으로 제공됨
- 2,325개의 likes를 기록하며 사용자들 사이에서 높은 관심을 받고 있음

**태그**: unsloth, Qwen, GGUF

**Metrics**: {"likes": 2325, "downloads": 5126652, "num_parameters": 27320697856, "pipeline_tag": ""}

### 원문 설명
likes=2325, downloads=5126652, pipeline_tag=

---

## 2. [orcarouter/Qwen3.8-27B-Uncensored-FP8](https://huggingface.co/orcarouter/Qwen3.8-27B-Uncensored-FP8)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Qwen3.8-27B-Uncensored-FP8 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 image-text-to-text 파이프라인을 지원하는 27B 규모의 모델입니다.

### 핵심 포인트
- orcarouter/Qwen3.8-27B-Uncensored-FP8 모델의 높은 트렌드 기록
- 76,109회의 downloads와 671개의 likes를 기록
- image-text-to-text 파이프라인을 지원하는 27B 규모의 모델

**태그**: Qwen3.8-27B-Uncensored-FP8, image-text-to-text, Model Trending

**Metrics**: {"likes": 671, "downloads": 76109, "num_parameters": 27781427952, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=671, downloads=76109, pipeline_tag=image-text-to-text

---

## 3. [orcarouter/Qwen3.8-27B-Uncensored-MLX](https://huggingface.co/orcarouter/Qwen3.8-27B-Uncensored-MLX)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
orcarouter/Qwen3.8-27B-Uncensored-MLX 모델이 Hugging Face에서 주목받고 있습니다. 이 모델은 image-text-to-text 파이프라인을 지원하며 높은 다운로드 수를 기록 중입니다.

### 핵심 포인트
- orcarouter/Qwen3.8-27B-Uncensored-MLX 모델의 높은 관심도(likes 692, downloads 2628)
- image-text-to-text 파이프라인을 지원하는 멀티모달 성격의 모델
- 약 4.67B 규모의 파라미터를 보유한 모델

**태그**: Qwen3.8-27B-Uncensored-MLX, image-text-to-text, MLX

**Metrics**: {"likes": 692, "downloads": 2628, "num_parameters": 4665462000, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=692, downloads=2628, pipeline_tag=image-text-to-text

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

