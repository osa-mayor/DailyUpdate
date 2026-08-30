# Model & Eval Signals (2026-08-31)

## 오늘의 요약
Hugging Face의 신규 모델(LTX-2.5, GLM-5.3 등)이 높은 다운로드 수를 기록하며 주목받는 가운데, LiveCodeBench 벤치마크에서는 O4-Mini 및 Gemini 시리즈 모델들이 상위권 성적을 기록하며 코딩 성능 경쟁이 이어지고 있습니다.

### 오늘의 핵심 포인트
- Lightricks의 LTX-2.5 및 GLM-5.3 시리즈 등 신규 모델들의 Hugging Face 내 높은 트렌드 기록
- image-to-video 및 text-generation 등 다양한 파이프라인을 지원하는 모델들의 활발한 배포
- LiveCodeBench 벤치마크에서 O4-Mini와 Gemini 모델들이 상위권 성적을 기록하며 코딩 성능 입증

**오늘의 태그**: HuggingFace, LiveCodeBench, LLM_Trending

## 1. [Lightricks/LTX-2.5](https://huggingface.co/Lightricks/LTX-2.5)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Lightricks에서 공개한 LTX-2.5 모델이 Hugging Face에서 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 image-to-video 파이프라인을 지원하는 것이 특징입니다.

### 핵심 포인트
- Lightricks에서 출시한 LTX-2.5 모델의 트렌딩 현황
- 1,137,181회의 높은 다운로드 수를 기록하며 기술적 관심을 입증
- image-to-video 태그를 사용하는 이미지 기반 비디오 생성 모델

**태그**: Lightricks, LTX-2.5, image-to-video

**Metrics**: {"likes": 2241, "downloads": 1137181, "num_parameters": 0, "pipeline_tag": "image-to-video"}

### 원문 설명
likes=2241, downloads=1137181, pipeline_tag=image-to-video

---

## 2. [unsloth/GLM-5.3-Flash-GGUF](https://huggingface.co/unsloth/GLM-5.3-Flash-GGUF)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
unsloth/GLM-5.3-Flash-GGUF 모델이 Hugging Face에서 높은 다운로드 수를 기록하며 주목받고 있습니다. 해당 모델은 text-generation 파이프라인을 지원하는 GGUF 포맷의 모델입니다.

### 핵심 포인트
- unsloth/GLM-5.3-Flash-GGUF 모델의 높은 다운로드 수(45,936회) 기록
- text-generation 작업을 위한 GGUF 포맷 모델
- 약 320B 규모의 파라미터를 보유한 모델

**태그**: unsloth, GLM-5.3-Flash-GGUF, text-generation

**Metrics**: {"likes": 284, "downloads": 45936, "num_parameters": 320759404382, "pipeline_tag": "text-generation"}

### 원문 설명
likes=284, downloads=45936, pipeline_tag=text-generation

---

## 3. [zai-org/GLM-5.3](https://huggingface.co/zai-org/GLM-5.3)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
zai-org에서 공개한 GLM-5.3 모델이 Hugging Face에서 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 text-generation 태스크를 위한 대규모 파라미터를 가진 모델입니다.

### 핵심 포인트
- zai-org/GLM-5.3 모델이 50,116회의 다운로드를 기록하며 트렌딩 중입니다.
- 모델의 파라미터 규모는 약 753B(753,329,940,480) 수준입니다.
- text-generation 파이프라인을 지원하는 모델입니다.

**태그**: GLM-5.3, text-generation, Hugging Face

**Metrics**: {"likes": 1331, "downloads": 50116, "num_parameters": 753329940480, "pipeline_tag": "text-generation"}

### 원문 설명
likes=1331, downloads=50116, pipeline_tag=text-generation

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

