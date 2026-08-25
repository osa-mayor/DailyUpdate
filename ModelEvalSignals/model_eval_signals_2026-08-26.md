# Model & Eval Signals (2026-08-26)

## 오늘의 요약
Hugging Face에서는 Qwen 기반의 27B~35B 규모 모델들이 높은 다운로드 수를 기록하며 트렌드를 주도하고 있으며, LiveCodeBench에서는 O4-Mini 및 Gemini 시리즈 모델들이 상위권 성적을 기록하며 코딩 성능 경쟁을 보여주었습니다.

### 오늘의 핵심 포인트
- Qwen 27B 및 Ornith 35B 등 중대형 파라미터 규모 모델들의 Hugging Face 트렌드 강세
- Uncensored 및 GGUF 포맷 등 특정 목적 및 최적화 모델에 대한 높은 사용자 수요 확인
- LiveCodeBench 벤치마크에서 O4-Mini와 Gemini 모델들의 상위권 성적 기록

**오늘의 태그**: HuggingFace, LiveCodeBench, Qwen, Gemini, LLM_Trending

## 1. [OBLITERATUS/Qwen3.8-27B-OBLITERATED](https://huggingface.co/OBLITERATUS/Qwen3.8-27B-OBLITERATED)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
OBLITERATUS/Qwen3.8-27B-OBLITERATED 모델이 Hugging Face에서 높은 다운로드 수를 기록하며 주목받고 있습니다. 27B 파라미터 규모의 text-generation 모델로, 약 38만 회 이상의 다운로드를 기록하며 트렌드 상위에 올랐습니다.

### 핵심 포인트
- OBLITERATUS/Qwen3.8-27B-OBLITERATED 모델의 높은 사용자 유입 확인
- 약 389,747회의 downloads를 기록하며 활발한 배포 상태를 보임
- 27.7B 규모의 파라미터를 가진 text-generation 태그 모델임

**태그**: Qwen3.8-27B-OBLITERATED, text-generation, HuggingFace

**Metrics**: {"likes": 741, "downloads": 389747, "num_parameters": 27781427952, "pipeline_tag": "text-generation"}

### 원문 설명
likes=741, downloads=389747, pipeline_tag=text-generation

---

## 2. [orcarouter/Qwen3.8-27B-Uncensored-MLX](https://huggingface.co/orcarouter/Qwen3.8-27B-Uncensored-MLX)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Qwen3.8-27B-Uncensored-MLX 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 image-text-to-text 파이프라인을 지원하는 것이 특징입니다.

### 핵심 포인트
- 68,855회의 높은 downloads를 기록하며 트렌드 형성
- image-text-to-text 파이프라인 태그를 가진 멀티모달 성격의 모델
- 약 4.67B 규모의 파라미터를 보유

**태그**: Qwen3.8-27B-Uncensored-MLX, image-text-to-text, MLX

**Metrics**: {"likes": 1088, "downloads": 68855, "num_parameters": 4665462000, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=1088, downloads=68855, pipeline_tag=image-text-to-text

---

## 3. [ornith-ai/Ornith-1.5-35B-A3B-GGUF](https://huggingface.co/ornith-ai/Ornith-1.5-35B-A3B-GGUF)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
ornith-ai/Ornith-1.5-35B-A3B-GGUF 모델이 Hugging Face에서 높은 다운로드 수를 기록하며 주목받고 있습니다. 35B 규모의 파라미터를 가진 이 모델은 text-generation 태그로 분류된 GGUF 포맷 모델입니다.

### 핵심 포인트
- ornith-ai/Ornith-1.5-35B-A3B-GGUF 모델의 높은 사용자 관심도 확인
- 누적 다운로드 수 1,156,903회를 기록하며 활발한 배포 상태 유지
- 35B 규모의 파라미터를 가진 text-generation용 GGUF 모델

**태그**: ornith-ai, GGUF, text-generation

**Metrics**: {"likes": 290, "downloads": 1156903, "num_parameters": 35505251456, "pipeline_tag": "text-generation"}

### 원문 설명
likes=290, downloads=1156903, pipeline_tag=text-generation

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

