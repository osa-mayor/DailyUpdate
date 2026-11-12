# Model & Eval Signals (2026-11-13)

## 오늘의 요약
Hugging Face에서는 새로운 텍스트 생성 및 이미지 생성 모델들이 높은 관심을 받고 있으며, LiveCodeBench에서는 Gemini 및 O4-Mini 모델들이 코딩 성능 벤치마크에서 상위권을 기록했습니다.

### 오늘의 핵심 포인트
- DeepSeek-V4-Pro 및 MiniMax-H3-Image 모델이 Hugging Face에서 높은 트렌드와 다운로드 수를 기록함
- LiveCodeBench 벤치마크에서 O4-Mini와 Gemini 시리즈 모델들이 상위 성적을 거둠
- 텍스트 생성 및 이미지 생성(text-to-image) 분야의 모델 업데이트가 활발함

**오늘의 태그**: HuggingFace, LiveCodeBench, LLM_Trending, Image_Generation

## 1. [xtools-at/DeepSeek-V4-Pro-Qwen3.5-9B-UNCENSORED-heretic](https://huggingface.co/xtools-at/DeepSeek-V4-Pro-Qwen3.5-9B-UNCENSORED-heretic)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
DeepSeek-V4-Pro-Qwen3.5-9B-UNCENSORED-heretic 모델이 Hugging Face에서 높은 관심을 받고 있습니다. 약 9.4B 파라미터를 가진 이 모델은 텍스트 생성(text-generation) 태그로 분류되어 있습니다.

### 핵심 포인트
- DeepSeek-V4-Pro-Qwen3.5-9B-UNCENSORED-heretic 모델의 높은 다운로드 수 기록
- 약 9.4B 규모의 파라미터를 보유한 text-generation 태그 모델
- 4,673개의 likes와 18,933회의 downloads를 기록하며 트렌드 형성

**태그**: DeepSeek-V4-Pro-Qwen3.5-9B-UNCENSORED-heretic, text-generation, Hugging Face

**Metrics**: {"likes": 4673, "downloads": 18933, "num_parameters": 9409813744, "pipeline_tag": "text-generation"}

### 원문 설명
likes=4673, downloads=18933, pipeline_tag=text-generation

---

## 2. [MiniMaxAI/MiniMax-H3-Image](https://huggingface.co/MiniMaxAI/MiniMax-H3-Image)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
MiniMaxAI에서 공개한 MiniMax-H3-Image 모델이 Hugging Face에서 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 text-to-image 파이프라인을 지원하는 이미지 생성 모델입니다.

### 핵심 포인트
- MiniMaxAI의 text-to-image 모델인 MiniMax-H3-Image가 공개되었습니다.
- 30만 회 이상의 높은 다운로드 수를 기록하며 모델 트렌드를 형성하고 있습니다.
- 842개의 likes를 기록하며 사용자들의 관심을 받고 있습니다.

**태그**: MiniMax-H3-Image, text-to-image, MiniMaxAI

**Metrics**: {"likes": 842, "downloads": 306718, "num_parameters": 0, "pipeline_tag": "text-to-image"}

### 원문 설명
likes=842, downloads=306718, pipeline_tag=text-to-image

---

## 3. [Comfy-Org/MiniMax-H3-Image](https://huggingface.co/Comfy-Org/MiniMax-H3-Image)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Comfy-Org에서 공개한 MiniMax-H3-Image 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 text-to-image 파이프라인을 지원하는 모델입니다.

### 핵심 포인트
- Comfy-Org에서 배포한 MiniMax-H3-Image 모델의 트렌드 확인
- 835,593회의 높은 다운로드 수를 기록하며 사용자 관심을 받음
- text-to-image 파이프라인을 활용하는 모델임

**태그**: MiniMax-H3-Image, text-to-image, Comfy-Org

**Metrics**: {"likes": 285, "downloads": 835593, "num_parameters": 0, "pipeline_tag": "text-to-image"}

### 원문 설명
likes=285, downloads=835593, pipeline_tag=text-to-image

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

