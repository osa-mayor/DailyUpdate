# Model & Eval Signals (2026-08-24)

## 오늘의 요약
Hugging Face의 신규 모델(Qwen 27B 계열 및 Ornith-1.5)이 높은 다운로드와 관심을 받으며 주목받고 있으며, LiveCodeBench 벤치마크에서는 O4-Mini와 Gemini 시리즈 모델들이 상위권 성적을 기록했습니다.

### 오늘의 핵심 포인트
- Qwen 27B 기반의 다양한 파생 모델(OBLITERATED, Uncensored-MLX)이 높은 다운로드 수를 기록하며 트렌드로 부상
- ornith-ai의 Ornith-1.5-35B-A3B 모델이 활발한 사용자 피드백(Likes)과 함께 주목받음
- LiveCodeBench 벤치마크에서 O4-Mini 및 Gemini 시리즈 모델들이 상위권 성적을 기록하며 코딩 성능 입증

**오늘의 태그**: LLM, HuggingFace, LiveCodeBench, Qwen, Gemini

## 1. [OBLITERATUS/Qwen3.8-27B-OBLITERATED](https://huggingface.co/OBLITERATUS/Qwen3.8-27B-OBLITERATED)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
OBLITERATUS/Qwen3.8-27B-OBLITERATED 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 27B 규모의 파라미터를 가진 text-generation 태그의 모델입니다.

### 핵심 포인트
- OBLITERATUS/Qwen3.8-27B-OBLITERATED 모델의 높은 사용자 유입 확인
- 244,834회의 downloads와 611개의 likes 기록
- 27.7B 규모의 파라미터를 보유한 text-generation 모델

**태그**: Qwen3.8-27B-OBLITERATED, text-generation, LLM

**Metrics**: {"likes": 611, "downloads": 244834, "num_parameters": 27781427952, "pipeline_tag": "text-generation"}

### 원문 설명
likes=611, downloads=244834, pipeline_tag=text-generation

---

## 2. [orcarouter/Qwen3.8-27B-Uncensored-MLX](https://huggingface.co/orcarouter/Qwen3.8-27B-Uncensored-MLX)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
orcarouter/Qwen3.8-27B-Uncensored-MLX 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 image-text-to-text 파이프라인을 지원하는 것이 특징입니다.

### 핵심 포인트
- orcarouter/Qwen3.8-27B-Uncensored-MLX 모델의 downloads가 47,098회를 기록하며 트렌딩되었습니다.
- 해당 모델은 image-text-to-text 파이프라인 태그를 보유하고 있습니다.
- 모델의 파라미터 규모는 약 4.67B 수준입니다.

**태그**: Qwen3.8-27B-Uncensored-MLX, image-text-to-text, MLX

**Metrics**: {"likes": 942, "downloads": 47098, "num_parameters": 4665462000, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=942, downloads=47098, pipeline_tag=image-text-to-text

---

## 3. [ornith-ai/Ornith-1.5-35B-A3B](https://huggingface.co/ornith-ai/Ornith-1.5-35B-A3B)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
ornith-ai에서 공개한 35B 규모의 text-generation 모델인 Ornith-1.5-35B-A3B가 Hugging Face에서 주목받고 있습니다. 약 23,516회의 다운로드와 358개의 likes를 기록하며 활발한 사용세를 보이고 있습니다.

### 핵심 포인트
- ornith-ai에서 출시한 35B 파라미터 규모의 text-generation 모델입니다.
- 23,516회의 다운로드와 358개의 likes를 기록하며 트렌딩 중입니다.
- 모델의 주요 용도는 text-generation 파이프라인입니다.

**태그**: ornith-ai, text-generation, LLM

**Metrics**: {"likes": 358, "downloads": 23516, "num_parameters": 35951822704, "pipeline_tag": "text-generation"}

### 원문 설명
likes=358, downloads=23516, pipeline_tag=text-generation

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

