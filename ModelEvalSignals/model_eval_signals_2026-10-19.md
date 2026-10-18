# Model & Eval Signals (2026-10-19)

## 오늘의 요약
Hugging Face의 신규 모델 출시로 인한 멀티모달 및 TTS 분야의 트렌드 형성과 LiveCodeBench를 통한 코딩 성능 벤치마크 결과가 주요 흐름을 이뤘습니다.

### 오늘의 핵심 포인트
- Hugging Face에서 이미지 생성(flux-3), 멀티모달(DeepSeek-V4.1), TTS(drama-3) 등 다양한 도메인의 모델들이 높은 관심을 받으며 트렌드에 진입함
- LiveCodeBench 벤치마크에서 O4-Mini 및 Gemini 시리즈 모델들이 상위권 성적을 기록하며 코딩 성능 경쟁을 보여줌
- 텍스트뿐만 아니라 이미지, 음성 등 멀티모달 기능과 대규모 파라미터를 활용한 특화 모델들의 활발한 배포가 관찰됨

**오늘의 태그**: HuggingFace, Multimodal, LiveCodeBench, LLM, TTS

## 1. [black-forest-labs/flux-3-image-klein-comfy](https://huggingface.co/black-forest-labs/flux-3-image-klein-comfy)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
black-forest-labs/flux-3-image-klein-comfy 모델이 Hugging Face에서 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 image-to-image 파이프라인을 지원하는 것이 특징입니다.

### 핵심 포인트
- black-forest-labs/flux-3-image-klein-comfy 모델의 높은 인기도 확인
- 338,036회의 downloads와 786 likes 기록
- image-to-image 파이프라인 태그를 사용하는 모델

**태그**: black-forest-labs, flux-3-image-klein-comfy, image-to-image

**Metrics**: {"likes": 786, "downloads": 338036, "num_parameters": 0, "pipeline_tag": "image-to-image"}

### 원문 설명
likes=786, downloads=338036, pipeline_tag=image-to-image

---

## 2. [deepseek-ai/DeepSeek-V4.1-Flash-1017](https://huggingface.co/deepseek-ai/DeepSeek-V4.1-Flash-1017)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
DeepSeek-AI에서 출시한 DeepSeek-V4.1-Flash-1017 모델이 Hugging Face에서 주목받고 있습니다. 이 모델은 이미지와 텍스트를 동시에 처리하는 멀티모달 기능을 제공합니다.

### 핵심 포인트
- DeepSeek-AI의 image-text-to-text 파이프라인 모델임
- 10,233회의 다운로드와 1,295개의 likes를 기록하며 트렌딩 중
- 약 763B 규모의 파라미터를 보유한 대형 모델임

**태그**: DeepSeek-V4.1-Flash-1017, image-text-to-text, DeepSeek-AI

**Metrics**: {"likes": 1295, "downloads": 10233, "num_parameters": 763205315794, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=1295, downloads=10233, pipeline_tag=image-text-to-text

---

## 3. [fishaudio/drama-3](https://huggingface.co/fishaudio/drama-3)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
fishaudio에서 공개한 drama-3 모델이 text-to-speech 분야에서 주목받고 있습니다. 약 35.9B 파라미터를 가진 대규모 모델로, 높은 다운로드 수를 기록하며 트렌드에 진입했습니다.

### 핵심 포인트
- fishaudio/drama-3 모델은 text-to-speech 파이프라인을 지원합니다.
- 모델 파라미터 규모는 약 35.9B입니다.
- 680개의 likes와 9,620회의 downloads를 기록하며 높은 관심을 받고 있습니다.

**태그**: fishaudio, text-to-speech, LLM

**Metrics**: {"likes": 680, "downloads": 9620, "num_parameters": 35899643008, "pipeline_tag": "text-to-speech"}

### 원문 설명
likes=680, downloads=9620, pipeline_tag=text-to-speech

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

