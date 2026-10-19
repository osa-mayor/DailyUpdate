# Model & Eval Signals (2026-10-20)

## 오늘의 요약
Hugging Face의 신규 모델 트렌드와 LiveCodeBench 벤치마크 결과가 주요 흐름을 형성하였으며, 특히 멀티모달 모델과 코딩 성능 중심의 모델들이 주목받았습니다.

### 오늘의 핵심 포인트
- OpenBMB, black-forest-labs, DeepSeek 등 다양한 기업의 멀티모달(Image-to-Text/Image) 모델이 높은 다운로드 수를 기록하며 트렌드를 주도함
- LiveCodeBench 벤치마크에서 O4-Mini 및 Gemini 시리즈 모델들이 상위권 성적을 기록하며 코딩 성능 경쟁을 보여줌
- 이미지-텍스트 결합 파이프라인을 지원하는 모델들의 활발한 배포가 관찰됨

**오늘의 태그**: HuggingFace, Multimodal, LiveCodeBench

## 1. [openbmb/MiniCPM-V-4.7-35B-A3B](https://huggingface.co/openbmb/MiniCPM-V-4.7-35B-A3B)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
OpenBMB에서 공개한 MiniCPM-V-4.7-35B-A3B 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 이미지와 텍스트를 결합하여 처리하는 image-text-to-text 파이프라인을 지원합니다.

### 핵심 포인트
- MiniCPM-V-4.7-35B-A3B 모델의 높은 사용자 관심도(likes 1,051, downloads 76,410)
- 35B 규모의 파라미터를 가진 image-text-to-text 태스크 특화 모델
- 멀티모달 작업 수행을 위한 효율적인 구조 제공

**태그**: MiniCPM-V-4.7-35B-A3B, image-text-to-text, OpenBMB

**Metrics**: {"likes": 1051, "downloads": 76410, "num_parameters": 35212875824, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=1051, downloads=76410, pipeline_tag=image-text-to-text

---

## 2. [black-forest-labs/flux-3-image-klein-comfy](https://huggingface.co/black-forest-labs/flux-3-image-klein-comfy)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
black-forest-labs/flux-3-image-klein-comfy 모델이 Hugging Face에서 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 image-to-image 파이프라인을 지원하는 것이 특징입니다.

### 핵심 포인트
- black-forest-labs/flux-3-image-klein-comfy 모델의 높은 인기도 확인
- 393,062회의 downloads와 938개의 likes 기록
- pipeline_tag는 image-to-image로 분류됨

**태그**: black-forest-labs, flux-3-image-klein-comfy, image-to-image

**Metrics**: {"likes": 938, "downloads": 393062, "num_parameters": 0, "pipeline_tag": "image-to-image"}

### 원문 설명
likes=938, downloads=393062, pipeline_tag=image-to-image

---

## 3. [deepseek-ai/DeepSeek-V4.1-Flash-1017](https://huggingface.co/deepseek-ai/DeepSeek-V4.1-Flash-1017)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
DeepSeek-V4.1-Flash-1017 모델이 Hugging Face에서 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 image-text-to-text 파이프라인을 지원하는 멀티모달 성격의 모델입니다.

### 핵심 포인트
- DeepSeek-V4.1-Flash-1017 모델의 높은 사용자 관심도(likes 1,654, downloads 17,924) 확인
- image-text-to-text 파이프라인을 지원하는 모델로 분류됨
- 약 763B 규모의 파라미터를 보유한 대형 모델

**태그**: DeepSeek-V4.1-Flash-1017, image-text-to-text, Model Trending

**Metrics**: {"likes": 1654, "downloads": 17924, "num_parameters": 763205315794, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=1654, downloads=17924, pipeline_tag=image-text-to-text

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

