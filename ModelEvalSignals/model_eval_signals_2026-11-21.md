# Model & Eval Signals (2026-11-21)

## 오늘의 요약
Hugging Face를 중심으로 멀티모달(Image-to-Text, Text-to-Video) 모델들이 주목받고 있으며, LiveCodeBench 벤치마크에서는 O4-Mini 및 Gemini 시리즈 모델들이 상위권 성적을 기록하며 코딩 성능 경쟁이 이어지고 있습니다.

### 오늘의 핵심 포인트
- Hugging Face에서 Qwen 및 SenseNova 계열의 멀티모달(image-text-to-text) 모델과 Apple의 FastFrames-L(text-to-video) 모델이 트렌드로 부상
- LiveCodeBench 벤치마크에서 O4-Mini(High)와 Gemini-2.5 시리즈 모델들이 상위권 성적 기록
- 새로운 비디오 생성 모델 및 코딩 특화 모델에 대한 기술적 관심 증가

**오늘의 태그**: Multimodal, Text-to-Video, LiveCodeBench, HuggingFace

## 1. [harness-hub/Qwen3.8-27B-pi-adapted](https://huggingface.co/harness-hub/Qwen3.8-27B-pi-adapted)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Qwen3.8-27B-pi-adapted 모델이 Hugging Face에서 주목받고 있습니다. 이 모델은 image-text-to-text 파이프라인을 지원하는 것이 특징입니다.

### 핵심 포인트
- harness-hub/Qwen3.8-27B-pi-adapted 모델의 출시 및 트렌드 확인
- 850개의 likes와 1,874회의 downloads를 기록하며 사용자 관심을 유도
- image-text-to-text 태그를 사용하는 멀티모달 관련 모델로 분류

**태그**: Qwen3.8-27B-pi-adapted, image-text-to-text, Hugging Face

**Metrics**: {"likes": 850, "downloads": 1874, "num_parameters": 0, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=850, downloads=1874, pipeline_tag=image-text-to-text

---

## 2. [sensenova/SenseNova-Loop-9B](https://huggingface.co/sensenova/SenseNova-Loop-9B)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
sensenova/SenseNova-Loop-9B 모델이 Hugging Face에서 주목받고 있습니다. 이 모델은 image-text-to-text 파이프라인을 지원하는 9B 규모의 모델입니다.

### 핵심 포인트
- sensenova/SenseNova-Loop-9B 모델의 출시 및 트렌드 확인
- image-text-to-text 태그를 가진 멀티모달 모델
- 약 9.6B 파라미터를 보유한 모델 규모

**태그**: SenseNova-Loop-9B, image-text-to-text, LLM

**Metrics**: {"likes": 437, "downloads": 1631, "num_parameters": 9656254576, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=437, downloads=1631, pipeline_tag=image-text-to-text

---

## 3. [apple/FastFrames-L](https://huggingface.co/apple/FastFrames-L)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Apple에서 공개한 text-to-video 모델인 FastFrames-L이 Hugging Face에서 주목받고 있습니다. 현재 485개의 likes를 기록하며 새로운 비디오 생성 모델로서의 관심을 받고 있습니다.

### 핵심 포인트
- apple/FastFrames-L 모델이 Hugging Face에 공개됨
- pipeline_tag는 text-to-video 분야임
- 현재 485 likes를 기록하며 트렌딩 중

**태그**: FastFrames-L, text-to-video, Apple

**Metrics**: {"likes": 485, "downloads": 0, "num_parameters": 0, "pipeline_tag": "text-to-video"}

### 원문 설명
likes=485, downloads=0, pipeline_tag=text-to-video

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

