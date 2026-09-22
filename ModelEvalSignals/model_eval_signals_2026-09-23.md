# Model & Eval Signals (2026-09-23)

## 오늘의 요약
Hugging Face에서는 Qwen-Image-2.1 및 Hemmingway-1과 같은 신규 모델들이 높은 관심을 받고 있으며, LiveCodeBench에서는 O4-Mini와 Gemini 시리즈 모델들이 상위권 성적을 기록하며 코딩 성능 경쟁이 치열함을 보여주었습니다.

### 오늘의 핵심 포인트
- Qwen-Image-2.1 및 GGUF 포맷 모델의 높은 다운로드 수로 인한 사용자 관심 증대
- Altworld의 Hemmingway-1(26.9B) 모델 공개 및 주목
- LiveCodeBench 벤치마크에서 O4-Mini 및 Gemini 시리즈 모델들의 상위권 성적 기록

**오늘의 태그**: HuggingFace, LiveCodeBench, LLM_Trending

## 1. [abenzerps/Qwen-Image-2.1-Uncensored-GGUF](https://huggingface.co/abenzerps/Qwen-Image-2.1-Uncensored-GGUF)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
abenzerps/Qwen-Image-2.1-Uncensored-GGUF 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 text-to-image 파이프라인을 지원하는 GGUF 포맷의 모델입니다.

### 핵심 포인트
- 182,313회의 높은 downloads를 기록하며 트렌드에 진입함
- text-to-image 파이프라인을 지원하는 모델임
- 약 7.1B 규모의 파라미터를 가진 GGUF 포맷 모델임

**태그**: Qwen-Image-2.1-Uncensored-GGUF, text-to-image, GGUF

**Metrics**: {"likes": 1031, "downloads": 182313, "num_parameters": 7115124736, "pipeline_tag": "text-to-image"}

### 원문 설명
likes=1031, downloads=182313, pipeline_tag=text-to-image

---

## 2. [Altworld/Hemmingway-1](https://huggingface.co/Altworld/Hemmingway-1)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Altworld에서 공개한 Hemmingway-1 모델이 Hugging Face에서 주목받고 있습니다. 약 26.9B 파라미터를 가진 이 모델은 text-generation 태그로 분류되어 있습니다.

### 핵심 포인트
- Altworld/Hemmingway-1 모델이 Hugging Face에서 트렌딩 중입니다.
- 모델의 파라미터 규모는 약 26.9B입니다.
- 주요 작업은 text-generation 파이프라인을 지원합니다.

**태그**: Hemmingway-1, text-generation, LLM

**Metrics**: {"likes": 487, "downloads": 2745, "num_parameters": 26895998464, "pipeline_tag": "text-generation"}

### 원문 설명
likes=487, downloads=2745, pipeline_tag=text-generation

---

## 3. [Comfy-Org/Qwen-Image-2.1](https://huggingface.co/Comfy-Org/Qwen-Image-2.1)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Comfy-Org에서 공개한 Qwen-Image-2.1 모델이 Hugging Face에서 높은 다운로드 수를 기록하며 주목받고 있습니다. 해당 모델은 약 142만 회 이상의 다운로드를 기록하며 강력한 사용자 관심을 받고 있습니다.

### 핵심 포인트
- Comfy-Org에서 배포한 Qwen-Image-2.1 모델의 트렌딩 현황
- 1,429,925회의 높은 다운로드 수 기록
- 555개의 likes를 확보하며 사용자 관심을 입증

**태그**: Qwen-Image-2.1, Comfy-Org, Hugging Face

**Metrics**: {"likes": 555, "downloads": 1429925, "num_parameters": 0, "pipeline_tag": ""}

### 원문 설명
likes=555, downloads=1429925, pipeline_tag=

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

