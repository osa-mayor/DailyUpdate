# Model & Eval Signals (2026-09-14)

## 오늘의 요약
Hugging Face에서는 다양한 규모의 텍스트 생성 및 오디오 생성 모델들이 높은 다운로드 수를 기록하며 트렌드를 형성하고 있으며, LiveCodeBench에서는 Gemini 및 O4-Mini 모델들이 상위권 성적을 기록하며 코딩 성능 경쟁을 보여주었습니다.

### 오늘의 핵심 포인트
- OpenBMB, m-a-p, nex-agi 등 다양한 규모(2B~397B)의 모델들이 Hugging Face에서 높은 관심을 받으며 트렌드 진입
- text-generation 및 text-to-audio 등 특정 태스크 중심의 모델 활용도 증가
- LiveCodeBench 벤치마크에서 Gemini 시리즈와 O4-Mini 모델이 상위권 성적 기록

**오늘의 태그**: LLM, HuggingFace, LiveCodeBench

## 1. [openbmb/MiniCPM5-2B](https://huggingface.co/openbmb/MiniCPM5-2B)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
OpenBMB에서 공개한 2B 규모의 text-generation 모델인 MiniCPM5-2B가 높은 다운로드 수를 기록하며 주목받고 있습니다. 약 2.5B 파라미터를 가진 이 모델은 효율적인 텍inal generation 성능을 제공합니다.

### 핵심 포인트
- OpenBMB의 2B 규모 text-generation 모델 출시
- 150,110회의 높은 다운로드 수 기록
- 약 2.5B 파라미터를 보유한 효율적인 모델 구조

**태그**: MiniCPM5-2B, OpenBMB, text-generation

**Metrics**: {"likes": 1326, "downloads": 150110, "num_parameters": 2516756480, "pipeline_tag": "text-generation"}

### 원문 설명
likes=1326, downloads=150110, pipeline_tag=text-generation

---

## 2. [m-a-p/YuE2-3B](https://huggingface.co/m-a-p/YuE2-3B)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
m-a-p/YuE2-3B 모델이 Hugging Face에서 text-to-audio 태스크로 주목받고 있습니다. 약 3.6B 파라미터를 가진 이 모델은 최근 높은 다운로드 수를 기록하며 트렌드에 진입했습니다.

### 핵심 포인트
- m-a-p/YuE2-3B 모델의 출시 및 트렌드 형성
- text-to-audio 파이프라인을 지원하는 약 3.6B 규모의 모델
- 3,707회의 다운로드와 389개의 likes를 기록하며 사용자 관심을 확보

**태그**: m-a-p/YuE2-3B, text-to-audio, Hugging Face

**Metrics**: {"likes": 389, "downloads": 3707, "num_parameters": 3630684224, "pipeline_tag": "text-to-audio"}

### 원문 설명
likes=389, downloads=3707, pipeline_tag=text-to-audio

---

## 3. [nex-agi/Nex-N2.5-Pro](https://huggingface.co/nex-agi/Nex-N2.5-Pro)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
nex-agi/Nex-N2.5-Pro 모델이 Hugging Face에서 높은 다운로드 수를 기록하며 주목받고 있습니다. 약 397B 파라미터를 보유한 text-generation 태그의 모델입니다.

### 핵심 포인트
- nex-agi/Nex-N2.5-Pro 모델의 높은 사용자 관심도 확인
- 30,289회의 downloads와 623개의 likes 기록
- 약 396.8B 파라미터를 가진 text-generation 모델

**태그**: nex-agi, text-generation, LLM

**Metrics**: {"likes": 623, "downloads": 30289, "num_parameters": 396802360816, "pipeline_tag": "text-generation"}

### 원문 설명
likes=623, downloads=30289, pipeline_tag=text-generation

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

