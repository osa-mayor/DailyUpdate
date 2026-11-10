# Model & Eval Signals (2026-11-11)

## 오늘의 요약
Hugging Face에서는 새로운 이미지 생성 및 대규모 언어 모델(LLM)의 트렌드가 두드러졌으며, LiveCodeBench에서는 다양한 모델들이 코딩 성능 벤치마크에서 상위권을 기록했습니다.

### 오늘의 핵심 포인트
- MiniMax-H3-Image 및 Ripple-65B-Preview 등 새로운 규모와 기능을 가진 모델들이 Hugging Face 트렌드 진입
- Qwen3.8 기반 GGUF 양자화 모델의 높은 다운로드 수 기록을 통한 로컬 실행 모델의 인기 확인
- LiveCodeBench 벤치마크에서 O4-Mini 및 Gemini 시리즈 모델들의 상위권 성적 기록

**오늘의 태그**: HuggingFace, LLM, LiveCodeBench

## 1. [MiniMaxAI/MiniMax-H3-Image](https://huggingface.co/MiniMaxAI/MiniMax-H3-Image)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
MiniMaxAI에서 공개한 text-to-image 모델인 MiniMax-H3-Image가 Hugging Face에서 주목받고 있습니다. 해당 모델은 텍ante-to-image 파이프라인을 지원하며 최근 다운로드와 좋아요 수가 증가하고 있습니다.

### 핵심 포인트
- MiniMaxAI에서 출시한 text-to-image 모델인 MiniMax-H3-Image가 트렌딩 모델로 등장했습니다.
- 현재 310개의 likes와 667개의 downloads를 기록하며 사용자 관심을 받고 있습니다.
- 해당 모델의 주요 기능은 text-to-image 파이프라인을 활용한 이미지 생성입니다.

**태그**: MiniMax-H3-Image, text-to-image, MiniMaxAI

**Metrics**: {"likes": 310, "downloads": 667, "num_parameters": 0, "pipeline_tag": "text-to-image"}

### 원문 설명
likes=310, downloads=667, pipeline_tag=text-to-image

---

## 2. [ricursiveAI/Ripple-65B-Preview](https://huggingface.co/ricursiveAI/Ripple-65B-Preview)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
ricursiveAI에서 공개한 Ripple-65B-Preview 모델이 Hugging Face에서 주목받고 있습니다. 약 65B 파라미터를 가진 이 모델은 최근 높은 다운로드 수를 기록하며 트렌드에 진입했습니다.

### 핵심 포인트
- ricursiveAI의 65B 규모 모델인 Ripple-65B-Preview 공개
- 6,480회의 다운로드와 479개의 likes를 기록하며 높은 관심을 받음
- 약 64.8B 파라미터를 보유한 대규모 언어 모델

**태그**: ricursiveAI, Ripple-65B-Preview, LLM

**Metrics**: {"likes": 479, "downloads": 6480, "num_parameters": 64782689360, "pipeline_tag": ""}

### 원문 설명
likes=479, downloads=6480, pipeline_tag=

---

## 3. [DavidAU/Qwen3.8-27B-TURBO-Fable-Cold-Fusion-735-882-Heretic-Uncensored-NEO-CODER-MAX-MTP-GGUF](https://huggingface.co/DavidAU/Qwen3.8-27B-TURBO-Fable-Cold-Fusion-735-882-Heretic-Uncensored-NEO-CODER-MAX-MTP-GGUF)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
DavidAU에서 공개한 Qwen3.8-27B 기반의 GGUF 양자화 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 image-text-to-text 파이프라인을 지원하는 27B 규모의 모델입니다.

### 핵심 포인트
- Qwen3.8-27B 모델을 기반으로 한 GGUF 포맷의 모델입니다.
- 약 146만 회의 다운로드와 2,831개의 좋아요를 기록하며 높은 관심을 받고 있습니다.
- image-text-to-text 파이프라인 태그를 보유하고 있습니다.

**태그**: Qwen3.8, GGUF, image-text-to-text

**Metrics**: {"likes": 2831, "downloads": 1459029, "num_parameters": 26895998464, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=2831, downloads=1459029, pipeline_tag=image-text-to-text

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

