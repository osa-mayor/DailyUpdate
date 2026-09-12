# Model & Eval Signals (2026-09-13)

## 오늘의 요약
Hugging Face의 신규 모델 출시로 인한 텍스트 생성 및 멀티모달 모델의 트렌드와 LiveCodeBench를 통한 코딩 성능 벤치마크 결과가 주요 흐름을 형성했습니다.

### 오늘의 핵심 포인트
- OpenBMB, nex-agi, DeepSeek 등 다양한 규모와 목적(2B~397B)을 가진 텍스트 생성 및 멀티모달 모델들이 Hugging Face에서 높은 관심을 받음
- DeepSeek-V4.1-Flash와 같이 이미지와 텍스트를 동시에 처리하는 멀티모달 기능이 주목받는 추세임
- LiveCodeBench 벤치마크에서 O4-Mini 및 Gemini 시리즈 모델들이 상위권 성적을 기록하며 코딩 성능 경쟁이 지속됨

**오늘의 태그**: LLM, Multimodal, LiveCodeBench, HuggingFace, Text-Generation

## 1. [openbmb/MiniCPM5-2B](https://huggingface.co/openbmb/MiniCPM5-2B)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
OpenBMB에서 공개한 2B 규모의 text-generation 모델인 MiniCPM5-2B가 높은 다운로드 수를 기록하며 주목받고 있습니다. 약 2.5B 파라미터를 가진 이 모델은 효율적인 텍inal generation 성능을 제공합니다.

### 핵심 포인트
- OpenBMB의 2B 규모 text-generation 모델 출시
- 10만 회 이상의 높은 downloads 기록
- 약 2.5B 파라미터를 보유한 효율적인 모델 구조

**태그**: MiniCPM5-2B, OpenBMB, text-generation

**Metrics**: {"likes": 1248, "downloads": 102334, "num_parameters": 2516756480, "pipeline_tag": "text-generation"}

### 원문 설명
likes=1248, downloads=102334, pipeline_tag=text-generation

---

## 2. [nex-agi/Nex-N2.5-Pro](https://huggingface.co/nex-agi/Nex-N2.5-Pro)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
nex-agi에서 공개한 nex-agi/Nex-N2.5-Pro 모델이 Hugging Face에서 주목받고 있습니다. 약 397B 파라미터를 보유한 text-generation 모델로 높은 다운로드 수를 기록 중입니다.

### 핵심 포인트
- nex-agi/Nex-N2.5-Pro 모델의 Hugging Face 트렌딩 기록
- 약 396.8B 파라미터를 가진 대규모 text-generation 모델
- 30,000회 이상의 높은 다운로드 수와 615개의 likes 기록

**태그**: nex-agi, text-generation, LLM

**Metrics**: {"likes": 615, "downloads": 30081, "num_parameters": 396802360816, "pipeline_tag": "text-generation"}

### 원문 설명
likes=615, downloads=30081, pipeline_tag=text-generation

---

## 3. [deepseek-ai/DeepSeek-V4.1-Flash](https://huggingface.co/deepseek-ai/DeepSeek-V4.1-Flash)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
DeepSeek-AI에서 출시한 DeepSeek-V4.1-Flash 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 이미지와 텍스트를 동시에 처리하는 멀티모달 기능을 제공합니다.

### 핵심 포인트
- DeepSeek-AI의 새로운 모델인 DeepSeek-V4.1-Flash 출시
- 14만 회 이상의 높은 다운로드 수를 기록하며 트렌드 형성
- image-text-to-text 파이프라인을 지원하는 멀티모달 모델

**태그**: DeepSeek-V4.1-Flash, DeepSeek-AI, image-text-to-text

**Metrics**: {"likes": 1976, "downloads": 140636, "num_parameters": 763205315794, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=1976, downloads=140636, pipeline_tag=image-text-to-text

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

