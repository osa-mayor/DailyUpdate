# Model & Eval Signals (2026-10-22)

## 오늘의 요약
OpenMOSS-Team의 MOSS-Image 시리즈와 black-forest-labs의 flux 모델이 text-to-image 및 image-to-image 분야에서 높은 관심을 받았으며, LiveCodeBench에서는 Gemini와 O4-Mini 모델들이 상위권 성적을 기록했습니다.

### 오늘의 핵심 포인트
- OpenMOSS-Team의 MOSS-Image(SFT/Base) 모델이 5B 규모의 파라미터로 text-to-image 태스크에서 트렌드 진입
- black-forest-labs의 flux-3-image-klein-comfy 모델이 image-to-image 파이프라인으로 주목받음
- LiveCodeBench 벤치마크에서 O4-Mini 및 Gemini 시리즈 모델들이 상위권 성적 기록

**오늘의 태그**: Text-to-Image, LiveCodeBench, HuggingFace_Trending

## 1. [OpenMOSS-Team/MOSS-Image-SFT](https://huggingface.co/OpenMOSS-Team/MOSS-Image-SFT)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
OpenMOSS-Team에서 공개한 MOSS-Image-SFT 모델이 text-to-image 태스크를 중심으로 주목받고 있습니다. 약 5B 규모의 파라미터를 가진 이 모델은 최근 높은 다운로드 수를 기록하며 트렌드에 진입했습니다.

### 핵심 포인트
- OpenMOSS-Team에서 공개한 text-to-image 태스크용 모델입니다.
- 약 5.08B의 파라미터 규모를 가지고 있습니다.
- 최근 5,840회의 다운로드와 528개의 likes를 기록하며 트렌딩 중입니다.

**태그**: MOSS-Image-SFT, text-to-image, OpenMOSS-Team

**Metrics**: {"likes": 528, "downloads": 5840, "num_parameters": 5082308624, "pipeline_tag": "text-to-image"}

### 원문 설명
likes=528, downloads=5840, pipeline_tag=text-to-image

---

## 2. [OpenMOSS-Team/MOSS-Image-Base](https://huggingface.co/OpenMOSS-Team/MOSS-Image-Base)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
OpenMOSS-Team에서 공개한 MOSS-Image-Base 모델이 text-to-image 태스크를 중심으로 주목받고 있습니다. 약 5.08B 파라미터를 보유한 이 모델은 최근 높은 다운로드 수를 기록하며 트렌드에 진입했습니다.

### 핵심 포인트
- OpenMOSS-Team에서 개발한 text-to-image 파이프라인 모델입니다.
- 모델의 파라미터 규모는 약 5.08B입니다.
- 최근 4,344회의 다운로드와 462개의 likes를 기록하며 트렌딩 중입니다.

**태그**: MOSS-Image-Base, text-to-image, OpenMOSS-Team

**Metrics**: {"likes": 462, "downloads": 4344, "num_parameters": 5082308624, "pipeline_tag": "text-to-image"}

### 원문 설명
likes=462, downloads=4344, pipeline_tag=text-to-image

---

## 3. [black-forest-labs/flux-3-image-klein-comfy](https://huggingface.co/black-forest-labs/flux-3-image-klein-comfy)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
black-forest-labs/flux-3-image-klein-comfy 모델이 Hugging Face에서 높은 관심을 받고 있습니다. 해당 모델은 image-to-image 파이프라인을 지원하며 많은 다운로드 수를 기록하고 있습니다.

### 핵심 포인트
- black-forest-labs/flux-3-image-klein-comfy 모델의 높은 다운로드 수(490,447회) 기록
- 1,178개의 likes를 기록하며 사용자들의 관심을 받음
- image-to-image 파이프라인 태그를 사용하는 모델임

**태그**: black-forest-labs, flux-3-image-klein-comfy, image-to-image

**Metrics**: {"likes": 1178, "downloads": 490447, "num_parameters": 0, "pipeline_tag": "image-to-image"}

### 원문 설명
likes=1178, downloads=490447, pipeline_tag=image-to-image

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

