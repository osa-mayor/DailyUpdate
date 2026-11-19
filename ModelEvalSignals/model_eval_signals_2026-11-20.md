# Model & Eval Signals (2026-11-20)

## 오늘의 요약
Hugging Face에서는 멀티모달 및 비디오 생성 모델이 주목받고 있으며, LiveCodeBench에서는 코딩 성능을 갖춘 최신 모델들이 상위권을 기록했습니다.

### 오늘의 핵심 포인트
- Tencent와 Qwen의 멀티모달(image-text-to-text) 모델 및 Apple의 비디오 생성 모델(FastFrames-L)이 Hugging Face 트렌드 주도
- LiveCodeBench 벤치마크에서 O4-Mini, Gemini 시리즈 등 최신 모델들의 코딩 성능 검증
- 텍스트 기반 생성에서 비디오 및 멀티모달로 확장되는 모델 개발 동향 확인

**오늘의 태그**: Multimodal, Text-to-Video, LiveCodeBench

## 1. [tencent/Hy4-flash](https://huggingface.co/tencent/Hy4-flash)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Tencent에서 공개한 Hy4-flash 모델이 Hugging Face에서 주목받고 있습니다. 이 모델은 image-text-to-text 파이프라인을 지원하는 멀티모달 모델입니다.

### 핵심 포인트
- Tencent에서 출시한 Hy4-flash 모델이 Hugging Face에서 트렌딩 중입니다.
- 해당 모델은 image-text-to-text 태그를 가진 멀티모달 모델입니다.
- 현재 2,053회의 downloads와 325개의 likes를 기록하고 있습니다.

**태그**: Tencent, Hy4-flash, image-text-to-text

**Metrics**: {"likes": 325, "downloads": 2053, "num_parameters": 220251201958, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=325, downloads=2053, pipeline_tag=image-text-to-text

---

## 2. [harness-hub/Qwen3.8-27B-pi-adapted](https://huggingface.co/harness-hub/Qwen3.8-27B-pi-adapted)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Qwen3.8-27B-pi-adapted 모델이 Hugging Face에서 주목받고 있습니다. 이 모델은 image-text-to-text 파이프라인을 지원하는 것이 특징입니다.

### 핵심 포인트
- Qwen3.8-27B-pi-adapted 모델의 출시 및 트렌드 발생
- 709개의 likes와 1,320회의 downloads를 기록하며 높은 관심을 받음
- image-text-to-text 태그를 사용하는 멀티모달 관련 모델임

**태그**: Qwen3.8-27B-pi-adapted, image-text-to-text, Hugging Face

**Metrics**: {"likes": 709, "downloads": 1320, "num_parameters": 0, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=709, downloads=1320, pipeline_tag=image-text-to-text

---

## 3. [apple/FastFrames-L](https://huggingface.co/apple/FastFrames-L)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Apple에서 공개한 text-to-video 모델인 FastFrames-L이 Hugging Face에서 주목받고 있습니다. 현재 308개의 likes를 기록하며 새로운 비디오 생성 모델로서의 관심을 받고 있습니다.

### 핵심 포인트
- Apple에서 공개한 text-to-video 파이프라인 모델임
- Hugging Face에서 308 likes를 기록하며 트렌드에 진입함
- 비디오 생성 기술(text-to-video) 분야의 새로운 모델 동향을 보여줌

**태그**: apple, FastFrames-L, text-to-video

**Metrics**: {"likes": 308, "downloads": 0, "num_parameters": 0, "pipeline_tag": "text-to-video"}

### 원문 설명
likes=308, downloads=0, pipeline_tag=text-to-video

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

