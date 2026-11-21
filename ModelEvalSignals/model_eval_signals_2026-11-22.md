# Model & Eval Signals (2026-11-22)

## 오늘의 요약
Hugging Face에서는 멀티모달(image-text-to-text) 기능을 갖춘 Inkling-2-Mini 및 Qwen 계열 모델이 주목받고 있으며, LiveCodeBench에서는 O4-Mini와 Gemini 시리즈 모델들이 상위권 성적을 기록하며 코딩 성능 경쟁을 보여주었습니다.

### 오늘의 핵심 포인트
- Inkling-2-Mini 및 Qwen3.8-27B-pi-adapted 등 image-text-to-text 파이프라인 지원 모델의 트렌드 상승
- LiveCodeBench 벤치마크에서 O4-Mini 및 Gemini 시리즈 모델들의 상위권 성적 기록
- GGUF 포맷 및 멀티모달 태스크 중심의 모델 배포 및 활용 활성화

**오늘의 태그**: Multimodal, LiveCodeBench, HuggingFace_Trending

## 1. [unsloth/Inkling-2-Mini-GGUF](https://huggingface.co/unsloth/Inkling-2-Mini-GGUF)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
unsloth/Inkling-2-Mini-GGUF 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 image-text-to-text 파이프라인을 지원하는 GGUF 포맷의 모델입니다.

### 핵심 포인트
- unsloth/Inkling-2-Mini-GGUF 모델의 downloads가 238,152회를 기록하며 높은 관심을 받고 있습니다.
- 해당 모델은 image-text-to-text 파이프라인 태그를 가진 멀티모달 성격의 모델입니다.
- 모델의 파라미터 규모는 약 26B(26,070,390,272) 수준입니다.

**태그**: unsloth, GGUF, image-text-to-text

**Metrics**: {"likes": 537, "downloads": 238152, "num_parameters": 26070390272, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=537, downloads=238152, pipeline_tag=image-text-to-text

---

## 2. [harness-hub/Qwen3.8-27B-pi-adapted](https://huggingface.co/harness-hub/Qwen3.8-27B-pi-adapted)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Qwen3.8-27B-pi-adapted 모델이 Hugging Face에서 주목받고 있습니다. 이 모델은 image-text-to-text 파이프라인을 지원하는 것이 특징입니다.

### 핵심 포인트
- harness-hub/Qwen3.8-27B-pi-adapted 모델의 출시 및 트렌드 확인
- 915개의 likes와 2,383회의 downloads를 기록하며 사용자 관심을 유도
- image-text-to-text 태그를 사용하는 멀티모달 관련 모델로 분류

**태그**: Qwen3.8-27B-pi-adapted, image-text-to-text, Hugging Face

**Metrics**: {"likes": 915, "downloads": 2383, "num_parameters": 0, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=915, downloads=2383, pipeline_tag=image-text-to-text

---

## 3. [thinkingmachines/Inkling-2-Mini](https://huggingface.co/thinkingmachines/Inkling-2-Mini)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
thinkingmachines에서 공개한 Inkling-2-Mini 모델이 Hugging Face에서 주목받고 있습니다. 이 모델은 약 26.4B 파라미터를 가진 image-text-to-text 태스크용 모델입니다.

### 핵심 포인트
- 모델명은 thinkingmachines/Inkling-2-Mini이며, 약 26.4B 파라미터를 보유하고 있습니다.
- pipeline_tag는 image-text-to-text로 멀티모달 작업에 특화되어 있습니다.
- 현재 2,060개의 likes와 7,944회의 downloads를 기록하며 트렌딩 중입니다.

**태그**: Inkling-2-Mini, image-text-to-text, multimodal

**Metrics**: {"likes": 2060, "downloads": 7944, "num_parameters": 26388646440, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=2060, downloads=7944, pipeline_tag=image-text-to-text

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

