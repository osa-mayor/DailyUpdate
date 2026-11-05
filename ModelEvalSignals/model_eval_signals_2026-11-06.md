# Model & Eval Signals (2026-11-06)

## 오늘의 요약
Hugging Face에서는 멀티모달 기능을 갖춘 Qwen 및 Kimi 시리즈 모델이 높은 관심을 받고 있으며, LiveCodeBench에서는 O4-Mini와 Gemini 시리즈 모델들이 상위권 성적을 기록하며 코딩 성능 경쟁을 보여주었습니다.

### 오늘의 핵심 포인트
- Qwen 및 Moonshot AI의 Kimi 모델 등 이미지-텍스트 통합 처리가 가능한 멀티모달 모델 트렌드 지속
- FusionCow의 Sulphur-3 모델이 높은 다운로드와 좋아요를 기록하며 트렌드 진입
- LiveCodeBench 벤치마크에서 O4-Mini 및 Gemini 시리즈 모델들의 상위권 성적 기록

**오늘의 태그**: Multimodal, LiveCodeBench, HuggingFace_Trending

## 1. [Qwen/Qwen3.8-27B](https://huggingface.co/Qwen/Qwen3.8-27B)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Qwen/Qwen3.8-27B 모델이 높은 다운로드 수와 좋아요를 기록하며 주목받고 있습니다. 이 모델은 이미지와 텍스트를 동시에 처리하는 image-text-to-text 파이프라인을 지원합니다.

### 핵심 포인트
- 8,037,597회의 높은 downloads를 기록하며 강력한 트렌드를 보임
- 27.7B 규모의 파라미터를 가진 모델임
- image-text-to-text 기능을 지원하는 멀티모달 모델

**태그**: Qwen, Multimodal, LLM

**Metrics**: {"likes": 19203, "downloads": 8037597, "num_parameters": 27781427952, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=19203, downloads=8037597, pipeline_tag=image-text-to-text

---

## 2. [moonshotai/Kimi-K3.1-Pro](https://huggingface.co/moonshotai/Kimi-K3.1-Pro)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Moonshot AI에서 공개한 Kimi-K3.1-Pro 모델이 Hugging Face에서 높은 관심을 받고 있습니다. 이 모델은 이미지와 텍스트를 동시에 처리하는 멀티모달 기능을 제공합니다.

### 핵심 포인트
- moonshotai/Kimi-K3.1-Pro 모델이 높은 다운로드 수를 기록하며 트렌드에 진입했습니다.
- pipeline_tag는 image-text-to-text로 멀티모달 작업에 특화되어 있습니다.
- 약 2.78T 파라미터를 보유한 대규모 모델입니다.

**태그**: moonshotai, Kimi-K3.1-Pro, image-text-to-text

**Metrics**: {"likes": 879, "downloads": 11658, "num_parameters": 2780110363392, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=879, downloads=11658, pipeline_tag=image-text-to-text

---

## 3. [FusionCow/Sulphur-3](https://huggingface.co/FusionCow/Sulphur-3)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
FusionCow에서 공개한 Sulphur-3 모델이 Hugging Face에서 주목받고 있습니다. 해당 모델은 377개의 likes와 607회의 downloads를 기록하며 트렌드에 진입했습니다.

### 핵심 포인트
- FusionCow/Sulphur-3 모델의 Hugging Face 트렌드 발생
- likes 377회 및 downloads 607회 기록
- 최근 모델 트렌드 지표에 반영됨

**태그**: Sulphur-3, FusionCow, Model Trending

**Metrics**: {"likes": 377, "downloads": 607, "num_parameters": 0, "pipeline_tag": ""}

### 원문 설명
likes=377, downloads=607, pipeline_tag=

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

