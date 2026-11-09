# Model & Eval Signals (2026-11-10)

## 오늘의 요약
Hugging Face에서는 Qwen 기반의 멀티모달 및 텍스트 생성 모델들이 높은 관심을 받고 있으며, LiveCodeBench에서는 Gemini와 O4-Mini 모델들이 상위권 성적을 기록하며 코딩 성능 경쟁을 보여주었습니다.

### 오늘의 핵심 포인트
- Qwen 기반의 27B 및 9B 파라미터 규모 모델들이 Hugging Face에서 높은 다운로드와 관심을 기록함
- 이미지와 텍스트를 동시에 처리하는 멀티모달(image-text-to-text) 파이프라인 모델의 트렌드 확인
- LiveCodeBench 벤치마크에서 O4-Mini 및 Gemini 시리즈 모델들이 상위권 성적을 기록함

**오늘의 태그**: Qwen, LiveCodeBench, Multimodal, LLM-Trending

## 1. [DavidAU/Qwen3.8-27B-TURBO-Fable-Cold-Fusion-735-882-Heretic-Uncensored-NEO-CODER-MAX-MTP-GGUF](https://huggingface.co/DavidAU/Qwen3.8-27B-TURBO-Fable-Cold-Fusion-735-882-Heretic-Uncensored-NEO-CODER-MAX-MTP-GGUF)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
DavidAU에서 공개한 Qwen3.8-27B-TURBO-Fable-Cold-Fusion-735-882-Heretic-Uncensored-NEO-CODER-MAX-MTP-GGUF 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 약 26.9B 파라미터를 가진 image-text-to-text 파이프라인 모델입니다.

### 핵심 포인트
- 약 153만 회 이상의 높은 다운로드 수를 기록하며 트렌딩 중인 모델입니다.
- 26.9B 규모의 파라미터를 보유한 Qwen 기반 모델입니다.
- image-text-to-text 파이프라인 태그를 가진 멀티모달 성격의 모델입니다.

**태그**: Qwen, GGUF, image-text-to-text

**Metrics**: {"likes": 2759, "downloads": 1530688, "num_parameters": 26895998464, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=2759, downloads=1530688, pipeline_tag=image-text-to-text

---

## 2. [xtools-at/DeepSeek-V4-Pro-Qwen3.5-9B-UNCENSORED-heretic](https://huggingface.co/xtools-at/DeepSeek-V4-Pro-Qwen3.5-9B-UNCENSORED-heretic)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
DeepSeek-V4-Pro-Qwen3.5-9B-UNCENSORED-heretic 모델이 Hugging Face에서 높은 관심을 받고 있습니다. 약 9.4B 파라미터를 가진 이 모델은 text-generation 태그로 분류되어 있습니다.

### 핵심 포인트
- DeepSeek-V4-Pro-Qwen3.5-9B-UNCENSORED-heretic 모델의 높은 다운로드 수(11,755회)와 좋아요(1,020회) 기록
- 약 9.4B 규모의 파라미터를 보유한 text-generation 모델
- Hugging Face 내 모델 트렌드 반영

**태그**: DeepSeek-V4-Pro-Qwen3.5-9B-UNCENSORED-heretic, text-generation, Hugging Face

**Metrics**: {"likes": 1020, "downloads": 11755, "num_parameters": 9409813744, "pipeline_tag": "text-generation"}

### 원문 설명
likes=1020, downloads=11755, pipeline_tag=text-generation

---

## 3. [Qwen/Qwen3.8-27B](https://huggingface.co/Qwen/Qwen3.8-27B)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Qwen/Qwen3.8-27B 모델이 높은 다운로드 수와 좋아요를 기록하며 주목받고 있습니다. 이 모델은 이미지와 텍스트를 동시에 처리하는 image-text-to-text 파이프라인을 지원합니다.

### 핵심 포인트
- Qwen/Qwen3.8-27B 모델의 높은 사용자 관심도(likes 19,472, downloads 7,508,158) 확인
- 약 27.8B 파라미터를 보유한 모델 규모
- image-text-to-text 기능을 지원하는 멀티모달 모델

**태그**: Qwen, Multimodal, LLM

**Metrics**: {"likes": 19472, "downloads": 7508158, "num_parameters": 27781427952, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=19472, downloads=7508158, pipeline_tag=image-text-to-text

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

