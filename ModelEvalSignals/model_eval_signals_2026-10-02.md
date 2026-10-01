# Model & Eval Signals (2026-10-02)

## 오늘의 요약
Hugging Face에서는 Qwen 기반의 이미지 생성 모델과 TeleOCR와 같은 멀티모달 모델이 높은 관심을 받고 있으며, LiveCodeBench에서는 Gemini 및 O4-Mini 모델들이 코딩 성능 벤치마크에서 상위권을 기록했습니다.

### 오늘의 핵심 포인트
- Hugging Face 내 Qwen-Image 시리즈 및 TeleOCR 모델의 높은 다운로드 수 기록
- LiveCodeBench 벤치마크에서 Gemini 및 O4-Mini 모델의 상위권 성적 달성
- Text-to-Image 및 Image-to-Text 등 멀티모달 생성 모델의 트렌드 지속

**오늘의 태그**: HuggingFace, LiveCodeBench, Multimodal, GenerativeAI

## 1. [Viggle/Qwen-Image-2.1-viggle-turbo](https://huggingface.co/Viggle/Qwen-Image-2.1-viggle-turbo)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Viggle/Qwen-Image-2.1-viggle-turbo 모델이 Hugging Face에서 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 text-to-image 파이프라인을 지원하는 생성형 모델입니다.

### 핵심 포인트
- Viggle/Qwen-Image-2.1-viggle-turbo 모델의 downloads가 217,638회를 기록하며 높은 관심을 받고 있습니다.
- 해당 모델의 pipeline_tag는 text-to-image로 분류됩니다.
- 모델의 파라미터 규모는 약 7.1B(7,115,124,736)입니다.

**태그**: Viggle/Qwen-Image-2.1-viggle-turbo, text-to-image, Hugging Face

**Metrics**: {"likes": 491, "downloads": 217638, "num_parameters": 7115124736, "pipeline_tag": "text-to-image"}

### 원문 설명
likes=491, downloads=217638, pipeline_tag=text-to-image

---

## 2. [Qwen/Qwen-Image-2.1](https://huggingface.co/Qwen/Qwen-Image-2.1)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Qwen/Qwen-Image-2.1 모델이 Hugging Face에서 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 text-to-image 파이프라인을 지원하는 것이 특징입니다.

### 핵심 포인트
- Qwen/Qwen-Image-2.1 모델의 높은 사용자 관심도 확인
- 76,938회의 다운로드와 2,763개의 likes 기록
- text-to-image 기능을 제공하는 약 7.1B 파라미터 규모의 모델

**태그**: Qwen-Image-2.1, text-to-image, Hugging Face

**Metrics**: {"likes": 2763, "downloads": 76938, "num_parameters": 7115124736, "pipeline_tag": "text-to-image"}

### 원문 설명
likes=2763, downloads=76938, pipeline_tag=text-to-image

---

## 3. [XingChen-AGI/TeleOCR](https://huggingface.co/XingChen-AGI/TeleOCR)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
XingChen-AGI에서 공개한 TeleOCR 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 image-text-to-text 파이프라인을 사용하는 1.4B 규모의 모델입니다.

### 핵심 포인트
- XingChen-AGI에서 공개한 TeleOCR 모델의 트렌딩 현황
- 약 1.4B(1,415,072,768) 파라미터를 가진 모델 규모
- image-text-to-text 파이프라인을 지원하는 모델

**태그**: TeleOCR, image-text-to-text, HuggingFace

**Metrics**: {"likes": 1201, "downloads": 31584, "num_parameters": 1415072768, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=1201, downloads=31584, pipeline_tag=image-text-to-text

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

