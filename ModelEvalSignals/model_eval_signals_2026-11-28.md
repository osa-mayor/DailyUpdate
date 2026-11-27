# Model & Eval Signals (2026-11-28)

## 오늘의 요약
Hugging Face에서는 멀티모달(Image-to-Text, Image-to-Video) 기능 중심의 신규 모델들이 주목받았으며, LiveCodeBench에서는 O4-Mini 및 Gemini 시리즈 모델들이 상위권 성적을 기록하며 코딩 성능 경쟁을 보여주었습니다.

### 오늘의 핵심 포인트
- Inkling-2-Mini 시리즈 및 LTX-2.5 등 이미지/비디오 처리 파이프라인 지원 모델의 높은 관심
- LiveCodeBench 벤치마크에서 O4-Mini 및 Gemini 모델들의 상위권 성적 기록
- GGUF 포맷 및 멀티모달 기능을 갖춘 오픈 모델들의 활발한 배포

**오늘의 태그**: Multimodal, LiveCodeBench, HuggingFace_Trending

## 1. [AtomicChat/Inkling-2-Mini-Uncensored-GGUF](https://huggingface.co/AtomicChat/Inkling-2-Mini-Uncensored-GGUF)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
AtomicChat에서 공개한 Inkling-2-Mini-Uncensored-GGUF 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 이미지와 텍스트를 동시에 처리하는 image-text-to-text 파이프라인을 지원합니다.

### 핵심 포인트
- Inkling-2-Mini-Uncensored-GGUF 모델의 다운로드 수가 1,000,000회를 돌파하며 높은 관심을 받고 있습니다.
- 해당 모델은 약 26B 파라미터를 가진 image-text-to-text 태그의 모델입니다.
- GGUF 포맷으로 제공되어 다양한 환경에서의 활용 가능성을 보여줍니다.

**태그**: Inkling-2-Mini-Uncensored-GGUF, image-text-to-text, GGUF

**Metrics**: {"likes": 994, "downloads": 1059763, "num_parameters": 26070385152, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=994, downloads=1059763, pipeline_tag=image-text-to-text

---

## 2. [strata-engine/Inkling-2-Mini-Strata](https://huggingface.co/strata-engine/Inkling-2-Mini-Strata)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
strata-engine에서 공개한 Inkling-2-Mini-Strata 모델이 Hugging Face에서 주목받고 있습니다. 이 모델은 image-text-to-text 파이프라인을 지원하는 것이 특징입니다.

### 핵심 포인트
- Inkling-2-Mini-Strata 모델의 Hugging Face 배포
- image-text-to-text 태그를 사용하는 멀티모달 모델
- 4,532회의 다운로드와 276개의 likes를 기록 중

**태그**: Inkling-2-Mini-Strata, image-text-to-text, Hugging Face

**Metrics**: {"likes": 276, "downloads": 4532, "num_parameters": 0, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=276, downloads=4532, pipeline_tag=image-text-to-text

---

## 3. [Lightricks/LTX-2.5](https://huggingface.co/Lightricks/LTX-2.5)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Lightricks에서 공개한 LTX-2.5 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 image-to-video 파이프라인을 지원하는 것이 특징입니다.

### 핵심 포인트
- Lightricks에서 출시한 LTX-2.5 모델의 트렌드 상승
- 3,000,000회 이상의 높은 downloads 기록
- image-to-video 기능을 제공하는 모델 파이프라인

**태그**: Lightricks, LTX-2.5, image-to-video

**Metrics**: {"likes": 13688, "downloads": 3080701, "num_parameters": 0, "pipeline_tag": "image-to-video"}

### 원문 설명
likes=13688, downloads=3080701, pipeline_tag=image-to-video

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

