# Model & Eval Signals (2026-11-14)

## 오늘의 요약
Hugging Face를 중심으로 멀티모달 및 텍스트 생성 모델의 높은 관심과 함께, LiveCodeBench 벤치마크에서 Gemini 및 O4-Mini 모델들이 상위권 성적을 기록하며 코딩 성능 경쟁이 가속화되고 있습니다.

### 오늘의 핵심 포인트
- Hugging Face에서 Qwen3.8 기반 멀티모달 모델 및 DeepSeek/MiniMax 계열 모델들이 높은 다운로드 수를 기록하며 트렌드를 주도함
- LiveCodeBench 벤치마크에서 O4-Mini와 Gemini 시리즈 모델들이 상위권 성적을 기록하며 코딩 능력 입증
- 텍스트 생성, 이미지 생성, 멀티모달 등 다양한 도메인의 모델들이 동시에 주목받는 양상을 보임

**오늘의 태그**: HuggingFace, LiveCodeBench, Multimodal, LLM_Trending

## 1. [DavidAU/Qwen3.8-27B-TURBO-Fable-Cold-Fusion-735-882-Heretic-Uncensored-NEO-CODER-MAX-MTP-GGUF](https://huggingface.co/DavidAU/Qwen3.8-27B-TURBO-Fable-Cold-Fusion-735-882-Heretic-Uncensored-NEO-CODER-MAX-MTP-GGUF)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
DavidAU에서 공개한 Qwen3.8-27B 기반의 GGUF 양자화 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 이미지와 텍스트를 동시에 처리하는 멀티모달 기능을 갖추고 있습니다.

### 핵심 포인트
- Qwen3.8-27B 파라미터를 기반으로 한 GGUF 형식의 모델입니다.
- 160만 회 이상의 높은 다운로드 수를 기록하며 트렌드 모델로 부상했습니다.
- image-text-to-text 파이프라인을 지원하는 멀티모달 모델입니다.

**태그**: Qwen3.8, GGUF, Multimodal

**Metrics**: {"likes": 3033, "downloads": 1639400, "num_parameters": 26895998464, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=3033, downloads=1639400, pipeline_tag=image-text-to-text

---

## 2. [xtools-at/DeepSeek-V4-Pro-Qwen3.5-9B-UNCENSORED-heretic](https://huggingface.co/xtools-at/DeepSeek-V4-Pro-Qwen3.5-9B-UNCENSORED-heretic)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
DeepSeek-V4-Pro-Qwen3.5-9B-UNCENSORED-heretic 모델이 Hugging Face에서 높은 관심을 받고 있습니다. 약 9.4B 파라미터를 가진 이 모델은 text-generation 태그로 분류되어 있습니다.

### 핵심 포인트
- DeepSeek-V4-Pro-Qwen3.5-9B-UNCENSORED-heretic 모델의 높은 다운로드 수(21,586회)와 좋아요(5,204회) 기록
- 약 9.4B 규모의 파라미터를 보유한 text-generation 모델
- Hugging Face 내 모델 트렌드 지표 상승

**태그**: DeepSeek-V4-Pro-Qwen3.5-9B-UNCENSORED-heretic, text-generation, Hugging Face

**Metrics**: {"likes": 5204, "downloads": 21586, "num_parameters": 9409813744, "pipeline_tag": "text-generation"}

### 원문 설명
likes=5204, downloads=21586, pipeline_tag=text-generation

---

## 3. [MiniMaxAI/MiniMax-H3-Image](https://huggingface.co/MiniMaxAI/MiniMax-H3-Image)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
MiniMaxAI에서 공개한 text-to-image 모델인 MiniMax-H3-Image가 Hugging Face에서 높은 다운로드 수를 기록하며 주목받고 있습니다. 해당 모델은 텍스트를 이미지로 변환하는 파이프라인을 제공합니다.

### 핵심 포인트
- MiniMaxAI의 text-to-image 모델인 MiniMax-H3-Image가 공개됨
- 437,039회의 높은 downloads를 기록하며 모델 트렌드 형성
- 텍스트를 기반으로 이미지를 생성하는 pipeline_tag를 가짐

**태그**: MiniMax-H3-Image, text-to-image, MiniMaxAI

**Metrics**: {"likes": 987, "downloads": 437039, "num_parameters": 0, "pipeline_tag": "text-to-image"}

### 원문 설명
likes=987, downloads=437039, pipeline_tag=text-to-image

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

