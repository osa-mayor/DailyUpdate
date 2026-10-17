# Model & Eval Signals (2026-10-18)

## 오늘의 요약
Hugging Face의 신규 모델 트렌드와 LiveCodeBench 벤치마크 성과를 중심으로 멀티모달, TTS, 코딩 성능 분야의 기술 동향이 관찰되었습니다.

### 오늘의 핵심 포인트
- Hugging Face에서 이미지 생성(flux-3), 멀티모달(DeepSeek-V4.1), TTS(drama-3) 등 다양한 도메인의 모델들이 높은 관심을 받으며 트렌드에 진입함
- LiveCodeBench 벤치마크에서 O4-Mini 및 Gemini 시리즈 모델들이 상위권 성적을 기록하며 코딩 성능 경쟁이 지속됨
- 이미지-텍스트 결합 및 텍스트-음성 변환 등 멀티모달 기능 중심의 모델 활용도가 높아지는 추세임

**오늘의 태그**: HuggingFace, LiveCodeBench, Multimodal, LLM, TTS

## 1. [black-forest-labs/flux-3-image-klein-comfy](https://huggingface.co/black-forest-labs/flux-3-image-klein-comfy)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
black-forest-labs/flux-3-image-klein-comfy 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 image-to-image 파이프라인을 지원하는 것이 특징입니다.

### 핵심 포인트
- black-forest-labs/flux-3-image-klein-comfy 모델의 높은 사용자 유입 확인
- 224,108회의 downloads와 626개의 likes 기록
- image-to-image 파이프라인 태그를 사용하는 모델

**태그**: black-forest-labs, flux-3-image-klein-comfy, image-to-image

**Metrics**: {"likes": 626, "downloads": 224108, "num_parameters": 0, "pipeline_tag": "image-to-image"}

### 원문 설명
likes=626, downloads=224108, pipeline_tag=image-to-image

---

## 2. [deepseek-ai/DeepSeek-V4.1-Flash-1017](https://huggingface.co/deepseek-ai/DeepSeek-V4.1-Flash-1017)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
DeepSeek-AI에서 출시한 DeepSeek-V4.1-Flash-1017 모델이 Hugging Face에서 주목받고 있습니다. 이 모델은 이미지와 텍스트를 동시에 처리하는 멀티모달 기능을 제공합니다.

### 핵심 포인트
- DeepSeek-AI에서 공개한 image-text-to-text 태그의 모델입니다.
- 856개의 likes를 기록하며 모델 트렌드에 진입했습니다.
- 약 763B 규모의 파라미터를 보유한 대형 모델입니다.

**태그**: DeepSeek-V4.1-Flash-1017, image-text-to-text, DeepSeek-AI

**Metrics**: {"likes": 856, "downloads": 0, "num_parameters": 763205315794, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=856, downloads=0, pipeline_tag=image-text-to-text

---

## 3. [fishaudio/drama-3](https://huggingface.co/fishaudio/drama-3)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
fishaudio에서 공개한 drama-3 모델이 text-to-speech 분야에서 주목받고 있습니다. 약 35.9B 파라미터를 보유한 이 모델은 최근 높은 다운로드 수를 기록하며 트렌드에 진입했습니다.

### 핵심 포인트
- fishaudio/drama-3 모델은 text-to-speech 파이프라인을 지원합니다.
- 모델의 파라미터 규모는 약 35.9B입니다.
- 최근 8,193회의 다운로드와 610개의 likes를 기록하며 트렌드에 진입했습니다.

**태그**: fishaudio, text-to-speech, LLM

**Metrics**: {"likes": 610, "downloads": 8193, "num_parameters": 35899643008, "pipeline_tag": "text-to-speech"}

### 원문 설명
likes=610, downloads=8193, pipeline_tag=text-to-speech

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

