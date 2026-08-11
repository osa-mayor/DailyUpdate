# Model & Eval Signals (2026-08-12)

## 오늘의 요약
Hugging Face에서는 멀티모달(Image-to-Video, Text-to-Video) 모델들이 높은 관심을 받고 있으며, LiveCodeBench에서는 Gemini 및 O4-Mini 모델들이 코딩 성능 벤치마크에서 상위권을 기록했습니다.

### 오늘의 핵심 포인트
- Hugging Face 내 이미지 및 비디오 생성/변환 관련 멀티모달 모델(Muse-Glimmer, MiniMax-H3 등)의 트렌드 지속
- LiveCodeBench 벤치마크에서 Gemini 시리즈 및 O4-Mini 모델의 우수한 코딩 성능 확인
- 텍스트를 넘어 비디오 생성 파이프라인을 지원하는 모델들의 활발한 공개

**오늘의 태그**: Multimodal, LiveCodeBench, HuggingFace_Trending

## 1. [meta-models/Muse-Glimmer-30B](https://huggingface.co/meta-models/Muse-Glimmer-30B)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
meta-models/Muse-Glimmer-30B 모델이 Hugging Face에서 주목받고 있습니다. 이 모델은 약 29.8B 파라미터를 가진 image-text-to-text 태스크용 모델입니다.

### 핵심 포인트
- meta-models/Muse-Glimmer-30B 모델의 출시 및 트렌드 발생
- 약 29.8B 규모의 파라미터를 보유한 모델
- image-text-to-text 파이프라인을 지원하는 멀티모달 모델

**태그**: meta-models/Muse-Glimmer-30B, image-text-to-text, LLM

**Metrics**: {"likes": 1048, "downloads": 0, "num_parameters": 29776626688, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=1048, downloads=0, pipeline_tag=image-text-to-text

---

## 2. [lightx2v/Minimax-h3-Turbo](https://huggingface.co/lightx2v/Minimax-h3-Turbo)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
lightx2v/Minimax-h3-Turbo 모델이 Hugging Face에서 주목받고 있습니다. 이 모델은 image-to-video 파이프라인을 지원하는 것이 특징입니다.

### 핵심 포인트
- lightx2v/Minimax-h3-Turbo 모델의 높은 다운로드 수 기록
- image-to-video 파이프라인 태그를 보유한 모델
- 20,376회의 다운로드와 324개의 likes를 기록하며 트렌드 형성

**태그**: Minimax-h3-Turbo, image-to-video, Hugging Face

**Metrics**: {"likes": 324, "downloads": 20376, "num_parameters": 0, "pipeline_tag": "image-to-video"}

### 원문 설명
likes=324, downloads=20376, pipeline_tag=image-to-video

---

## 3. [MiniMaxAI/MiniMax-H3](https://huggingface.co/MiniMaxAI/MiniMax-H3)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
MiniMaxAI에서 공개한 MiniMax-H3 모델이 Hugging Face에서 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 image-text-to-video 파이프라인을 지원하는 것이 특징입니다.

### 핵심 포인트
- MiniMax-H3 모델은 약 33.1B 파라미터를 보유하고 있습니다.
- image-text-to-video 태그를 사용하는 비디오 생성 모델입니다.
- 59,368회의 다운로드와 3,549개의 likes를 기록하며 트렌드에 진입했습니다.

**태그**: MiniMax-H3, image-text-to-video, Model Trending

**Metrics**: {"likes": 3549, "downloads": 59368, "num_parameters": 33122992896, "pipeline_tag": "image-text-to-video"}

### 원문 설명
likes=3549, downloads=59368, pipeline_tag=image-text-to-video

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

