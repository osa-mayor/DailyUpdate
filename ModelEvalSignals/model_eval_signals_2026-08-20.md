# Model & Eval Signals (2026-08-20)

## 오늘의 요약
Qwen 기반 27B 모델들의 양자화 및 특수 목적 모델이 주목받는 가운데, LTX-2.5의 비디오 생성 모델 공개와 LiveCodeBench에서의 상위 모델 성적이 주요 흐름으로 나타났습니다.

### 오늘의 핵심 포인트
- Qwen 27B 기반의 GGUF 및 Uncensored MLX 모델이 높은 관심을 받으며 효율적인 추론 및 특수 목적 활용 가능성 확인
- Lightricks의 LTX-2.5 공개로 인한 image-to-video 파이프라인 기술 트렌드 부각
- LiveCodeBench 벤치마크에서 O4-Mini 및 Gemini 시리즈 모델들이 상위권 성적 기록

**오늘의 태그**: Qwen, LLM_Quantization, Image-to-Video, LiveCodeBench, Gemini

## 1. [unsloth/Qwen3.8-27B-GGUF](https://huggingface.co/unsloth/Qwen3.8-27B-GGUF)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
unsloth/Qwen3.8-27B-GGUF 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 해당 모델은 27B 파라미터 규모의 Qwen 기반 GGUF 양자화 모델입니다.

### 핵심 포인트
- unsloth/Qwen3.8-27B-GGUF 모델의 높은 인기도 확인
- 4,318,342회의 다운로드와 2,003개의 likes 기록
- 27B 규모의 파라미터를 가진 Qwen 기반 모델

**태그**: Qwen, GGUF, unsloth

**Metrics**: {"likes": 2003, "downloads": 4318134, "num_parameters": 27320697856, "pipeline_tag": ""}

### 원문 설명
likes=2003, downloads=4318134, pipeline_tag=

---

## 2. [orcarouter/Qwen3.8-27B-Uncensored-MLX](https://huggingface.co/orcarouter/Qwen3.8-27B-Uncensored-MLX)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
orcarouter/Qwen3.8-27B-Uncensored-MLX 모델이 Hugging Face에서 주목받고 있습니다. 이 모델은 image-text-to-text 파이프라인을 지원하는 27B 규모의 모델입니다.

### 핵심 포인트
- orcarouter/Qwen3.8-27B-Uncensored-MLX 모델의 likes가 563을 기록하며 트렌딩 중입니다.
- 해당 모델은 image-text-to-text 파이프라인 태그를 가진 멀티모달 성격의 모델입니다.
- 모델의 파라미터 규모는 약 4.67B 수준입니다.

**태그**: Qwen3.8-27B-Uncensored-MLX, image-text-to-text, Model Trending

**Metrics**: {"likes": 563, "downloads": 27, "num_parameters": 4665462000, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=563, downloads=27, pipeline_tag=image-text-to-text

---

## 3. [Lightricks/LTX-2.5](https://huggingface.co/Lightricks/LTX-2.5)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Lightricks에서 공개한 LTX-2.5 모델이 Hugging Face에서 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 image-to-video 파이프라인을 지원하는 것이 특징입니다.

### 핵심 포인트
- Lightricks에서 출시한 LTX-2.5 모델
- image-to-video 파이프라인 태그를 보유한 영상 생성 모델
- 555,993회의 높은 다운로드 수를 기록하며 트렌드 형성

**태그**: LTX-2.5, image-to-video, Lightricks

**Metrics**: {"likes": 1303, "downloads": 555993, "num_parameters": 0, "pipeline_tag": "image-to-video"}

### 원문 설명
likes=1303, downloads=555993, pipeline_tag=image-to-video

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

