# Model & Eval Signals (2026-10-17)

## 오늘의 요약
Hugging Face에서는 멀티모달(image-text-to-text) 및 텍스트 생성 모델들이 높은 관심을 받았으며, LiveCodeBench에서는 Gemini 시리즈와 O4-Mini 등 코딩 성능이 우수한 모델들이 상위권을 기록했습니다.

### 오늘의 핵심 포인트
- OpenBMB 및 meta-models의 멀티모달 모델(image-text-to-text)이 Hugging Face에서 주목받음
- jialinyyzz/humanizer와 같은 텍스트 생성 모델의 높은 다운로드 수 기록
- LiveCodeBench 벤치마크에서 O4-Mini 및 Gemini 시리즈 모델들의 상위권 성적 달성

**오늘의 태그**: HuggingFace, Multimodal, LiveCodeBench, LLM, Text-Generation

## 1. [openbmb/MiniCPM-V-4.7-35B-A3B](https://huggingface.co/openbmb/MiniCPM-V-4.7-35B-A3B)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
OpenBMB에서 공개한 MiniCPM-V-4.7-35B-A3B 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 이미지와 텍스트를 결합하여 처리하는 image-text-to-text 파이프라인을 지원합니다.

### 핵심 포인트
- OpenBMB의 MiniCPM-V-4.7-35B-A3B 모델이 17,553회의 다운로드를 기록하며 트렌드에 진입했습니다.
- 약 35B 규모의 파라미터를 가진 모델로, image-text-to-text 태그를 보유하고 있습니다.
- 838개의 likes를 기록하며 사용자들의 관심을 받고 있습니다.

**태그**: MiniCPM-V-4.7-35B-A3B, OpenBMB, image-text-to-text

**Metrics**: {"likes": 838, "downloads": 17553, "num_parameters": 35212875824, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=838, downloads=17553, pipeline_tag=image-text-to-text

---

## 2. [meta-models/Muse-Spark-Open-816B-A42B](https://huggingface.co/meta-models/Muse-Spark-Open-816B-A42B)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
meta-models/Muse-Spark-Open-816B-A42B 모델이 Hugging Face에서 주목받고 있습니다. 이 모델은 image-text-to-text 파이프라인을 지원하는 대규모 모델입니다.

### 핵심 포인트
- 모델명은 meta-models/Muse-Spark-Open-816B-A42B이며, 약 822B 파라미터를 보유하고 있습니다.
- pipeline_tag는 image-text-to-text로 분류됩니다.
- 현재 likes 426회, downloads 815회를 기록하며 트렌드에 진입했습니다.

**태그**: meta-models/Muse-Spark-Open-816B-A42B, image-text-to-text, Hugging Face

**Metrics**: {"likes": 426, "downloads": 815, "num_parameters": 822036529664, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=426, downloads=815, pipeline_tag=image-text-to-text

---

## 3. [jialinyyzz/humanizer](https://huggingface.co/jialinyyzz/humanizer)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
jialinyyzz/humanizer 모델이 Hugging Face에서 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 text-generation 파이프라인을 사용하는 텍스트 생성 모델입니다.

### 핵심 포인트
- jialinyyzz/humanizer 모델의 downloads가 85,612회를 기록하며 높은 관심을 받고 있습니다.
- 모델의 파라미터 규모는 약 11.96B입니다.
- pipeline_tag는 text-generation으로 분류됩니다.

**태그**: text-generation, LLM, HuggingFace

**Metrics**: {"likes": 1816, "downloads": 85612, "num_parameters": 11959730224, "pipeline_tag": "text-generation"}

### 원문 설명
likes=1816, downloads=85612, pipeline_tag=text-generation

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

