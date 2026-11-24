# Model & Eval Signals (2026-11-25)

## 오늘의 요약
Hugging Face에서는 멀티모달 기능을 갖춘 Inkling-2-Mini 계열 모델들이 높은 관심을 받고 있으며, LiveCodeBench에서는 O4-Mini와 Gemini 시리즈 모델들이 상위권 성적을 기록하며 코딩 성능 경쟁을 보여주었습니다.

### 오늘의 핵심 포인트
- Hugging Face 내 Inkling-2-Mini 기반 멀티모달(image-text-to-text) 모델들의 높은 트렌드 기록
- LiveCodeBench 벤치마크에서 O4-Mini 및 Gemini 시리즈 모델들의 상위권 성적 달성
- GGUF 포맷 및 Uncensored 버전 등 특정 목적을 가진 모델들의 활발한 배포 및 다운로드

**오늘의 태그**: Multimodal, LiveCodeBench, HuggingFace_Trending

## 1. [thinkingmachines/Inkling-2-Mini](https://huggingface.co/thinkingmachines/Inkling-2-Mini)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Hugging Face에서 높은 관심을 받고 있는 thinkingmachines/Inkling-2-Mini 모델이 공개되었습니다. 이 모델은 image-text-to-text 파이프라인을 지원하는 멀티모달 모델입니다.

### 핵심 포인트
- 5,734개의 likes와 69,042회의 downloads를 기록하며 높은 관심을 받고 있습니다.
- 약 26.4B 파라미터를 가진 모델입니다.
- image-text-to-text 태그를 가진 멀티모달 모델입니다.

**태그**: thinkingmachines/Inkling-2-Mini, image-text-to-text, multimodal

**Metrics**: {"likes": 5734, "downloads": 69042, "num_parameters": 26388646440, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=5734, downloads=69042, pipeline_tag=image-text-to-text

---

## 2. [AtomicChat/Inkling-2-Mini-Uncensored-GGUF](https://huggingface.co/AtomicChat/Inkling-2-Mini-Uncensored-GGUF)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
AtomicChat에서 공개한 Inkling-2-Mini-Uncensored-GGUF 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 이미지와 텍스트를 동시에 처리하는 멀티모달 기능을 갖춘 것이 특징입니다.

### 핵심 포인트
- Inkling-2-Mini-Uncensored-GGUF 모델의 높은 사용자 관심도 반영 (downloads 573,775회)
- image-text-to-text 파이프라인을 지원하는 멀티모달 모델
- 약 26B 파라미터 규모의 모델 성능 및 배포

**태그**: Inkling-2-Mini-Uncensored-GGUF, image-text-to-text, GGUF

**Metrics**: {"likes": 731, "downloads": 573775, "num_parameters": 26070385152, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=731, downloads=573775, pipeline_tag=image-text-to-text

---

## 3. [harness-hub/Qwen3.8-27B-pi-adapted](https://huggingface.co/harness-hub/Qwen3.8-27B-pi-adapted)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Qwen3.8-27B-pi-adapted 모델이 Hugging Face에서 주목받고 있습니다. 이 모델은 image-text-to-text 파이프라인을 지원하는 것이 특징입니다.

### 핵심 포인트
- harness-hub/Qwen3.8-27B-pi-adapted 모델의 높은 관심도 확인
- likes 1,065회 및 downloads 3,529회를 기록하며 트렌드 형성
- image-text-to-text 태그를 사용하는 멀티모달 관련 모델

**태그**: Qwen3.8-27B-pi-adapted, image-text-to-text, Hugging Face

**Metrics**: {"likes": 1065, "downloads": 3529, "num_parameters": 0, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=1065, downloads=3529, pipeline_tag=image-text-to-text

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

