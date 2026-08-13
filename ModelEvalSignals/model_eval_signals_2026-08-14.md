# Model & Eval Signals (2026-08-14)

## 오늘의 요약
Hugging Face에서는 이미지 기반 비디오 생성 모델들이 높은 관심을 받고 있으며, LiveCodeBench에서는 다양한 최신 모델들이 코딩 성능 벤치마크 상위권을 기록했습니다.

### 오늘의 핵심 포인트
- Minimax-H3 및 LTX-2.5 등 Image-to-Video 파이프라인 지원 모델의 Hugging Face 트렌드 상승
- LiveCodeBench 벤치마크에서 O4-Mini, Gemini 시리즈 등 주요 모델들의 상위권 성적 기록
- 비디오 생성 기술과 코딩 성능 평가 모델 간의 기술적 흐름 분리

**오늘의 태그**: Video-Generation, LiveCodeBench, HuggingFace-Trending

## 1. [lightx2v/Minimax-h3-Turbo](https://huggingface.co/lightx2v/Minimax-h3-Turbo)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
lightx2v/Minimax-h3-Turbo 모델이 Hugging Face에서 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 image-to-video 파이프라인을 지원하는 것이 특징입니다.

### 핵심 포인트
- lightx2v/Minimax-h3-Turbo 모델의 높은 사용자 유입 확인
- 91,455회의 downloads와 452개의 likes 기록
- image-to-video 파이프라인을 활용한 모델

**태그**: Minimax-h3-Turbo, image-to-video, HuggingFace

**Metrics**: {"likes": 452, "downloads": 91455, "num_parameters": 0, "pipeline_tag": "image-to-video"}

### 원문 설명
likes=452, downloads=91455, pipeline_tag=image-to-video

---

## 2. [MiniMaxAI/MiniMax-H3](https://huggingface.co/MiniMaxAI/MiniMax-H3)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
MiniMaxAI에서 공개한 MiniMax-H3 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 image-text-to-video 파이프라인을 지원하는 것이 특징입니다.

### 핵심 포인트
- MiniMax-H3 모델은 약 33.1B 파라미터를 보유하고 있습니다.
- image-text-to-video 태그를 가진 비디오 생성 모델입니다.
- 1,605,940회의 다운로드와 3,812개의 likes를 기록하며 높은 관심을 받고 있습니다.

**태그**: MiniMax-H3, image-text-to-video, MiniMaxAI

**Metrics**: {"likes": 3812, "downloads": 1605940, "num_parameters": 33122992896, "pipeline_tag": "image-text-to-video"}

### 원문 설명
likes=3812, downloads=1605940, pipeline_tag=image-text-to-video

---

## 3. [Lightricks/LTX-2.5](https://huggingface.co/Lightricks/LTX-2.5)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Lightricks에서 공개한 LTX-2.5 모델이 Hugging Face에서 주목받고 있습니다. 이 모델은 image-to-video 파이프라인을 지원하는 것이 특징입니다.

### 핵심 포인트
- Lightricks에서 출시한 LTX-2.5 모델이 Hugging Face에서 높은 다운로드 수를 기록 중입니다.
- 해당 모델의 주요 기능은 image-to-video 파이프라인입니다.
- 약 57,287회의 다운로드와 696개의 likes를 기록하며 트렌딩 모델로 부상했습니다.

**태그**: LTX-2.5, image-to-video, Lightricks

**Metrics**: {"likes": 696, "downloads": 57287, "num_parameters": 0, "pipeline_tag": "image-to-video"}

### 원문 설명
likes=696, downloads=57287, pipeline_tag=image-to-video

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

