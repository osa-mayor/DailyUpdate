# Model & Eval Signals (2026-08-11)

## 오늘의 요약
Hugging Face를 중심으로 멀티모달(Video, Text) 및 양자화 모델에 대한 높은 관심이 관찰되었으며, LiveCodeBench 벤치마크에서는 O4-Mini 및 Gemini 시리즈 모델들이 상위권 성적을 기록했습니다.

### 오늘의 핵심 포인트
- MiniMax-H3 및 Muse-Glimmer-30B 등 이미지/텍스트 기반의 멀티모달 모델이 Hugging Face에서 주목받음
- Qwen3.6 기반 GGUF 양자화 모델의 높은 다운로드 수 기록
- LiveCodeBench 벤치마크에서 O4-Mini 및 Gemini 모델 시리즈의 상위권 성적 달성

**오늘의 태그**: Multi-modal, HuggingFace, LiveCodeBench

## 1. [MiniMaxAI/MiniMax-H3](https://huggingface.co/MiniMaxAI/MiniMax-H3)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
MiniMaxAI에서 공개한 MiniMax-H3 모델이 Hugging Face에서 높은 관심을 받고 있습니다. 이 모델은 image-text-to-video 파이프라인을 지원하는 것이 특징입니다.

### 핵심 포인트
- MiniMax-H3 모델은 약 33.1B 파라미터를 보유하고 있습니다.
- image-text-to-video 태그를 가진 비디오 생성 모델입니다.
- 높은 다운로드 수(47,468)와 좋아요(3,401)를 기록하며 트렌드에 진입했습니다.

**태그**: MiniMax-H3, image-text-to-video, Model Trending

**Metrics**: {"likes": 3401, "downloads": 47468, "num_parameters": 33122992896, "pipeline_tag": "image-text-to-video"}

### 원문 설명
likes=3401, downloads=47468, pipeline_tag=image-text-to-video

---

## 2. [meta-models/Muse-Glimmer-30B](https://huggingface.co/meta-models/Muse-Glimmer-30B)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
meta-models/Muse-Glimmer-30B 모델이 Hugging Face에서 주목받고 있습니다. 이 모델은 image-text-to-text 파이프라인을 지원하는 약 30B 규모의 모델입니다.

### 핵심 포인트
- 모델명은 meta-models/Muse-Glimmer-30B이며, 약 29.7B 파라미터를 보유하고 있습니다.
- pipeline_tag는 image-text-to-text로 분류됩니다.
- 현재 593개의 likes를 기록하며 트렌딩 중입니다.

**태그**: meta-models/Muse-Glimmer-30B, image-text-to-text, LLM

**Metrics**: {"likes": 593, "downloads": 0, "num_parameters": 29776626688, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=593, downloads=0, pipeline_tag=image-text-to-text

---

## 3. [DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF](https://huggingface.co/DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
DavidAU에서 공개한 Qwen3.6-27B 기반의 GGUF 양자화 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 image-text-to-text 파이프라인을 지원하는 것이 특징입니다.

### 핵심 포인트
- Qwen3.6-27B 모델을 기반으로 제작된 GGUF 포맷의 모델입니다.
- 약 243만 회 이상의 다운로드와 1,854개의 likes를 기록하며 높은 관심을 받고 있습니다.
- pipeline_tag는 image-text-to-text로 분류됩니다.

**태그**: Qwen3.6, GGUF, image-text-to-text

**Metrics**: {"likes": 1854, "downloads": 2439083, "num_parameters": 26895998464, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=1854, downloads=2439083, pipeline_tag=image-text-to-text

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

