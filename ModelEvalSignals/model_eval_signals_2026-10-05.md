# Model & Eval Signals (2026-10-05)

## 오늘의 요약
Hugging Face의 신규 모델(텍스트 분류, 생성, 비디오 생성) 트렌드와 LiveCodeBench의 코딩 성능 벤치마크 결과가 주요 흐름을 형성했습니다.

### 오늘의 핵심 포인트
- Hugging Face에서 텍스트 분류(Laya), 대규모 언어 모델(Kolibri-1), 비디오 생성(LTX-2.5) 등 다양한 태스크의 모델들이 주목받고 있습니다.
- LiveCodeBench 벤치마크에서 O4-Mini, Gemini-2.5 시리즈 등 최신 모델들이 상위권 성적을 기록하며 코딩 능력을 입증했습니다.
- 모델 파라미터 규모가 421M에서 78B까지 다양하게 분포하며 각기 다른 특화 태스크를 수행하고 있습니다.

**오늘의 태그**: HuggingFace, LiveCodeBench, LLM, Text-to-Video, Benchmark

## 1. [convaiinnovations/laya](https://huggingface.co/convaiinnovations/laya)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
convaiinnovations/laya 모델이 Hugging Face에서 주목받으며 텍스트 분류 태스크를 수행합니다. 약 421M 파라미터를 가진 모델로, 높은 좋아요 수와 다운로드 수를 기록하고 있습니다.

### 핵심 포인트
- convaiinnovations/laya 모델은 text-classification 태스크를 위한 모델입니다.
- 약 421,293,830개의 파라미터를 보유하고 있습니다.
- 5,143개의 likes와 3,752개의 downloads를 기록하며 트렌딩 중입니다.

**태그**: text-classification, NLP, HuggingFace

**Metrics**: {"likes": 5143, "downloads": 3752, "num_parameters": 421293830, "pipeline_tag": "text-classification"}

### 원문 설명
likes=5143, downloads=3752, pipeline_tag=text-classification

---

## 2. [Aleph-Alpha/Kolibri-1](https://huggingface.co/Aleph-Alpha/Kolibri-1)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Aleph-Alpha에서 공개한 Kolibri-1 모델이 Hugging Face에서 주목받고 있습니다. 약 78B 파라미터를 보유한 text-generation 태그의 모델입니다.

### 핵심 포인트
- Aleph-Alpha의 Kolibri-1 모델이 Hugging Face에서 트렌딩 중입니다.
- 모델의 파라미터 규모는 약 78.1B입니다.
- text-generation 태그를 사용하는 모델로, 높은 다운로드 수를 기록하고 있습니다.

**태그**: Aleph-Alpha, Kolibri-1, text-generation

**Metrics**: {"likes": 372, "downloads": 1135, "num_parameters": 78103074560, "pipeline_tag": "text-generation"}

### 원문 설명
likes=372, downloads=1135, pipeline_tag=text-generation

---

## 3. [Lightricks/LTX-2.5](https://huggingface.co/Lightricks/LTX-2.5)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Lightricks에서 공개한 LTX-2.5 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 image-to-video 파이프라인을 지원하는 것이 특징입니다.

### 핵심 포인트
- Lightricks에서 출시한 LTX-2.5 모델의 트렌딩 현황
- 1,626,951회의 높은 다운로드 수를 기록하며 사용자 관심을 입증
- image-to-video 기능을 제공하는 파이프라인 모델

**태그**: Lightricks, LTX-2.5, image-to-video

**Metrics**: {"likes": 6269, "downloads": 1626951, "num_parameters": 0, "pipeline_tag": "image-to-video"}

### 원문 설명
likes=6269, downloads=1626951, pipeline_tag=image-to-video

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

