# Model & Eval Signals (2026-10-28)

## 오늘의 요약
Hugging Face의 신규 모델 트렌드와 LiveCodeBench 벤치마크 결과가 주요 흐름을 형성하였으며, 텍스트 생성 및 멀티모달 모델의 활약과 코드 생성 성능 경쟁이 관찰되었습니다.

### 오늘의 핵심 포인트
- Hugging Face에서 Nanbeige 및 XHToken의 텍스트 생성 모델이 높은 다운로드 수를 기록하며 트렌드 진입
- MiniMaxAI의 MiniMax-M3.1-Flash 모델이 멀티모달(image-text-to-text) 성능으로 주목받음
- LiveCodeBench 벤치마크에서 O4-Mini 및 Gemini 시리즈 모델들이 상위권 성적 기록

**오늘의 태그**: LLM, Multi-modal, LiveCodeBench

## 1. [Nanbeige/Nanbeige4.3-33B](https://huggingface.co/Nanbeige/Nanbeige4.3-33B)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Nanbeige/Nanbeige4.3-33B 모델이 Hugging Face에서 텍스트 생성 태그와 함께 주목받고 있습니다. 약 33B 파라미터 규모의 모델로, 최근 높은 다운로드 수를 기록하며 트렌드에 진입했습니다.

### 핵심 포인트
- Nanbeige/Nanbeige4.3-33B 모델의 Hugging Face 트렌드 진입
- 약 33B 규모의 파라미터를 가진 text-generation 모델
- 4,785회의 다운로드와 655개의 likes를 기록하며 사용자 관심을 확보

**태그**: Nanbeige, text-generation, LLM

**Metrics**: {"likes": 655, "downloads": 4785, "num_parameters": 33118977024, "pipeline_tag": "text-generation"}

### 원문 설명
likes=655, downloads=4785, pipeline_tag=text-generation

---

## 2. [XHToken/Spark-X2.6-4B](https://huggingface.co/XHToken/Spark-X2.6-4B)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
XHToken/Spark-X2.6-4B 모델이 Hugging Face에서 주목받으며 높은 다운로드 수를 기록하고 있습니다. 약 4.1B 파라미터를 가진 이 모델은 text-generation 태스크를 위해 설계되었습니다.

### 핵심 포인트
- XHToken/Spark-X2.6-4B 모델의 높은 관심도(likes 777, downloads 6191) 확인
- 약 4.1B 규모의 파라미터를 보유한 text-generation 모델
- Hugging Face 내 모델 트렌드 지표 상승

**태그**: XHToken/Spark-X2.6-4B, text-generation, LLM

**Metrics**: {"likes": 777, "downloads": 6191, "num_parameters": 4112079360, "pipeline_tag": "text-generation"}

### 원문 설명
likes=777, downloads=6191, pipeline_tag=text-generation

---

## 3. [MiniMaxAI/MiniMax-M3.1-Flash](https://huggingface.co/MiniMaxAI/MiniMax-M3.1-Flash)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
MiniMaxAI에서 출시한 MiniMax-M3.1-Flash 모델이 Hugging Face에서 주목받고 있습니다. 이 모델은 image-text-to-text 파이프라인을 지원하는 멀티모달 모델입니다.

### 핵심 포인트
- MiniMaxAI의 새로운 모델인 MiniMax-M3.1-Flash가 공개되었습니다.
- image-text-to-text 태그를 사용하는 멀티모달 모델입니다.
- 약 220B 규모의 파라미터를 보유하고 있으며, 높은 다운로드 수를 기록 중입니다.

**태그**: MiniMax-M3.1-Flash, Multi-modal, Hugging Face

**Metrics**: {"likes": 405, "downloads": 11075, "num_parameters": 220490854016, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=405, downloads=11075, pipeline_tag=image-text-to-text

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

