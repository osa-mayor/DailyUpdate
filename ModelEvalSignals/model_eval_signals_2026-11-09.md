# Model & Eval Signals (2026-11-09)

## 오늘의 요약
Hugging Face에서는 다양한 규모의 신규 모델들이 트렌드에 진입하며 주목받고 있으며, LiveCodeBench에서는 Gemini 및 O4-Mini 모델들이 상위권 성적을 기록하며 코딩 성능 경쟁을 보여주었습니다.

### 오늘의 핵심 포인트
- Hugging Face 내 DeepSeek, Qwen, Ripple 등 다양한 파라미터 규모의 모델들이 높은 다운로드와 관심을 받으며 트렌드 형성
- LiveCodeBench 벤치마크에서 O4-Mini 및 Gemini 시리즈 모델들이 상위권 성적 기록
- 텍스트 생성부터 멀티모달(image-text-to-text)까지 다양한 활용 목적의 모델 공개

**오늘의 태그**: HuggingFace, LiveCodeBench, LLM_Trending

## 1. [xtools-at/DeepSeek-V4-Pro-Qwen3.5-9B-UNCENSORED-heretic](https://huggingface.co/xtools-at/DeepSeek-V4-Pro-Qwen3.5-9B-UNCENSORED-heretic)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
xtools-at에서 공개한 DeepSeek-V4-Pro-Qwen3.5-9B-UNCENSORED-heretic 모델이 Hugging Face에서 주목받고 있습니다. 약 9.4B 파라미터를 가진 이 모델은 텍스트 생성(text-generation) 태그로 분류되어 있습니다.

### 핵심 포인트
- DeepSeek-V4-Pro-Qwen3.5-9B-UNCENSORED-heretic 모델의 Hugging Face 트렌딩 기록
- 약 9.4B 규모의 파라미터를 보유한 text-generation 태그 모델
- 7,088회의 downloads와 797개의 likes를 기록하며 높은 관심을 받음

**태그**: DeepSeek-V4-Pro-Qwen3.5-9B-UNCENSORED-heretic, text-generation, Hugging Face

**Metrics**: {"likes": 797, "downloads": 7088, "num_parameters": 9409813744, "pipeline_tag": "text-generation"}

### 원문 설명
likes=797, downloads=7088, pipeline_tag=text-generation

---

## 2. [Qwen/Qwen3.8-27B](https://huggingface.co/Qwen/Qwen3.8-27B)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Qwen/Qwen3.8-27B 모델이 높은 다운로드 수와 좋아요를 기록하며 주목받고 있습니다. 이 모델은 image-text-to-text 파이프라인을 지원하는 27B 규모의 모델입니다.

### 핵심 포인트
- Qwen/Qwen3.8-27B 모델의 높은 사용자 관심도(likes 19,399, downloads 7,668,187) 확인
- 27.7B 파라미터를 보유한 모델 규모
- image-text-to-text 기능을 지원하는 멀티모달 파이프라인

**태그**: Qwen, Multimodal, LLM

**Metrics**: {"likes": 19399, "downloads": 7668187, "num_parameters": 27781427952, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=19399, downloads=7668187, pipeline_tag=image-text-to-text

---

## 3. [ricursiveAI/Ripple-65B-Preview](https://huggingface.co/ricursiveAI/Ripple-65B-Preview)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
ricursiveAI에서 공개한 Ripple-65B-Preview 모델이 Hugging Face에서 주목받고 있습니다. 약 65B 파라미터를 가진 이 모델은 최근 높은 다운로드 수를 기록하며 트렌드에 진입했습니다.

### 핵심 포인트
- ricursiveAI가 공개한 65B 규모의 모델인 Ripple-65B-Preview가 출시되었습니다.
- 해당 모델은 5,087회의 downloads를 기록하며 사용자들의 관심을 받고 있습니다.
- 모델의 파라미터 규모는 약 64.7B입니다.

**태그**: ricursiveAI, Ripple-65B-Preview, LLM

**Metrics**: {"likes": 393, "downloads": 5087, "num_parameters": 64782689360, "pipeline_tag": ""}

### 원문 설명
likes=393, downloads=5087, pipeline_tag=

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

