# Model & Eval Signals (2026-09-09)

## 오늘의 요약
Hugging Face에서는 2B~27B 규모의 다양한 텍스트 생성 및 멀티모달 모델들이 트렌드로 주목받았으며, LiveCodeBench에서는 Gemini 및 O4-Mini 모델들이 상위권 성적을 기록하며 코딩 성능을 입증했습니다.

### 오늘의 핵심 포인트
- OpenBMB, XHToken 등 다양한 규모(2B~27B)의 신규 텍스트 생성 및 멀티모달 모델들이 Hugging Face 트렌드 진입
- LiveCodeBench 벤치마크에서 O4-Mini 및 Gemini 시리즈 모델들이 상위권 성적 기록
- GGUF 포맷 및 Uncensored 모델 등 특정 목적을 가진 파라미터 최적화 모델들의 주목

**오늘의 태그**: HuggingFace, LiveCodeBench, LLM_Trending

## 1. [openbmb/MiniCPM5-2B](https://huggingface.co/openbmb/MiniCPM5-2B)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
OpenBMB에서 공개한 2B 규모의 text-generation 모델인 MiniCPM5-2B가 Hugging Face에서 주목받고 있습니다. 약 2.5B 파라미터를 가진 이 모델은 최근 높은 다운로드 수를 기록하며 트렌드에 진입했습니다.

### 핵심 포인트
- OpenBMB의 2B 규모 text-generation 모델 출시
- 약 2.5B 파라미터를 보유한 소형 언어 모델
- 최근 2,879회의 다운로드와 612개의 likes를 기록하며 트렌드 형성

**태그**: MiniCPM5-2B, OpenBMB, text-generation

**Metrics**: {"likes": 612, "downloads": 2879, "num_parameters": 2516756480, "pipeline_tag": "text-generation"}

### 원문 설명
likes=612, downloads=2879, pipeline_tag=text-generation

---

## 2. [DavidAU/Qwen3.8-27B-TURBO-Fable-Cold-Fusion-735-882-Heretic-Uncensored-NEO-CODER-MAX-MTP-GGUF](https://huggingface.co/DavidAU/Qwen3.8-27B-TURBO-Fable-Cold-Fusion-735-882-Heretic-Uncensored-NEO-CODER-MAX-MTP-GGUF)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
DavidAU에서 공개한 Qwen3.8-27B-TURBO-Fable-Cold-Fusion-735-882-Heretic-Uncensored-NEO-CODER-MAX-MTP-GGUF 모델이 Hugging Face에서 주목받고 있습니다. 이 모델은 약 26.9B 파라미터를 가진 image-text-to-text 파이프라인 모델입니다.

### 핵심 포인트
- 모델명: DavidAU/Qwen3.8-27B-TURBO-Fable-Cold-Fusion-735-882-Heretic-Uncensored-NEO-CODER-MAX-MTP-GGUF
- 누적 다운로드 수 348,753회를 기록하며 높은 관심을 받고 있음
- 26.9B 규모의 파라미터를 가진 image-text-to-text 태그의 모델임

**태그**: Qwen3.8, GGUF, image-text-to-text

**Metrics**: {"likes": 343, "downloads": 348753, "num_parameters": 26895998464, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=343, downloads=348753, pipeline_tag=image-text-to-text

---

## 3. [XHToken/Spark-X2.5-4B](https://huggingface.co/XHToken/Spark-X2.5-4B)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
XHToken에서 공개한 Spark-X2.5-4B 모델이 Hugging Face에서 주목받고 있습니다. 약 4.1B 파라미터를 가진 이 모델은 텍스트 생성(text-generation) 태스크를 위해 설계되었습니다.

### 핵심 포인트
- XHToken의 Spark-X2.5-4B 모델이 높은 다운로드 수를 기록하며 트렌딩 중입니다.
- 모델의 파라미터 규모는 약 4.1B입니다.
- 주요 활용 분야는 text-generation 파이프라인입니다.

**태그**: XHToken, Spark-X2.5-4B, text-generation

**Metrics**: {"likes": 833, "downloads": 10661, "num_parameters": 4112079360, "pipeline_tag": "text-generation"}

### 원문 설명
likes=833, downloads=10661, pipeline_tag=text-generation

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

