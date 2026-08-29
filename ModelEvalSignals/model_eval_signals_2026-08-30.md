# Model & Eval Signals (2026-08-30)

## 오늘의 요약
Hugging Face에서는 GLM-5.3 및 Hy4-preview와 같은 대규모 파라미터 기반의 신규 모델들이 주목받고 있으며, LiveCodeBench에서는 O4-Mini 및 Gemini 시리즈 모델들이 상위권 성적을 기록하며 코딩 성능 경쟁을 보여주었습니다.

### 오늘의 핵심 포인트
- GLM-5.3 및 Hy4-preview 등 700B 이상의 대규모 파라미터를 가진 모델들의 Hugging Face 트렌드 상승
- unsloth/GLM-5.3-Flash-GGUF와 같은 GGUF 포맷 모델의 높은 활용도 확인
- LiveCodeBench 벤치마크에서 O4-Mini 및 Gemini 시리즈 모델들의 상위권 랭킹 기록

**오늘의 태그**: LLM_Trending, Benchmark_Results, Large_Scale_Models

## 1. [unsloth/GLM-5.3-Flash-GGUF](https://huggingface.co/unsloth/GLM-5.3-Flash-GGUF)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
unsloth/GLM-5.3-Flash-GGUF 모델이 Hugging Face에서 높은 다운로드 수를 기록하며 주목받고 있습니다. 해당 모델은 text-generation 파이프라인을 지원하는 GGUF 포맷의 모델입니다.

### 핵심 포인트
- unsloth/GLM-5.3-Flash-GGUF 모델의 높은 사용자 관심도 확인
- 27,288회의 downloads와 266개의 likes 기록
- text-generation 작업을 위한 GGUF 포맷 모델

**태그**: GLM-5.3-Flash-GGUF, unsloth, text-generation

**Metrics**: {"likes": 266, "downloads": 27288, "num_parameters": 320759404382, "pipeline_tag": "text-generation"}

### 원문 설명
likes=266, downloads=27288, pipeline_tag=text-generation

---

## 2. [zai-org/GLM-5.3](https://huggingface.co/zai-org/GLM-5.3)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
zai-org에서 공개한 GLM-5.3 모델이 Hugging Face에서 주목받고 있습니다. 약 753B 파라미터를 가진 대규모 텍e-generation 모델입니다.

### 핵심 포인트
- zai-org에서 공개한 GLM-5.3 모델의 트렌딩 현황
- 약 753B 규모의 파라미터를 보유한 text-generation 모델
- 높은 다운로드 수(8804)와 좋아요(1253)를 기록하며 사용자 관심을 유도

**태그**: GLM-5.3, text-generation, Hugging Face

**Metrics**: {"likes": 1253, "downloads": 8804, "num_parameters": 753329940480, "pipeline_tag": "text-generation"}

### 원문 설명
likes=1253, downloads=8804, pipeline_tag=text-generation

---

## 3. [tencent/Hy4-preview](https://huggingface.co/tencent/Hy4-preview)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Tencent에서 공개한 text-generation 태그의 Hy4-preview 모델이 Hugging Face에서 주목받고 있습니다. 해당 모델은 약 780B 규모의 파라미터를 가진 대형 언어 모델로 보입니다.

### 핵심 포인트
- Tencent에서 공개한 Hy4-preview 모델의 등장
- 약 780B 규모의 파라미터를 보유한 text-generation 모델
- likes 276회, downloads 1,394회를 기록하며 트렌드 형성

**태그**: Tencent, Hy4-preview, text-generation

**Metrics**: {"likes": 276, "downloads": 1394, "num_parameters": 779960992733, "pipeline_tag": "text-generation"}

### 원문 설명
likes=276, downloads=1394, pipeline_tag=text-generation

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

