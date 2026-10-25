# Model & Eval Signals (2026-10-26)

## 오늘의 요약
Hugging Face를 중심으로 멀티모달 및 텍스트 생성 모델들의 신규 출시가 활발하며, LiveCodeBench를 통해 코딩 성능 중심의 모델 벤치마크 결과가 확인되었습니다.

### 오늘의 핵심 포인트
- MiniMax-M3.1-Flash 등 멀티모달 및 텍1 생성 모델의 Hugging Face 트렌드 진입
- 40B 규모의 flint 모델 및 4B 규모의 Spark-X2.6-4B 모델 등 다양한 파라미터 규모의 모델 공개
- LiveCodeBench에서 O4-Mini 및 Gemini 시리즈 모델들의 상위권 성적 기록

**오늘의 태그**: HuggingFace, Multi-modal, LiveCodeBench

## 1. [MiniMaxAI/MiniMax-M3.1-Flash](https://huggingface.co/MiniMaxAI/MiniMax-M3.1-Flash)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
MiniMaxAI에서 출시한 MiniMax-M3.1-Flash 모델이 Hugging Face에서 주목받고 있습니다. 이 모델은 이미지와 텍스트를 동시에 처리하는 멀티모달 기능을 제공합니다.

### 핵심 포인트
- MiniMaxAI의 새로운 모델인 MiniMax-M3.1-Flash가 공개되었습니다.
- 7,355회의 다운로드와 343개의 likes를 기록하며 트렌딩 모델로 부상했습니다.
- image-text-to-text 파이프라인을 지원하는 멀티모달 모델입니다.

**태그**: MiniMax-M3.1-Flash, Multi-modal, Hugging Face

**Metrics**: {"likes": 343, "downloads": 7355, "num_parameters": 220490854016, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=343, downloads=7355, pipeline_tag=image-text-to-text

---

## 2. [RecursiveSI/flint](https://huggingface.co/RecursiveSI/flint)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
RecursiveSI에서 공개한 flint 모델이 Hugging Face에서 주목받고 있습니다. 약 40B 파라미터 규모의 text-generation 모델로, 최근 다운로드 수가 증가하며 트렌드에 진입했습니다.

### 핵심 포인트
- RecursiveSI에서 공개한 40B 규모의 text-generation 모델입니다.
- likes 839회, downloads 6,444회를 기록하며 모델 트렌드에 진입했습니다.
- num_parameters는 약 39.8B로 확인됩니다.

**태그**: RecursiveSI, flint, text-generation

**Metrics**: {"likes": 839, "downloads": 6444, "num_parameters": 39785287456, "pipeline_tag": "text-generation"}

### 원문 설명
likes=839, downloads=6444, pipeline_tag=text-generation

---

## 3. [XHToken/Spark-X2.6-4B](https://huggingface.co/XHToken/Spark-X2.6-4B)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
XHToken에서 공개한 Spark-X2.6-4B 모델이 Hugging Face에서 주목받고 있습니다. 약 4.1B 파라미터를 가진 이 모델은 text-generation 태스크를 위한 모델입니다.

### 핵심 포인트
- XHToken의 Spark-X2.6-4B 모델이 Hugging Face에서 트렌딩 중입니다.
- 모델의 파라미터 규모는 약 4.1B입니다.
- 주요 활용 분야는 text-generation입니다.

**태그**: XHToken, Spark-X2.6-4B, text-generation

**Metrics**: {"likes": 488, "downloads": 3488, "num_parameters": 4112079360, "pipeline_tag": "text-generation"}

### 원문 설명
likes=488, downloads=3488, pipeline_tag=text-generation

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

