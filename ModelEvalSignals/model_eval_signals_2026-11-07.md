# Model & Eval Signals (2026-11-07)

## 오늘의 요약
Hugging Face의 신규 모델 트렌드와 LiveCodeBench 벤치마크 성과를 중심으로 모델 성능 및 사용자 관심도가 분산되어 나타났습니다.

### 오늘의 핵심 포인트
- Hugging Face에서 Ripple-65B-Preview, Qwen3.5-4B-3D-Coder, Qwen3.8-27B 등 다양한 규모와 목적의 모델들이 높은 다운로드 수를 기록하며 트렌드에 진입함
- Qwen 시리즈가 멀티모달 기능 및 코딩 특화 모델로서 사용자들의 높은 관심을 받고 있음
- LiveCodeBench 벤치마크에서 O4-Mini, Gemini-2.5-Pro, Gemini-2.5-Flash 모델들이 상위권 성적을 기록하며 코딩 성능 경쟁이 지속됨

**오늘의 태그**: LLM, HuggingFace, LiveCodeBench, Multimodal, Coding-Model

## 1. [ricursiveAI/Ripple-65B-Preview](https://huggingface.co/ricursiveAI/Ripple-65B-Preview)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
ricursiveAI에서 공개한 Ripple-65B-Preview 모델이 Hugging Face에서 주목받고 있습니다. 약 65B 파라미터를 가진 이 모델은 최근 2,000회 이상의 다운로드를 기록하며 트렌드에 진입했습니다.

### 핵심 포인트
- ricursiveAI의 65B 규모 모델인 Ripple-65B-Preview 공개
- 약 64.8B 파라미터를 보유한 대규모 언어 모델
- 최근 2,013회의 다운로드와 320개의 likes를 기록하며 트렌드 형성

**태그**: ricursiveAI, Ripple-65B-Preview, LLM

**Metrics**: {"likes": 320, "downloads": 2013, "num_parameters": 64782689360, "pipeline_tag": ""}

### 원문 설명
likes=320, downloads=2013, pipeline_tag=

---

## 2. [ccore/Qwen3.5-4B-3D-Coder](https://huggingface.co/ccore/Qwen3.5-4B-3D-Coder)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
ccore에서 공개한 Qwen3.5-4B-3D-Coder 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 약 4.5B 파라미터를 가진 이 모델은 최근 많은 사용자들의 관심을 받고 있는 트렌딩 모델입니다.

### 핵심 포인트
- ccore에서 공개한 Qwen3.5-4B-3D-Coder 모델의 트렌딩 현황
- 약 4.5B 규모의 파라미터를 보유한 모델
- 190,243회의 높은 다운로드 수를 기록하며 사용자 관심을 입증

**태그**: Qwen3.5-4B-3D-Coder, Model Trending, Hugging Face

**Metrics**: {"likes": 774, "downloads": 190243, "num_parameters": 4539265536, "pipeline_tag": ""}

### 원문 설명
likes=774, downloads=190243, pipeline_tag=

---

## 3. [Qwen/Qwen3.8-27B](https://huggingface.co/Qwen/Qwen3.8-27B)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Qwen/Qwen3.8-27B 모델이 높은 다운로드 수와 좋아요를 기록하며 주목받고 있습니다. 이 모델은 이미지와 텍스트를 동시에 처리하는 멀티모달 기능을 제공합니다.

### 핵심 포인트
- Qwen/Qwen3.8-27B 모델의 높은 사용자 관심도(likes 19,262, downloads 7,845,288)
- 27.7B 파라미터를 보유한 모델 규모
- image-text-to-text 파이프라인을 지원하는 멀티모달 모델

**태그**: Qwen, Multimodal, LLM

**Metrics**: {"likes": 19262, "downloads": 7845288, "num_parameters": 27781427952, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=19262, downloads=7845288, pipeline_tag=image-text-to-text

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

