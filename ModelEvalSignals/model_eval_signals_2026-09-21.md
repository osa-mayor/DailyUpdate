# Model & Eval Signals (2026-09-21)

## 오늘의 요약
Hugging Face의 신규 모델 트렌드와 LiveCodeBench의 벤치마크 결과가 주요 흐름을 형성하였으며, 텍스트 생성부터 이미지 생성, 분류에 이르기까지 다양한 규모의 모델들이 주목받았습니다.

### 오늘의 핵심 포인트
- Hugging Face에서 Qwen-Image-2.1(7.1B), Xing4.0-29B-A4B(31B) 등 다양한 파라미터 규모의 모델들이 트렌드로 부상함
- convaiinnovations/laya 모델이 974개의 likes를 기록하며 텍스트 분류 작업에서 주목받음
- LiveCodeBench 벤치마크에서 O4-Mini, Gemini-2.5-Pro, Gemini-2.5-Flash 등 상위 모델들의 성능 결과가 업데이트됨

**오늘의 태그**: HuggingFace, LiveCodeBench, LLM_Trending

## 1. [Qwen/Qwen-Image-2.1](https://huggingface.co/Qwen/Qwen-Image-2.1)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Qwen/Qwen-Image-2.1 모델이 Hugging Face에서 text-to-image 태그와 함께 주목받고 있습니다. 해당 모델은 약 7.1B 파라미터를 보유하고 있습니다.

### 핵심 포인트
- Qwen/Qwen-Image-2.1 모델의 Hugging Face 트렌딩 기록
- text-to-image 파이프라인을 지원하는 약 7.1B 규모의 모델
- 579개의 likes와 183개의 downloads를 기록 중

**태그**: Qwen-Image-2.1, text-to-image, Hugging Face

**Metrics**: {"likes": 579, "downloads": 183, "num_parameters": 7115124736, "pipeline_tag": "text-to-image"}

### 원문 설명
likes=579, downloads=183, pipeline_tag=text-to-image

---

## 2. [convaiinnovations/laya](https://huggingface.co/convaiinnovations/laya)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Hugging Face에서 974개의 likes를 기록하며 주목받고 있는 text-classification 모델인 convaiinnovations/laya입니다. 약 4.2억 개의 파라미터를 보유한 모델로 분류 작업에 최적화되어 있습니다.

### 핵심 포인트
- convaiinnovations/laya 모델은 974개의 likes를 기록하며 트렌딩 중입니다.
- 모델의 파라미터 규모는 약 421,293,830개입니다.
- 주요 작업은 text-classification 태그로 분류됩니다.

**태그**: convaiinnovations/laya, text-classification, Hugging Face

**Metrics**: {"likes": 974, "downloads": 0, "num_parameters": 421293830, "pipeline_tag": "text-classification"}

### 원문 설명
likes=974, downloads=0, pipeline_tag=text-classification

---

## 3. [XingChen-AGI/Xing4.0-29B-A4B](https://huggingface.co/XingChen-AGI/Xing4.0-29B-A4B)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
XingChen-AGI에서 공개한 Xing4.0-29B-A4B 모델이 Hugging Face에서 주목받고 있습니다. 약 31B 파라미터를 가진 이 모델은 text-generation 태그로 분류되어 있습니다.

### 핵심 포인트
- Xing4.0-29B-A4B 모델은 약 31.2B의 파라미터를 보유하고 있습니다.
- Hugging Face에서 12,617회의 다운로드와 842개의 likes를 기록하며 트렌딩 중입니다.
- 해당 모델의 주요 작업은 text-generation입니다.

**태그**: Xing4.0-29B-A4B, text-generation, LLM

**Metrics**: {"likes": 842, "downloads": 12617, "num_parameters": 31215031088, "pipeline_tag": "text-generation"}

### 원문 설명
likes=842, downloads=12617, pipeline_tag=text-generation

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

