# Model & Eval Signals (2026-10-23)

## 오늘의 요약
Hugging Face에서는 텍스트 생성 및 이미지 생성(text-to-image) 분야의 신규 모델들이 주목받고 있으며, LiveCodeBench에서는 Gemini 및 O4-Mini 모델들이 상위권 성적을 기록하며 코딩 성능 경쟁을 보여주었습니다.

### 오늘의 핵심 포인트
- RecursiveSI의 flint(40B) 및 OpenMOSS-Team의 MOSS-Image 시리즈 등 신규 모델 트렌드 확인
- MOSS-Image-Base 모델이 5B 규모로 높은 다운로드 수를 기록하며 text-to-image 분야 트렌드 진입
- LiveCodeBench 벤치마크에서 Gemini 시리즈와 O4-Mini 모델이 상위권 성적 기록

**오늘의 태그**: HuggingFace, LiveCodeBench, Text-to-Image, LLM_Benchmark

## 1. [RecursiveSI/flint](https://huggingface.co/RecursiveSI/flint)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
RecursiveSI에서 공개한 flint 모델이 Hugging Face에서 주목받고 있습니다. 약 40B 파라미터 규모의 text-generation 모델로, 최근 사용자들의 관심을 끌고 있습니다.

### 핵심 포인트
- RecursiveSI에서 공개한 flint 모델이 Hugging Face에서 트렌딩 중입니다.
- 약 39.8B 파라미터를 보유한 text-generation 태그의 모델입니다.
- likes 510회, downloads 420회를 기록하며 사용자 관심을 받고 있습니다.

**태그**: flint, text-generation, RecursiveSI

**Metrics**: {"likes": 510, "downloads": 420, "num_parameters": 39785287456, "pipeline_tag": "text-generation"}

### 원문 설명
likes=510, downloads=420, pipeline_tag=text-generation

---

## 2. [OpenMOSS-Team/MOSS-Image-SFT](https://huggingface.co/OpenMOSS-Team/MOSS-Image-SFT)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
OpenMOSS-Team에서 공개한 MOSS-Image-SFT 모델이 Hugging Face에서 주목받고 있습니다. 이 모델은 text-to-image 파이프라인을 지원하는 SFT 모델입니다.

### 핵심 포인트
- OpenMOSS-Team에서 공개한 text-to-image 모델인 MOSS-Image-SFT입니다.
- 약 5.08B 규모의 파라미터를 보유하고 있습니다.
- 높은 다운로드 수와 좋아요를 기록하며 모델 트렌드에 진입했습니다.

**태그**: MOSS-Image-SFT, text-to-image, SFT

**Metrics**: {"likes": 570, "downloads": 6890, "num_parameters": 5082308624, "pipeline_tag": "text-to-image"}

### 원문 설명
likes=570, downloads=6890, pipeline_tag=text-to-image

---

## 3. [OpenMOSS-Team/MOSS-Image-Base](https://huggingface.co/OpenMOSS-Team/MOSS-Image-Base)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
OpenMOSS-Team에서 공개한 MOSS-Image-Base 모델이 text-to-image 태스크를 중심으로 주목받고 있습니다. 약 50억 개의 파라미터를 보유한 이 모델은 최근 높은 다운로드 수를 기록하며 트렌드에 진입했습니다.

### 핵심 포인트
- OpenMOSS-Team에서 개발한 text-to-image 모델입니다.
- 모델의 파라미터 규모는 약 5.08B입니다.
- 최근 5,000회 이상의 다운로드와 484개의 likes를 기록하며 트렌드에 진입했습니다.

**태그**: MOSS-Image-Base, text-to-image, OpenMOSS-Team

**Metrics**: {"likes": 484, "downloads": 5013, "num_parameters": 5082308624, "pipeline_tag": "text-to-image"}

### 원문 설명
likes=484, downloads=5013, pipeline_tag=text-to-image

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

