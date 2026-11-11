# Model & Eval Signals (2026-11-12)

## 오늘의 요약
Hugging Face를 중심으로 다양한 규모와 목적(이미지 생성, 양자화, 대형 언어 모델)을 가진 모델들이 트렌드를 주도하고 있으며, LiveCodeBench에서는 Gemini 및 O4-Mini 모델들이 상위권 성적을 기록하며 코딩 성능 경쟁을 보여주었습니다.

### 오늘의 핵심 포인트
- Hugging Face에서 이미지 생성(MiniMax-H3-Image) 및 양자화(Qwen3.8-27B GGUF) 모델이 높은 관심을 받음
- 65B 규모의 대형 모델(Ripple-65B-Preview)이 트렌드에 진입하며 성능 주목
- LiveCodeBench 벤치마크에서 Gemini 시리즈와 O4-Mini 모델이 상위권 성적 기록

**오늘의 태그**: HuggingFace, LLM_Trending, LiveCodeBench

## 1. [MiniMaxAI/MiniMax-H3-Image](https://huggingface.co/MiniMaxAI/MiniMax-H3-Image)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
MiniMaxAI에서 공개한 MiniMax-H3-Image 모델이 Hugging Face에서 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 text-to-image 파이프라인을 지원하는 이미지 생성 모델입니다.

### 핵심 포인트
- MiniMax-H3-Image 모델의 높은 사용자 유입 확인
- 14만 건 이상의 높은 다운로드 수 기록
- text-to-image 태그를 사용하는 이미지 생성 모델

**태그**: MiniMax-H3-Image, text-to-image, Hugging Face

**Metrics**: {"likes": 667, "downloads": 142989, "num_parameters": 0, "pipeline_tag": "text-to-image"}

### 원문 설명
likes=667, downloads=142989, pipeline_tag=text-to-image

---

## 2. [DavidAU/Qwen3.8-27B-TURBO-Fable-Cold-Fusion-735-882-Heretic-Uncensored-NEO-CODER-MAX-MTP-GGUF](https://huggingface.co/DavidAU/Qwen3.8-27B-TURBO-Fable-Cold-Fusion-735-882-Heretic-Uncensored-NEO-CODER-MAX-MTP-GGUF)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
DavidAU에서 공개한 Qwen3.8-27B 기반의 GGUF 양자화 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 image-text-to-text 파이프라인을 지원하는 27B 규모의 모델입니다.

### 핵심 포인트
- Qwen3.8-27B 모델을 기반으로 한 GGUF 포맷의 모델입니다.
- 150만 회 이상의 높은 다운로드 수를 기록하며 트렌드에 진입했습니다.
- image-text-to-text 파이프라인 태그를 보유하고 있습니다.

**태그**: Qwen3.8, GGUF, image-text-to-text

**Metrics**: {"likes": 2894, "downloads": 1532273, "num_parameters": 26895998464, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=2894, downloads=1532273, pipeline_tag=image-text-to-text

---

## 3. [ricursiveAI/Ripple-65B-Preview](https://huggingface.co/ricursiveAI/Ripple-65B-Preview)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
ricursiveAI에서 공개한 Ripple-65B-Preview 모델이 Hugging Face에서 주목받고 있습니다. 약 65B 파라미터를 가진 이 모델은 최근 높은 다운로드 수를 기록하며 트렌드에 진입했습니다.

### 핵심 포인트
- ricursiveAI의 65B 규모 모델인 Ripple-65B-Preview 공개
- 7,112회의 downloads와 509개의 likes를 기록하며 높은 관심을 받음
- 약 64.78B 파라미터를 보유한 대규모 언어 모델

**태그**: ricursiveAI, Ripple-65B-Preview, LLM

**Metrics**: {"likes": 509, "downloads": 7112, "num_parameters": 64782689360, "pipeline_tag": ""}

### 원문 설명
likes=509, downloads=7112, pipeline_tag=

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

