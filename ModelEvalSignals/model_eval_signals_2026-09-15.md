# Model & Eval Signals (2026-09-15)

## 오늘의 요약
Hugging Face에서는 2B~35B 규모의 다양한 text-generation 모델들이 높은 관심을 받으며 트렌드를 형성하고 있으며, LiveCodeBench에서는 O4-Mini 및 Gemini 시리즈 모델들이 상위권 성적을 기록하며 코딩 성능 경쟁을 보여주었습니다.

### 오늘의 핵심 포인트
- Hugging Face 내 Edge0, XHToken, openbmb 등 다양한 규모의 text-generation 모델 트렌드 지속
- LiveCodeBench 벤치마크에서 O4-Mini 및 Gemini 시리즈 모델들의 상위권 성적 기록
- 소형(2B~4B)부터 중형(35B)까지 다양한 파라미터 규모의 모델들이 실사용 및 벤치마크에서 주목받음

**오늘의 태그**: LLM, HuggingFace, LiveCodeBench

## 1. [Edge0/Edge0-35B-A3B-preview](https://huggingface.co/Edge0/Edge0-35B-A3B-preview)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Edge0/Edge0-35B-A3B-preview 모델이 Hugging Face에서 주목받고 있습니다. 해당 모델은 text-generation 태스크를 위한 34.6B 파라미터 규모의 모델입니다.

### 핵심 포인트
- Edge0/Edge0-35B-A3B-preview 모델의 높은 관심도 확인
- 8,109회의 downloads와 1,792회의 likes 기록
- 34.6B 규모의 파라미터를 가진 text-generation 모델

**태그**: Edge0, text-generation, LLM

**Metrics**: {"likes": 1792, "downloads": 8109, "num_parameters": 34660610688, "pipeline_tag": "text-generation"}

### 원문 설명
likes=1792, downloads=8109, pipeline_tag=text-generation

---

## 2. [XHToken/Spark-X2.5-4B](https://huggingface.co/XHToken/Spark-X2.5-4B)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
XHToken/Spark-X2.5-4B 모델이 Hugging Face에서 주목받으며 높은 다운로드 수를 기록하고 있습니다. 약 4.1B 파라미터를 가진 이 모델은 text-generation 태스크를 위해 설계되었습니다.

### 핵심 포인트
- XHToken/Spark-X2.5-4B 모델의 높은 사용자 관심도 확인
- 24,084회의 다운로드와 1,170개의 likes 기록
- 약 4.1B 파라미터 규모의 text-generation 모델

**태그**: XHToken, Spark-X2.5-4B, text-generation

**Metrics**: {"likes": 1170, "downloads": 24084, "num_parameters": 4112079360, "pipeline_tag": "text-generation"}

### 원문 설명
likes=1170, downloads=24084, pipeline_tag=text-generation

---

## 3. [openbmb/MiniCPM5-2B](https://huggingface.co/openbmb/MiniCPM5-2B)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
openbmb에서 공개한 MiniCPM5-2B 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 약 2.5B 파라미터를 가진 이 모델은 text-generation 태스크를 위한 모델입니다.

### 핵심 포인트
- openbmb의 MiniCPM5-2B 모델이 높은 관심을 받고 있음
- 약 2.5B 규모의 파라미터를 보유한 text-generation 모델임
- 20만 회 이상의 downloads와 1,387개의 likes를 기록함

**태그**: MiniCPM5-2B, openbmb, text-generation

**Metrics**: {"likes": 1387, "downloads": 206774, "num_parameters": 2516756480, "pipeline_tag": "text-generation"}

### 원문 설명
likes=1387, downloads=206774, pipeline_tag=text-generation

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

