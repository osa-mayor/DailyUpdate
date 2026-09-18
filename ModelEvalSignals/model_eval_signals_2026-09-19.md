# Model & Eval Signals (2026-09-19)

## 오늘의 요약
Hugging Face에서는 27B~35B 규모의 GGUF 양자화 모델들이 높은 다운로드 수를 기록하며 트렌드를 형성하고 있으며, LiveCodeBench에서는 O4-Mini 및 Gemini 시리즈 모델들이 상위권 성적을 기록하며 코딩 성능 경쟁을 보여주었습니다.

### 오늘의 핵심 포인트
- 27B~35B 규모의 중형 모델 및 GGUF 포맷 모델들의 높은 사용자 관심도 확인
- Qwen3.8 기반의 멀티모달(image-text-to-text) 지원 모델 등 특화 기능 모델 주목
- LiveCodeBench 벤치마크에서 O4-Mini 및 Gemini 모델들의 상위권 성적 기록

**오늘의 태그**: LLM_Trending, GGUF, LiveCodeBench

## 1. [prism-ml/Ternary-Bonsai-2-27B-gguf](https://huggingface.co/prism-ml/Ternary-Bonsai-2-27B-gguf)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
prism-ml에서 공개한 27B 규모의 text-generation 모델인 Ternary-Bonsai-2-27B-gguf가 높은 다운로드 수를 기록하며 주목받고 있습니다. 해당 모델은 GGUF 포맷으로 제공되어 다양한 환경에서의 활용이 가능할 것으로 보입니다.

### 핵심 포인트
- prism-ml의 27B 파라미터 규모 모델인 Ternary-Bonsai-2-27B-gguf 공개
- 40만 회 이상의 높은 downloads 기록
- text-generation 태그를 가진 GGUF 포맷 모델

**태그**: Ternary-Bonsai-2-27B-gguf, text-generation, GGUF

**Metrics**: {"likes": 847, "downloads": 405609, "num_parameters": 26895998464, "pipeline_tag": "text-generation"}

### 원문 설명
likes=847, downloads=405609, pipeline_tag=text-generation

---

## 2. [Edge0/Edge0-35B-A3B-preview](https://huggingface.co/Edge0/Edge0-35B-A3B-preview)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Edge0/Edge0-35B-A3B-preview 모델이 Hugging Face에서 높은 관심을 받으며 트렌딩 중입니다. 약 34.7B 파라미터를 가진 이 모델은 텍스트 생성 작업을 위해 설계되었습니다.

### 핵심 포인트
- Edge0/Edge0-35B-A3B-preview 모델의 높은 다운로드 수(52,519회)와 좋아요(3,386회) 기록
- 약 34.7B 규모의 파라미터를 보유한 text-generation 태그 모델
- 최근 Hugging Face 내 모델 트렌드 반영

**태그**: Edge0, text-generation, LLM

**Metrics**: {"likes": 3386, "downloads": 52519, "num_parameters": 34660610688, "pipeline_tag": "text-generation"}

### 원문 설명
likes=3386, downloads=52519, pipeline_tag=text-generation

---

## 3. [DavidAU/Qwen3.8-27B-TURBO-Fable-Cold-Fusion-735-882-Heretic-Uncensored-NEO-CODER-MAX-MTP-GGUF](https://huggingface.co/DavidAU/Qwen3.8-27B-TURBO-Fable-Cold-Fusion-735-882-Heretic-Uncensored-NEO-CODER-MAX-MTP-GGUF)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
DavidAU에서 공개한 Qwen3.8-27B 기반의 GGUF 양자화 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 image-text-to-text 파이프라인을 지원하는 것이 특징입니다.

### 핵심 포인트
- Qwen3.8-27B 모델을 기반으로 제작된 GGUF 포맷의 모델입니다.
- 약 119만 회 이상의 다운로드와 887개의 likes를 기록하며 높은 관심을 받고 있습니다.
- pipeline_tag는 image-text-to-text로 분류됩니다.

**태그**: Qwen3.8, GGUF, image-text-to-text

**Metrics**: {"likes": 887, "downloads": 1197378, "num_parameters": 26895998464, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=887, downloads=1197378, pipeline_tag=image-text-to-text

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

