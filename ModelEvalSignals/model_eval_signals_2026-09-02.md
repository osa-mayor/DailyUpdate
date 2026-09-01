# Model & Eval Signals (2026-09-02)

## 오늘의 요약
Hugging Face에서는 멀티모달(Vision, Video) 및 GGUF 포맷 모델들이 높은 관심을 받았으며, LiveCodeBench에서는 Gemini 및 O4-Mini 모델들이 코딩 성능 상위권을 기록했습니다.

### 오늘의 핵심 포인트
- DeepSeek-V4-Flash-Vision-Exp 및 LTX-2.5 등 멀티모달(Image-to-Text/Video) 모델의 트렌드 강세
- unsloth의 Qwen3.8-Flash-Next-GGUF 모델이 높은 다운로드 수를 기록하며 효율적 추론 포맷에 대한 수요 확인
- LiveCodeBench 벤치마크에서 Gemini 시리즈와 O4-Mini 모델이 상위권 성적 기록

**오늘의 태그**: Multimodal, LiveCodeBench, HuggingFace_Trending

## 1. [deepseek-ai/DeepSeek-V4-Flash-Vision-Exp](https://huggingface.co/deepseek-ai/DeepSeek-V4-Flash-Vision-Exp)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
DeepSeek-AI에서 출시한 DeepSeek-V4-Flash-Vision-Exp 모델이 Hugging Face에서 주목받고 있습니다. 이 모델은 이미지와 텍스트를 결합하여 처리하는 image-text-to-text 태그의 모델입니다.

### 핵심 포인트
- DeepSeek-AI의 새로운 vision 실험 모델인 DeepSeek-V4-Flash-Vision-Exp 출시
- 17,893회의 다운로드와 438개의 likes를 기록하며 높은 관심을 받음
- image-text-to-text 파이프라인을 지원하는 약 304.6B 파라미터 규모의 모델

**태그**: DeepSeek-V4-Flash-Vision-Exp, image-text-to-text, DeepSeek-AI

**Metrics**: {"likes": 438, "downloads": 17893, "num_parameters": 304646824126, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=438, downloads=17893, pipeline_tag=image-text-to-text

---

## 2. [unsloth/Qwen3.8-Flash-Next-GGUF](https://huggingface.co/unsloth/Qwen3.8-Flash-Next-GGUF)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
unsloth에서 공개한 Qwen3.8-Flash-Next-GGUF 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 image-text-to-text 파이프라인을 지원하는 GGUF 포맷의 모델입니다.

### 핵심 포인트
- unsloth/Qwen3.8-Flash-Next-GGUF 모델의 높은 다운로드 수(431,339회) 기록
- image-text-to-text 파이프라인을 지원하는 멀티모달 성격의 모델
- 약 177B 규모의 파라미터를 가진 GGUF 포맷 모델

**태그**: unsloth, Qwen3.8-Flash-Next-GGUF, GGUF

**Metrics**: {"likes": 665, "downloads": 431339, "num_parameters": 176943899520, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=665, downloads=431339, pipeline_tag=image-text-to-text

---

## 3. [Lightricks/LTX-2.5](https://huggingface.co/Lightricks/LTX-2.5)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Lightricks에서 공개한 LTX-2.5 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 image-to-video 파이프라인을 지원하는 것이 특징입니다.

### 핵심 포인트
- Lightricks에서 출시한 LTX-2.5 모델
- 1,232,274회의 높은 다운로드 수를 기록하며 트렌드 형성
- image-to-video 기능을 제공하는 파이프라인 모델

**태그**: Lightricks, LTX-2.5, image-to-video

**Metrics**: {"likes": 2442, "downloads": 1232274, "num_parameters": 0, "pipeline_tag": "image-to-video"}

### 원문 설명
likes=2442, downloads=1232274, pipeline_tag=image-to-video

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

