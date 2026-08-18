# Model & Eval Signals (2026-08-19)

## 오늘의 요약
Hugging Face의 신규 모델(LTX-2.5, Qwen3.8 계열)이 높은 다운로드 수를 기록하며 주목받는 가운데, LiveCodeBench 벤치마크에서는 O4-Mini 및 Gemini 시리즈 모델들이 상위권 성적을 기록하며 코딩 성능 경쟁이 이어지고 있습니다.

### 오늘의 핵심 포인트
- Lightricks의 LTX-2.5 및 Qwen3.8 기반 모델들이 높은 다운로드 수를 기록하며 트렌드 형성
- image-to-video 및 image-text-to-text 등 멀티모달 기능 중심의 모델 활용 증가
- LiveCodeBench 벤치마크에서 O4-Mini와 Gemini 시리즈 모델들의 상위권 성적 기록

**오늘의 태그**: HuggingFace, LiveCodeBench, LLM_Trending

## 1. [Lightricks/LTX-2.5](https://huggingface.co/Lightricks/LTX-2.5)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Lightricks에서 공개한 LTX-2.5 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 image-to-video 파이프라인을 지원하는 것이 특징입니다.

### 핵심 포인트
- Lightricks에서 출시한 LTX-2.5 모델
- 50만 회 이상의 높은 다운로드 수 기록
- image-to-video 기능을 제공하는 모델

**태그**: Lightricks, LTX-2.5, image-to-video

**Metrics**: {"likes": 1206, "downloads": 503632, "num_parameters": 0, "pipeline_tag": "image-to-video"}

### 원문 설명
likes=1206, downloads=503632, pipeline_tag=image-to-video

---

## 2. [orcarouter/Qwen3.8-27B-Uncensored-FP8](https://huggingface.co/orcarouter/Qwen3.8-27B-Uncensored-FP8)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
orcarouter/Qwen3.8-27B-Uncensored-FP8 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 27B 규모의 파라미터를 가진 image-text-to-text 태스크용 모델입니다.

### 핵심 포인트
- orcarouter/Qwen3.8-27B-Uncensored-FP8 모델의 높은 관심도(likes 511, downloads 45465) 확인
- 27.7B 규모의 파라미터를 보유한 모델임
- image-text-to-text 파이프라인을 지원함

**태그**: Qwen3.8-27B-Uncensored-FP8, image-text-to-text, Model Trending

**Metrics**: {"likes": 511, "downloads": 45465, "num_parameters": 27781427952, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=511, downloads=45465, pipeline_tag=image-text-to-text

---

## 3. [unsloth/Qwen3.8-27B-GGUF](https://huggingface.co/unsloth/Qwen3.8-27B-GGUF)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
unsloth에서 공개한 Qwen3.8-27B-GGUF 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 약 27B 파라미터를 가진 이 모델은 GGUF 포맷으로 제공됩니다.

### 핵심 포인트
- unsloth에서 배포한 Qwen3.8-27B-GGUF 모델의 트렌딩 현황
- 누적 다운로드 수 3,561,466회를 기록하며 높은 사용자 관심을 증명
- 약 27.3B 파라미터를 보유한 모델

**태그**: unsloth, Qwen3.8-27B-GGUF, GGUF

**Metrics**: {"likes": 1799, "downloads": 3561466, "num_parameters": 27320697856, "pipeline_tag": ""}

### 원문 설명
likes=1799, downloads=3561466, pipeline_tag=

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

