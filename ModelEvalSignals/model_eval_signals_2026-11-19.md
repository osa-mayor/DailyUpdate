# Model & Eval Signals (2026-11-19)

## 오늘의 요약
Hugging Face에서는 멀티모달 및 TTS 모델들이 주목받고 있으며, LiveCodeBench에서는 Gemini 및 O4-Mini 모델들이 상위권 성적을 기록하며 코딩 성능 경쟁을 보여주었습니다.

### 오늘의 핵심 포인트
- Hugging Face에서 image-text-to-text 및 text-to-speech 파이프라인 지원 모델들이 트렌드로 부상
- Tencent의 Hy4-flash 등 멀티모달 모델의 주목도 상승
- LiveCodeBench 벤치마크에서 O4-Mini 및 Gemini 시리즈 모델들의 상위권 성적 기록

**오늘의 태그**: HuggingFace, Multimodal, LiveCodeBench

## 1. [harness-hub/Qwen3.8-27B-pi-adapted](https://huggingface.co/harness-hub/Qwen3.8-27B-pi-adapted)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
harness-hub/Qwen3.8-27B-pi-adapted 모델이 Hugging Face에서 주목받고 있습니다. 이 모델은 image-text-to-text 파이프라인을 지원하는 것이 특징입니다.

### 핵심 포인트
- harness-hub/Qwen3.8-27B-pi-adapted 모델의 출시 및 트렌드 확인
- likes 373회, downloads 377회를 기록하며 사용자 관심을 유도
- image-text-to-text 태그를 사용하는 멀티모달 관련 모델로 분류

**태그**: Qwen3.8-27B-pi-adapted, image-text-to-text, Hugging Face

**Metrics**: {"likes": 373, "downloads": 377, "num_parameters": 0, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=373, downloads=377, pipeline_tag=image-text-to-text

---

## 2. [n4ze3m/tiny-voca](https://huggingface.co/n4ze3m/tiny-voca)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
n4ze3m/tiny-voca 모델이 Hugging Face에서 주목받고 있습니다. 이 모델은 text-to-speech 파이프라인을 지원하는 모델입니다.

### 핵심 포인트
- n4ze3m/tiny-voca 모델의 downloads가 4430회를 기록하며 트렌드에 진입했습니다.
- 해당 모델은 text-to-speech 태그를 사용하는 음성 합성 모델입니다.
- likes 282회를 기록하며 사용자들의 관심을 받고 있습니다.

**태그**: n4ze3m/tiny-voca, text-to-speech, Hugging Face

**Metrics**: {"likes": 282, "downloads": 4430, "num_parameters": 0, "pipeline_tag": "text-to-speech"}

### 원문 설명
likes=282, downloads=4430, pipeline_tag=text-to-speech

---

## 3. [tencent/Hy4-flash](https://huggingface.co/tencent/Hy4-flash)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Tencent에서 공개한 Hy4-flash 모델이 Hugging Face에서 주목받고 있습니다. 이 모델은 image-text-to-text 파이프라인을 지원하는 멀티모달 모델입니다.

### 핵심 포인트
- Tencent에서 출시한 Hy4-flash 모델이 Hugging Face 트렌드에 진입했습니다.
- 해당 모델의 pipeline_tag는 image-text-to-text로 분류됩니다.
- 모델 파라미터 규모는 약 220B 수준입니다.

**태그**: Tencent, Hy4-flash, image-text-to-text

**Metrics**: {"likes": 217, "downloads": 159, "num_parameters": 220251201958, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=217, downloads=159, pipeline_tag=image-text-to-text

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

