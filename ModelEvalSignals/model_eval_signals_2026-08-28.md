# Model & Eval Signals (2026-08-28)

## 오늘의 요약
Qwen3.8 기반의 다양한 양자화 및 최적화 모델들이 Hugging Face에서 높은 관심을 받고 있으며, LiveCodeBench 벤치마크에서는 O4-Mini와 Gemini 시리즈 모델들이 상위권 성적을 기록했습니다.

### 오늘의 핵심 포인트
- Qwen3.8 기반의 GGUF, MLX, FP8 포맷 모델들이 높은 다운로드 수를 기록하며 트렌드로 부상
- Qwen3.8 모델들은 image-text-to-text 파이프라인을 지원하는 것이 특징
- LiveCodeBench 벤치마크에서 O4-Mini 및 Gemini-2.5 시리즈 모델들이 상위권 성적 달성

**오늘의 태그**: Qwen3.8, LiveCodeBench, LLM_Optimization

## 1. [unsloth/Qwen3.8-Flash-Next-GGUF](https://huggingface.co/unsloth/Qwen3.8-Flash-Next-GGUF)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
unsloth에서 공개한 Qwen3.8-Flash-Next-GGUF 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 image-text-to-text 파이프라인을 지원하는 GGUF 포맷 모델입니다.

### 핵심 포인트
- unsloth에서 배포한 Qwen3.8-Flash-Next-GGUF 모델의 트렌딩 확인
- 4,354회의 다운로드와 440개의 likes를 기록하며 높은 관심을 받음
- image-text-to-text 기능을 지원하는 멀티모달 성격의 모델

**태그**: unsloth, Qwen3.8-Flash-Next-GGUF, image-text-to-text

**Metrics**: {"likes": 440, "downloads": 4354, "num_parameters": 176943899520, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=440, downloads=4354, pipeline_tag=image-text-to-text

---

## 2. [orcarouter/Qwen3.8-27B-Uncensored-MLX](https://huggingface.co/orcarouter/Qwen3.8-27B-Uncensored-MLX)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
orcarouter/Qwen3.8-27B-Uncensored-MLX 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 image-text-to-text 파이프라인을 지원하는 것이 특징입니다.

### 핵심 포인트
- 83,352회의 높은 다운로드 수를 기록하며 트렌드에 진입함
- image-text-to-text 파이프라인 태그를 가진 멀티모달 성격의 모델임
- 약 4.67B 규모의 파라미터를 보유함

**태그**: Qwen3.8-27B-Uncensored-MLX, image-text-to-text, MLX

**Metrics**: {"likes": 1164, "downloads": 83352, "num_parameters": 4665462000, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=1164, downloads=83352, pipeline_tag=image-text-to-text

---

## 3. [orcarouter/Qwen3.8-27B-Uncensored-FP8](https://huggingface.co/orcarouter/Qwen3.8-27B-Uncensored-FP8)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
orcarouter/Qwen3.8-27B-Uncensored-FP8 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 27B 규모의 파라미터를 가진 image-text-to-text 태스크용 모델입니다.

### 핵심 포인트
- 277,814,279,52개의 파라미터를 보유한 27B 규모 모델입니다.
- 273,577회의 다운로드와 1,206개의 likes를 기록하며 높은 관심을 받고 있습니다.
- image-text-to-text 파이프라인을 지원하는 모델입니다.

**태그**: Qwen3.8-27B-Uncensored-FP8, image-text-to-text, Model Trending

**Metrics**: {"likes": 1206, "downloads": 273577, "num_parameters": 27781427952, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=1206, downloads=273577, pipeline_tag=image-text-to-text

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

