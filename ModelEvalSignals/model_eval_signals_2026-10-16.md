# Model & Eval Signals (2026-10-16)

## 오늘의 요약
Hugging Face에서는 다양한 규모와 태스크(이미지-텍스트, 텍스트 생성)를 가진 신규 모델들이 주목받고 있으며, LiveCodeBench에서는 O4-Mini 및 Gemini 시리즈 모델들이 상위권 성적을 기록하며 코딩 성능 경쟁을 보여주었습니다.

### 오늘의 핵심 포인트
- OpenBMB 및 ConwayResearch 등에서 공개한 27B~35B 규모의 신규 모델들이 Hugging Face 트렌드에 진입
- jialinyyzz/humanizer 모델이 높은 다운로드 수를 기록하며 텍스트 생성 분야에서 주목
- LiveCodeBench 벤치마크에서 O4-Mini와 Gemini 시리즈 모델들이 상위권 성적 달성

**오늘의 태그**: HuggingFace, LiveCodeBench, LLM_Trending

## 1. [openbmb/MiniCPM-V-4.7-35B-A3B](https://huggingface.co/openbmb/MiniCPM-V-4.7-35B-A3B)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
OpenBMB에서 공개한 MiniCPM-V-4.7-35B-A3B 모델이 Hugging Face에서 주목받고 있습니다. 이 모델은 35B 규모의 파라미터를 가진 image-text-to-text 태스크용 모델입니다.

### 핵심 포인트
- MiniCPM-V-4.7-35B-A3B 모델의 높은 관심도(likes 786, downloads 9278) 확인
- 35B 규모의 파라미터를 보유한 모델
- image-text-to-text 파이프라인을 지원하는 멀티모달 모델

**태그**: MiniCPM-V-4.7-35B-A3B, image-text-to-text, OpenBMB

**Metrics**: {"likes": 786, "downloads": 9278, "num_parameters": 35212875824, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=786, downloads=9278, pipeline_tag=image-text-to-text

---

## 2. [ConwayResearch/Underdog-Saluki-27B-1.0](https://huggingface.co/ConwayResearch/Underdog-Saluki-27B-1.0)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
ConwayResearch에서 공개한 Underdog-Saluki-27B-1.0 모델이 Hugging Face에서 주목받고 있습니다. 약 27B 파라미터를 가진 이 모델은 텍스트 생성(text-generation) 태그를 사용하는 모델입니다.

### 핵심 포인트
- ConwayResearch의 Underdog-Saluki-27B-1.0 모델 출시
- 약 26.9B 파라미터를 보유한 text-generation 태그 모델
- 누적 다운로드 수 344,177회를 기록하며 높은 관심을 받음

**태그**: Underdog-Saluki-27B-1.0, text-generation, HuggingFace

**Metrics**: {"likes": 496, "downloads": 344177, "num_parameters": 26895998464, "pipeline_tag": "text-generation"}

### 원문 설명
likes=496, downloads=344177, pipeline_tag=text-generation

---

## 3. [jialinyyzz/humanizer](https://huggingface.co/jialinyyzz/humanizer)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
jialinyyzz/humanizer 모델이 Hugging Face에서 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 text-generation 파이프라인을 사용하는 텍스트 생성 모델입니다.

### 핵심 포인트
- jialinyyzz/humanizer 모델의 downloads가 75,253회를 기록하며 높은 관심을 받고 있습니다.
- 모델의 파라미터 규모는 약 11.96B입니다.
- pipeline_tag는 text-generation으로 분류됩니다.

**태그**: text-generation, HuggingFace, LLM

**Metrics**: {"likes": 1720, "downloads": 75253, "num_parameters": 11959730224, "pipeline_tag": "text-generation"}

### 원문 설명
likes=1720, downloads=75253, pipeline_tag=text-generation

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

