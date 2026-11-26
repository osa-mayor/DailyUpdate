# Model & Eval Signals (2026-11-27)

## 오늘의 요약
Hugging Face의 신규 모델 공개로 멀티모달 및 생성형 AI 기술이 주목받는 가운데, LiveCodeBench를 통해 코딩 성능이 우수한 모델들이 상위권을 기록했습니다.

### 오늘의 핵심 포인트
- Hugging Face에서 멀티모달(Inkling-2-Mini), 비디오 생성(LTX-2.5), 텍스트-이미지(Nemotron-Labs) 등 다양한 생성형 모델이 트렌드로 부상
- LiveCodeBench 벤치마크에서 O4-Mini 및 Gemini 시리즈 모델들이 상위권 성적 기록
- 이미지, 비디오, 코딩 등 특정 도메인에 특화된 모델들의 활발한 배포 및 성능 검증

**오늘의 태그**: Generative AI, Multimodal, LiveCodeBench

## 1. [AtomicChat/Inkling-2-Mini-Uncensored-GGUF](https://huggingface.co/AtomicChat/Inkling-2-Mini-Uncensored-GGUF)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
AtomicChat에서 공개한 Inkling-2-Mini-Uncensored-GGUF 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 이미지와 텍스트를 동시에 처리하는 멀티모달 기능을 갖춘 것이 특징입니다.

### 핵심 포인트
- Inkling-2-Mini-Uncensored-GGUF 모델의 다운로드 수가 762,491회를 기록하며 높은 관심을 받고 있습니다.
- 해당 모델은 image-text-to-text 파이프라인을 지원하는 멀티모달 모델입니다.
- 모델의 파라미터 규모는 약 26B(26,070,385,152) 수준입니다.

**태그**: Inkling-2-Mini-Uncensored-GGUF, image-text-to-text, GGUF

**Metrics**: {"likes": 923, "downloads": 762491, "num_parameters": 26070385152, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=923, downloads=762491, pipeline_tag=image-text-to-text

---

## 2. [Lightricks/LTX-2.5](https://huggingface.co/Lightricks/LTX-2.5)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Lightricks에서 공개한 LTX-2.5 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 image-to-video 파이프라인을 지원하는 것이 특징입니다.

### 핵심 포인트
- Lightricks에서 출시한 LTX-2.5 모델의 트렌드 상승
- 3,000,000회 이상의 높은 downloads 기록
- image-to-video 기능을 제공하는 모델 파이프라인

**태그**: Lightricks, LTX-2.5, image-to-video

**Metrics**: {"likes": 13571, "downloads": 3041405, "num_parameters": 0, "pipeline_tag": "image-to-video"}

### 원문 설명
likes=13571, downloads=3041405, pipeline_tag=image-to-video

---

## 3. [nvidia/Nemotron-Labs-Image-30B-A3B](https://huggingface.co/nvidia/Nemotron-Labs-Image-30B-A3B)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
NVIDIA에서 공개한 Nemotron-Labs-Image-30B-A3B 모델이 Hugging Face에서 주목받고 있습니다. 이 모델은 text-to-image 파이프라인을 지원하는 30B 규모의 모델입니다.

### 핵심 포인트
- NVIDIA의 Nemotron-Labs-Image-30B-A3B 모델 출시
- text-to-image 태그를 사용하는 이미지 생성 모델
- 약 32.6B 파라미터를 보유한 모델 규모

**태그**: NVIDIA, text-to-image, Nemotron-Labs-Image-30B-A3B

**Metrics**: {"likes": 268, "downloads": 218, "num_parameters": 32634904896, "pipeline_tag": "text-to-image"}

### 원문 설명
likes=268, downloads=218, pipeline_tag=text-to-image

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

