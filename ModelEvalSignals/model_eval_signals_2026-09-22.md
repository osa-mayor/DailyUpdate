# Model & Eval Signals (2026-09-22)

## 오늘의 요약
Hugging Face에서는 Qwen 시리즈의 이미지 생성 모델과 Laya 분류 모델이 주목받았으며, LiveCodeBench에서는 O4-Mini 및 Gemini 시리즈 모델들이 상위권 성적을 기록하며 코딩 성능 경쟁을 보여주었습니다.

### 오늘의 핵심 포인트
- Qwen-Image-2.1 시리즈(GGUF 포함)가 text-to-image 파이프라인으로 높은 관심을 받음
- convaiinnovations/laya 모델이 텍스트 분류 작업에서 높은 Like 수를 기록하며 주목
- LiveCodeBench 벤치마크에서 O4-Mini 및 Gemini 모델들이 상위권 성적 달성

**오늘의 태그**: HuggingFace, LiveCodeBench, Text-to-Image, LLM-Benchmark

## 1. [abenzerps/Qwen-Image-2.1-GGUF](https://huggingface.co/abenzerps/Qwen-Image-2.1-GGUF)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Qwen-Image-2.1-GGUF 모델이 Hugging Face에서 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 text-to-image 파이프라인을 지원하는 GGUF 포맷의 모델입니다.

### 핵심 포인트
- 모델명은 abenzerps/Qwen-Image-2.1-GGUF입니다.
- 33,232회의 다운로드와 522개의 likes를 기록하며 트렌딩 중입니다.
- text-to-image 파이프라인을 지원하는 약 7.1B 파라미터 규모의 모델입니다.

**태그**: Qwen-Image-2.1-GGUF, text-to-image, GGUF

**Metrics**: {"likes": 522, "downloads": 33232, "num_parameters": 7115124736, "pipeline_tag": "text-to-image"}

### 원문 설명
likes=522, downloads=33232, pipeline_tag=text-to-image

---

## 2. [Qwen/Qwen-Image-2.1](https://huggingface.co/Qwen/Qwen-Image-2.1)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Qwen/Qwen-Image-2.1 모델이 Hugging Face에서 주목받고 있습니다. 이 모델은 text-to-image 파이프라인을 지원하는 약 7.1B 파라미터 규모의 모델입니다.

### 핵심 포인트
- Qwen/Qwen-Image-2.1 모델의 높은 관심도와 다운로드 수 기록
- text-to-image 태그를 사용하는 이미지 생성 관련 모델
- 약 7.1B(7,115,124,736) 파라미터 규모의 모델

**태그**: Qwen, text-to-image, Hugging Face

**Metrics**: {"likes": 1360, "downloads": 6523, "num_parameters": 7115124736, "pipeline_tag": "text-to-image"}

### 원문 설명
likes=1360, downloads=6523, pipeline_tag=text-to-image

---

## 3. [convaiinnovations/laya](https://huggingface.co/convaiinnovations/laya)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Hugging Face에서 1,652개의 likes를 기록하며 주목받고 있는 text-classification 모델인 convaiinnovations/laya입니다. 약 421M 파라미터를 보유한 모델로 분류 작업에 최적화되어 있습니다.

### 핵심 포인트
- convaiinnovations/laya 모델은 1,652 likes를 기록하며 트렌딩 중입니다.
- 모델의 주요 작업은 text-classification입니다.
- 모델의 파라미터 규모는 약 421,293,830개입니다.

**태그**: convaiinnovations/laya, text-classification, Hugging Face

**Metrics**: {"likes": 1652, "downloads": 0, "num_parameters": 421293830, "pipeline_tag": "text-classification"}

### 원문 설명
likes=1652, downloads=0, pipeline_tag=text-classification

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

