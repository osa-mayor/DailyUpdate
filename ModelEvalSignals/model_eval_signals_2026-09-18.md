# Model & Eval Signals (2026-09-18)

## 오늘의 요약
Hugging Face에서는 27B~35B 규모의 멀티모달 및 텍스트 생성 모델들이 트렌딩을 주도하고 있으며, LiveCodeBench에서는 O4-Mini와 Gemini 시리즈 모델들이 상위권 성적을 기록하며 코딩 성능 경쟁을 보여주었습니다.

### 오늘의 핵심 포인트
- Hugging Face 내 27B~35B 규모의 중형 모델(Edge0, Qwen3.8 기반 등) 및 멀티모달 기능 모델의 높은 관심
- LiveCodeBench 벤치마크에서 O4-Mini 및 Gemini 시리즈 모델들의 상위권 성적 기록
- GGUF 양자화 및 이미지-텍스트 결합 모델 등 특정 활용 목적을 가진 모델들의 트렌딩

**오늘의 태그**: HuggingFace, LiveCodeBench, Multimodal, LLM_Trending

## 1. [Edge0/Edge0-35B-A3B-preview](https://huggingface.co/Edge0/Edge0-35B-A3B-preview)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Edge0/Edge0-35B-A3B-preview 모델이 Hugging Face에서 높은 관심을 받으며 트렌딩 중입니다. 약 34.7B 파라미터를 보유한 text-generation 태그의 모델입니다.

### 핵심 포인트
- Edge0/Edge0-35B-A3B-preview 모델의 높은 다운로드 수(37,131회)와 좋아요(3,290회) 기록
- 약 34.66B 파라미터를 가진 text-generation 태그 모델
- Hugging Face 내 모델 트렌딩 지표 확인

**태그**: Edge0, text-generation, HuggingFace

**Metrics**: {"likes": 3290, "downloads": 37131, "num_parameters": 34660610688, "pipeline_tag": "text-generation"}

### 원문 설명
likes=3290, downloads=37131, pipeline_tag=text-generation

---

## 2. [DavidAU/Qwen3.8-27B-TURBO-Fable-Cold-Fusion-735-882-Heretic-Uncensored-NEO-CODER-MAX-MTP-GGUF](https://huggingface.co/DavidAU/Qwen3.8-27B-TURBO-Fable-Cold-Fusion-735-882-Heretic-Uncensored-NEO-CODER-MAX-MTP-GGUF)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
DavidAU에서 공개한 Qwen3.8-27B 기반의 GGUF 양자화 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 이미지와 텍스트를 동시에 처리하는 멀티모달 기능을 갖춘 것이 특징입니다.

### 핵심 포인트
- Qwen3.8-27B 모델을 기반으로 제작된 GGUF 포맷의 모델입니다.
- 1,116,038회의 다운로드와 839개의 likes를 기록하며 높은 관심을 받고 있습니다.
- pipeline_tag는 image-text-to-text로, 멀티모달 작업에 최적화되어 있습니다.

**태그**: Qwen3.8, GGUF, Multimodal

**Metrics**: {"likes": 839, "downloads": 1116038, "num_parameters": 26895998464, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=839, downloads=1116038, pipeline_tag=image-text-to-text

---

## 3. [ukisai/Swift-Qwen3.8-27b](https://huggingface.co/ukisai/Swift-Qwen3.8-27b)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
ukisai/Swift-Qwen3.8-27b 모델이 Hugging Face에서 주목받고 있습니다. 이 모델은 27B 규모의 파라미터를 가진 image-text-to-text 태스크용 모델입니다.

### 핵심 포인트
- ukisai/Swift-Qwen3.8-27b 모델의 likes는 372, downloads는 3221을 기록했습니다.
- 모델의 파라미터 규모는 약 27.7B입니다.
- pipeline_tag는 image-text-to-text로 분류됩니다.

**태그**: Swift-Qwen3.8-27b, image-text-to-text, Hugging Face

**Metrics**: {"likes": 372, "downloads": 3221, "num_parameters": 27781427952, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=372, downloads=3221, pipeline_tag=image-text-to-text

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

