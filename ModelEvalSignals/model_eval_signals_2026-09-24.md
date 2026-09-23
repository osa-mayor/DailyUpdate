# Model & Eval Signals (2026-09-24)

## 오늘의 요약
Hugging Face의 신규 모델 트렌드와 LiveCodeBench 벤치마크 결과가 주요 흐름을 형성하였으며, 텍스트 분류 및 이미지 생성 모델의 주목과 코드 생성 성능 측정 결과가 확인되었습니다.

### 오늘의 핵심 포인트
- Hugging Face에서 text-classification 및 text-to-image(GGUF) 관련 모델들이 높은 관심을 받음
- LiveCodeBench 벤치마크에서 O4-Mini, Gemini 시리즈 등 상위 모델들의 성능 지표 기록
- 특정 파라미터 규모 및 포맷(GGUF)을 가진 모델들의 실질적인 활용도 증가

**오늘의 태그**: HuggingFace, LiveCodeBench, LLM_Benchmark

## 1. [AlexWortega/openjev](https://huggingface.co/AlexWortega/openjev)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
AlexWortega/openjev 모델이 Hugging Face에서 주목받고 있습니다. 이 모델은 text-classification 태스크를 위한 모델입니다.

### 핵심 포인트
- AlexWortega/openjev 모델의 likes가 511를 기록하며 트렌딩 중입니다.
- 해당 모델의 pipeline_tag는 text-classification입니다.
- 현재 downloads는 0으로 기록되어 있습니다.

**태그**: text-classification, Hugging Face, Model Trending

**Metrics**: {"likes": 511, "downloads": 0, "num_parameters": 0, "pipeline_tag": "text-classification"}

### 원문 설명
likes=511, downloads=0, pipeline_tag=text-classification

---

## 2. [convaiinnovations/laya](https://huggingface.co/convaiinnovations/laya)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
convaiinnovations/laya 모델이 Hugging Face에서 주목받고 있습니다. 이 모델은 text-classification 태스크를 수행하며 약 421M 파라미터를 보유하고 있습니다.

### 핵심 포인트
- convaiinnovations/laya 모델의 likes가 3034를 기록하며 트렌딩 중입니다.
- 해당 모델의 pipeline_tag는 text-classification입니다.
- 모델의 파라미터 규모는 421,293,830개입니다.

**태그**: text-classification, NLP, HuggingFace

**Metrics**: {"likes": 3034, "downloads": 0, "num_parameters": 421293830, "pipeline_tag": "text-classification"}

### 원문 설명
likes=3034, downloads=0, pipeline_tag=text-classification

---

## 3. [abenzerps/Qwen-Image-2.1-Uncensored-GGUF](https://huggingface.co/abenzerps/Qwen-Image-2.1-Uncensored-GGUF)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
abenzerps/Qwen-Image-2.1-Uncensored-GGUF 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 text-to-image 파이프라인을 지원하는 GGUF 포맷의 모델입니다.

### 핵심 포인트
- 350,678회의 높은 downloads를 기록하며 트렌드에 진입함
- text-to-image 파이프라인 태그를 가진 모델임
- 약 7.1B 규모의 파라미터를 보유함

**태그**: Qwen-Image-2.1-Uncensored-GGUF, text-to-image, GGUF

**Metrics**: {"likes": 1407, "downloads": 350678, "num_parameters": 7115124736, "pipeline_tag": "text-to-image"}

### 원문 설명
likes=1407, downloads=350678, pipeline_tag=text-to-image

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

