# Model & Eval Signals (2026-08-27)

## 오늘의 요약
Hugging Face에서는 GLM 및 Qwen 시리즈 기반의 새로운 Flash 모델들이 트렌딩되며 텍스트 및 멀티모달 성능에 대한 관심을 모았으며, LiveCodeBench에서는 O4-Mini와 Gemini 시리즈 모델들이 상위권 성적을 기록하며 코딩 성능 경쟁을 보여주었습니다.

### 오늘의 핵심 포인트
- Hugging Face 내 GLM-5.3-Flash 및 Qwen 시리즈 모델들의 높은 트렌딩 및 다운로드 기록
- Qwen3.8-Flash-Next 모델의 멀티모달(image-text-to-text) 기능 주목
- LiveCodeBench 벤치마크에서 O4-Mini 및 Gemini 시리즈 모델들의 상위권 성적 달성

**오늘의 태그**: LLM, Multimodal, LiveCodeBench

## 1. [zai-org/GLM-5.3-Flash](https://huggingface.co/zai-org/GLM-5.3-Flash)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
zai-org에서 공개한 GLM-5.3-Flash 모델이 Hugging Face에서 주목받고 있습니다. 해당 모델은 text-generation 태그를 사용하는 대규모 언어 모델입니다.

### 핵심 포인트
- zai-org에서 공개한 GLM-5.3-Flash 모델의 등장
- 692개의 likes를 기록하며 모델 트렌드에 진입
- 약 321B 파라미터를 보유한 text-generation 모델

**태그**: GLM-5.3-Flash, text-generation, LLM

**Metrics**: {"likes": 692, "downloads": 0, "num_parameters": 321323031390, "pipeline_tag": "text-generation"}

### 원문 설명
likes=692, downloads=0, pipeline_tag=text-generation

---

## 2. [Qwen/Qwen3.8-Flash-Next](https://huggingface.co/Qwen/Qwen3.8-Flash-Next)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Qwen/Qwen3.8-Flash-Next 모델이 Hugging Face에서 높은 관심을 받으며 트렌딩 모델로 등장했습니다. 이 모델은 이미지와 텍스트를 동시에 처리하는 image-text-to-text 파이프라인을 지원합니다.

### 핵심 포인트
- Qwen/Qwen3.8-Flash-Next 모델의 높은 관심도(likes 3,516회) 기록
- image-text-to-text 파이프라인을 지원하는 멀티모달 모델
- 약 180B 규모의 파라미터를 보유한 모델

**태그**: Qwen, image-text-to-text, Multimodal

**Metrics**: {"likes": 3516, "downloads": 2551, "num_parameters": 179999981459, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=3516, downloads=2551, pipeline_tag=image-text-to-text

---

## 3. [OBLITERATUS/Qwen3.8-27B-OBLITERATED](https://huggingface.co/OBLITERATUS/Qwen3.8-27B-OBLITERATED)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
OBLITERATUS/Qwen3.8-27B-OBLITERATED 모델이 Hugging Face에서 높은 다운로드 수를 기록하며 주목받고 있습니다. 27B 규모의 파라미터를 가진 이 모델은 text-generation 태스크를 위해 개발되었습니다.

### 핵심 포인트
- OBLITERATUS/Qwen3.8-27B-OBLITERATED 모델의 높은 다운로드 수(468,746회) 기록
- 약 27.7B 규모의 파라미터를 보유한 text-generation 모델
- 799개의 likes를 기록하며 모델 트렌드 형성

**태그**: Qwen3.8-27B-OBLITERATED, text-generation, HuggingFace

**Metrics**: {"likes": 799, "downloads": 468746, "num_parameters": 27781427952, "pipeline_tag": "text-generation"}

### 원문 설명
likes=799, downloads=468746, pipeline_tag=text-generation

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

