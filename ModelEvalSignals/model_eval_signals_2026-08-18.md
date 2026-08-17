# Model & Eval Signals (2026-08-18)

## 오늘의 요약
Hugging Face에서는 LTX-2.5 및 Qwen 기반 모델들이 높은 다운로드 수를 기록하며 주목받았으며, LiveCodeBench에서는 O4-Mini와 Gemini 시리즈 모델들이 상위권 성적을 기록했습니다.

### 오늘의 핵심 포인트
- Lightricks의 LTX-2.5 및 Qwen 27B 계열 모델(Uncensored, GGUF)의 높은 트렌드 기록
- LiveCodeBench 벤치마크에서 O4-Mini 및 Gemini 모델들의 상위권 성능 입증
- 이미지 생성, 양자화, 코딩 능력 등 다양한 도메인의 모델 성능 및 활용도 증가

**오늘의 태그**: HuggingFace, LiveCodeBench, LLM, VideoGeneration, Quantization

## 1. [Lightricks/LTX-2.5](https://huggingface.co/Lightricks/LTX-2.5)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Lightricks에서 공개한 LTX-2.5 모델이 Hugging Face에서 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 image-to-video 파이프라인을 지원하는 것이 특징입니다.

### 핵심 포인트
- Lightricks에서 출시한 LTX-2.5 모델의 트렌드 확인
- 465,529회의 높은 다운로드 수를 기록하며 높은 관심을 받음
- image-to-video 태그를 가진 이미지 투 비디오 생성 모델

**태그**: Lightricks, LTX-2.5, image-to-video

**Metrics**: {"likes": 1092, "downloads": 465529, "num_parameters": 0, "pipeline_tag": "image-to-video"}

### 원문 설명
likes=1092, downloads=465529, pipeline_tag=image-to-video

---

## 2. [orcarouter/Qwen3.8-27B-Uncensored-FP8](https://huggingface.co/orcarouter/Qwen3.8-27B-Uncensored-FP8)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
orcarouter/Qwen3.8-27B-Uncensored-FP8 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 image-text-to-text 파이프라인을 지원하는 27B 규모의 모델입니다.

### 핵심 포인트
- orcarouter/Qwen3.8-27B-Uncensored-FP8 모델의 높은 관심도(likes 424, downloads 15812) 확인
- 27.7B 파라미터를 가진 모델로 image-text-to-text 태그를 보유함
- FP8 양자화가 적용된 것으로 추정되는 Uncensored 모델

**태그**: Qwen3.8-27B-Uncensored-FP8, image-text-to-text, LLM

**Metrics**: {"likes": 424, "downloads": 15812, "num_parameters": 27781427952, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=424, downloads=15812, pipeline_tag=image-text-to-text

---

## 3. [unsloth/Qwen3.8-27B-GGUF](https://huggingface.co/unsloth/Qwen3.8-27B-GGUF)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
unsloth/Qwen3.8-27B-GGUF 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 해당 모델은 약 27B 파라미터를 가진 Qwen 기반의 GGUF 양자화 모델입니다.

### 핵심 포인트
- unsloth/Qwen3.8-27B-GGUF 모델의 누적 다운로드 수가 2,727,609회를 기록함
- 약 27.3B 파라미터를 보유한 모델로 1,612개의 likes를 확보함
- GGUF 포맷을 통해 로컬 환경에서의 활용도가 높을 것으로 예상됨

**태그**: unsloth, Qwen, GGUF

**Metrics**: {"likes": 1612, "downloads": 2727609, "num_parameters": 27320697856, "pipeline_tag": ""}

### 원문 설명
likes=1612, downloads=2727609, pipeline_tag=

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

