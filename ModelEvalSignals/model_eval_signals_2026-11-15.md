# Model & Eval Signals (2026-11-15)

## 오늘의 요약
Hugging Face에서는 다양한 규모와 목적(TTS, Multimodal, Uncensored)을 가진 신규 모델들이 높은 다운로드 수를 기록하며 주목받았으며, LiveCodeBench에서는 O4-Mini 및 Gemini 시리즈 모델들이 상위권 성적을 기록하며 코딩 성능 경쟁을 보여주었습니다.

### 오늘의 핵심 포인트
- Zyphra의 ZONOS3-Mini(8.8억 파라미터) 등 특정 목적형 모델의 높은 관심
- Qwen 및 DeepSeek 기반의 양자화/Uncensored 모델들의 활발한 다운로드
- LiveCodeBench 벤치마크에서 O4-Mini 및 Gemini 모델들의 상위권 성적 기록

**오늘의 태그**: Hugging Face Trending, LiveCodeBench, Model Benchmarking

## 1. [Zyphra/ZONOS3-Mini](https://huggingface.co/Zyphra/ZONOS3-Mini)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Zyphra에서 공개한 ZONOS3-Mini는 약 8.8억 개의 파라미터를 가진 text-to-speech 모델입니다. 최근 높은 다운로드 수를 기록하며 주목받고 있는 모델입니다.

### 핵심 포인트
- Zyphra/ZONOS3-Mini 모델은 text-to-speech 파이프라인을 지원합니다.
- 모델의 파라미터 규모는 약 886,342,504개입니다.
- 최근 19,743회의 다운로드를 기록하며 높은 관심을 받고 있습니다.

**태그**: Zyphra, ZONOS3-Mini, text-to-speech

**Metrics**: {"likes": 337, "downloads": 19743, "num_parameters": 886342504, "pipeline_tag": "text-to-speech"}

### 원문 설명
likes=337, downloads=19743, pipeline_tag=text-to-speech

---

## 2. [DavidAU/Qwen3.8-27B-TURBO-Fable-Cold-Fusion-735-882-Heretic-Uncensored-NEO-CODER-MAX-MTP-GGUF](https://huggingface.co/DavidAU/Qwen3.8-27B-TURBO-Fable-Cold-Fusion-735-882-Heretic-Uncensored-NEO-CODER-MAX-MTP-GGUF)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
DavidAU에서 공개한 Qwen3.8-27B 기반의 GGUF 양자화 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 image-text-to-text 파이프라인을 지원하는 27B 규모의 모델입니다.

### 핵심 포인트
- Qwen3.8-27B 모델을 기반으로 한 GGUF 포맷의 모델 배포
- 1,657,783회의 다운로드와 3,109개의 likes를 기록하며 높은 관심을 받음
- image-text-to-text 파이프라인 태그를 보유한 멀티모달 성격의 모델

**태그**: Qwen3.8, GGUF, Multimodal

**Metrics**: {"likes": 3109, "downloads": 1657783, "num_parameters": 26895998464, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=3109, downloads=1657783, pipeline_tag=image-text-to-text

---

## 3. [xtools-at/DeepSeek-V4-Pro-Qwen3.5-9B-UNCENSORED-heretic](https://huggingface.co/xtools-at/DeepSeek-V4-Pro-Qwen3.5-9B-UNCENSORED-heretic)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
DeepSeek-V4-Pro-Qwen3.5-9B-UNCENSORED-heretic 모델이 Hugging Face에서 높은 관심을 받고 있습니다. 약 9.4B 파라미터를 가진 이 모델은 text-generation 태그로 분류되어 활발히 다운로드되고 있습니다.

### 핵심 포인트
- DeepSeek-V4-Pro-Qwen3.5-9B-UNCENSORED-heretic 모델의 높은 인기 확인
- likes 7,331회 및 downloads 24,470회를 기록하며 트렌드 형성
- 약 9.4B 규모의 파라미터를 가진 text-generation 모델

**태그**: DeepSeek-V4-Pro-Qwen3.5-9B-UNCENSORED-heretic, text-generation, Hugging Face

**Metrics**: {"likes": 7331, "downloads": 24470, "num_parameters": 9409813744, "pipeline_tag": "text-generation"}

### 원문 설명
likes=7331, downloads=24470, pipeline_tag=text-generation

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

