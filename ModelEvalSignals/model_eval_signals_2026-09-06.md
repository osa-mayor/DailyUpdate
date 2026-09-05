# Model & Eval Signals (2026-09-06)

## 오늘의 요약
Hugging Face에서 새로운 대규모 언어 모델(GLM-5.3, Spark-X2.5)의 배포로 인한 높은 다운로드 트렌드가 관찰되었으며, LiveCodeBench 벤치마크에서는 O4-Mini 및 Gemini 시리즈 모델들이 상위권 성적을 기록하며 코딩 성능 경쟁이 지속되고 있습니다.

### 오늘의 핵심 포인트
- zai-org의 GLM-5.3(753B) 및 GLM-5.3-Flash(멀티모달) 모델이 높은 다운로드 수를 기록하며 트렌드 진입
- XHToken/Spark-X2.5-4B 모델이 텍스트 생성 태스크로 주목받으며 배포됨
- LiveCodeBench 벤치마크에서 O4-Mini 및 Gemini-2.5 시리즈 모델들이 상위권 성적 달성

**오늘의 태그**: LLM_Trending, Multimodal, LiveCodeBench

## 1. [zai-org/GLM-5.3-Flash](https://huggingface.co/zai-org/GLM-5.3-Flash)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
zai-org에서 공개한 GLM-5.3-Flash 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 image-text-to-text 태스크를 지원하는 멀티모달 모델입니다.

### 핵심 포인트
- zai-org에서 공개한 GLM-5.3-Flash 모델의 트렌딩
- 727,610회의 높은 다운로드 수 기록
- image-text-to-text 파이프라인을 지원하는 모델

**태그**: GLM-5.3-Flash, image-text-to-text, HuggingFace

**Metrics**: {"likes": 2077, "downloads": 727610, "num_parameters": 321323031390, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=2077, downloads=727610, pipeline_tag=image-text-to-text

---

## 2. [zai-org/GLM-5.3](https://huggingface.co/zai-org/GLM-5.3)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
zai-org에서 공개한 GLM-5.3 모델이 Hugging Face에서 높은 다운로드 수를 기록하며 주목받고 있습니다. 약 753B 파라미터를 보유한 대규모 text-generation 모델입니다.

### 핵심 포인트
- zai-org에서 공개한 GLM-5.3 모델의 트렌딩 현황
- 370,417회의 높은 다운로드 수와 1,716개의 likes 기록
- 약 753B 규모의 파라미터를 가진 text-generation 모델

**태그**: GLM-5.3, text-generation, HuggingFace

**Metrics**: {"likes": 1716, "downloads": 370417, "num_parameters": 753329940480, "pipeline_tag": "text-generation"}

### 원문 설명
likes=1716, downloads=370417, pipeline_tag=text-generation

---

## 3. [XHToken/Spark-X2.5-4B](https://huggingface.co/XHToken/Spark-X2.5-4B)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
XHToken/Spark-X2.5-4B 모델이 Hugging Face에서 주목받으며 텍스트 생성 태그로 배포되었습니다. 약 4.1B 파라미터를 가진 이 모델은 최근 높은 다운로드 수를 기록하며 트렌드에 진입했습니다.

### 핵심 포인트
- XHToken/Spark-X2.5-4B 모델의 Hugging Face 트렌드 진입
- 약 4.1B 파라미터 규모의 text-generation 모델
- 4,755회의 다운로드와 528개의 likes 기록

**태그**: XHToken/Spark-X2.5-4B, text-generation, LLM

**Metrics**: {"likes": 528, "downloads": 4755, "num_parameters": 4112079360, "pipeline_tag": "text-generation"}

### 원문 설명
likes=528, downloads=4755, pipeline_tag=text-generation

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

