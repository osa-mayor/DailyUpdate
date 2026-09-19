# Model & Eval Signals (2026-09-20)

## 오늘의 요약
Hugging Face에서는 텍스트 분류 및 생성 목적의 다양한 규모(400M~31B) 모델들이 주목받고 있으며, LiveCodeBench에서는 O4-Mini 및 Gemini 시리즈 모델들이 상위권 성적을 기록하며 코딩 성능 경쟁을 보여주었습니다.

### 오늘의 핵심 포인트
- Hugging Face 내 텍스트 생성 및 분류 모델(Laya, Xing4.0, Ternary-Bonsai)의 트렌드 지속
- GGUF 양자화 모델(Ternary-Bonsai-2-27B)의 높은 활용도 확인
- LiveCodeBench 벤치마크에서 O4-Mini 및 Gemini 모델들의 상위권 성적 기록

**오늘의 태그**: HuggingFace, LiveCodeBench, LLM_Trending

## 1. [convaiinnovations/laya](https://huggingface.co/convaiinnovations/laya)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Hugging Face에서 text-classification 태그를 가진 convaiinnovations/laya 모델이 주목받고 있습니다. 해당 모델은 약 4.2억 개의 파라미터를 보유하고 있습니다.

### 핵심 포인트
- convaiinnovations/laya 모델의 likes가 451을 기록하며 트렌딩 중입니다.
- 모델의 주요 작업은 text-classification입니다.
- 모델의 파라미터 규모는 421,293,830개입니다.

**태그**: text-classification, convaiinnovations/laya, Hugging Face

**Metrics**: {"likes": 451, "downloads": 0, "num_parameters": 421293830, "pipeline_tag": "text-classification"}

### 원문 설명
likes=451, downloads=0, pipeline_tag=text-classification

---

## 2. [XingChen-AGI/Xing4.0-29B-A4B](https://huggingface.co/XingChen-AGI/Xing4.0-29B-A4B)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
XingChen-AGI에서 공개한 Xing4.0-29B-A4B 모델이 Hugging Face에서 주목받고 있습니다. 약 31B 파라미터를 가진 이 모델은 text-generation 태그로 분류되어 있습니다.

### 핵심 포인트
- XingChen-AGI의 Xing4.0-29B-A4B 모델이 Hugging Face에서 트렌딩 중입니다.
- 해당 모델은 약 31.2B의 파라미터를 보유한 text-generation 모델입니다.
- 현재 7,278회의 downloads와 616회의 likes를 기록하고 있습니다.

**태그**: Xing4.0-29B-A4B, text-generation, HuggingFace

**Metrics**: {"likes": 616, "downloads": 7278, "num_parameters": 31215031088, "pipeline_tag": "text-generation"}

### 원문 설명
likes=616, downloads=7278, pipeline_tag=text-generation

---

## 3. [prism-ml/Ternary-Bonsai-2-27B-gguf](https://huggingface.co/prism-ml/Ternary-Bonsai-2-27B-gguf)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
prism-ml에서 공개한 27B 규모의 GGUF 양자화 모델인 Ternary-Bonsai-2-27B-gguf가 높은 다운로드 수를 기록하며 주목받고 있습니다. 텍스트 생성(text-generation) 파이프라인을 지원하며 약 26.9B 파라미터를 보유하고 있습니다.

### 핵심 포인트
- prism-ml의 27B 규모 모델인 Ternary-Bonsai-2-27B-gguf 공개
- 1,516,960회의 높은 다운로드 수를 기록하며 모델 트렌드 형성
- text-generation 파이프라인을 지원하는 GGUF 포맷 모델

**태그**: Ternary-Bonsai-2-27B-gguf, GGUF, text-generation

**Metrics**: {"likes": 1157, "downloads": 1516960, "num_parameters": 26895998464, "pipeline_tag": "text-generation"}

### 원문 설명
likes=1157, downloads=1516960, pipeline_tag=text-generation

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

