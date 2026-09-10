# Model & Eval Signals (2026-09-11)

## 오늘의 요약
Hugging Face를 중심으로 다양한 규모의 텍러 생성 및 멀티모달 모델들이 주목받고 있으며, LiveCodeBench 벤치마크에서는 O4-Mini와 Gemini 시리즈 모델들이 상위권 성적을 기록하며 코딩 성능 경쟁을 보여주었습니다.

### 오늘의 핵심 포인트
- OpenBMB, DeepSeek, nex-agi 등 다양한 연구소의 신규 모델(MiniCPM5-2B, DeepSeek-V4.1-Flash 등)이 Hugging Face 트렌드 진입
- 텍스트 생성부터 멀티모달 기능까지 다양한 목적의 모델들이 높은 다운로드 및 관심을 기록
- LiveCodeBench 벤치마크에서 O4-Mini 및 Gemini 시리즈 모델들이 상위권 성적을 기록하며 코딩 역량 입증

**오늘의 태그**: LLM, HuggingFace, LiveCodeBench, Multimodal, Text-Generation

## 1. [openbmb/MiniCPM5-2B](https://huggingface.co/openbmb/MiniCPM5-2B)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
OpenBMB에서 공개한 MiniCPM5-2B 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 약 2.5B 파라미터를 가진 이 모델은 text-generation 태스크를 위한 모델입니다.

### 핵심 포인트
- OpenBMB의 MiniCPM5-2B 모델이 높은 관심을 받고 있음
- 약 2.5B 규모의 파라미터를 보유한 text-generation 모델
- 42,289회의 다운로드와 1,089개의 likes를 기록함

**태그**: MiniCPM5-2B, OpenBMB, text-generation

**Metrics**: {"likes": 1089, "downloads": 42289, "num_parameters": 2516756480, "pipeline_tag": "text-generation"}

### 원문 설명
likes=1089, downloads=42289, pipeline_tag=text-generation

---

## 2. [deepseek-ai/DeepSeek-V4.1-Flash](https://huggingface.co/deepseek-ai/DeepSeek-V4.1-Flash)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
DeepSeek-AI에서 출시한 DeepSeek-V4.1-Flash 모델이 Hugging Face에서 주목받고 있습니다. 이 모델은 이미지와 텍스트를 동시에 처리하는 멀티모달 기능을 제공합니다.

### 핵심 포인트
- DeepSeek-AI의 새로운 모델인 DeepSeek-V4.1-Flash가 공개되었습니다.
- 1,224개의 likes를 기록하며 모델 트렌드에서 높은 관심을 받고 있습니다.
- image-text-to-text 파이프라인을 지원하는 멀티모달 모델입니다.

**태그**: DeepSeek-V4.1-Flash, Multimodal, Hugging Face

**Metrics**: {"likes": 1224, "downloads": 6, "num_parameters": 763205315794, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=1224, downloads=6, pipeline_tag=image-text-to-text

---

## 3. [nex-agi/Nex-N2.5-mini](https://huggingface.co/nex-agi/Nex-N2.5-mini)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
nex-agi에서 공개한 nex-agi/Nex-N2.5-mini 모델이 Hugging Face에서 주목받고 있습니다. 약 35B 파라미터 규모의 text-generation 모델로, 높은 다운로드 수를 기록하며 트렌드에 진입했습니다.

### 핵심 포인트
- nex-agi/Nex-N2.5-mini 모델의 Hugging Face 트렌드 발생
- 약 35.1B 파라미터를 보유한 text-generation 태그 모델
- 2,444회의 downloads와 644개의 likes를 기록 중

**태그**: nex-agi, text-generation, LLM

**Metrics**: {"likes": 644, "downloads": 2444, "num_parameters": 35107181936, "pipeline_tag": "text-generation"}

### 원문 설명
likes=644, downloads=2444, pipeline_tag=text-generation

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

