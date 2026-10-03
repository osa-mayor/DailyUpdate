# Model & Eval Signals (2026-10-04)

## 오늘의 요약
Hugging Face의 신규 모델 트렌드와 LiveCodeBench의 벤치마크 결과가 주요 흐름을 형성하였으며, 텍스트 분류, 비디오 생성, 멀티모달 등 다양한 도메인의 모델들이 주목받았습니다.

### 오늘의 핵심 포인트
- Hugging Face에서 텍스트 분류(laya), 비디오 생성(LTX-2.5), 멀티모달(clef-flash) 등 특화된 성능을 가진 모델들이 높은 관심을 받음
- LiveCodeBench 벤치마크에서 O4-Mini(High), Gemini-2.5-Pro, Gemini-2.5-Flash 등 코딩 성능 중심의 모델들이 상위권 기록
- 모델 파라미터 규모와 파이프라인(image-to-video, image-text-to-text)에 따른 다양한 활용 가능성 확인

**오늘의 태그**: HuggingFace, LiveCodeBench, Multimodal, NLP, AI_Benchmark

## 1. [convaiinnovations/laya](https://huggingface.co/convaiinnovations/laya)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Hugging Face에서 5,000개 이상의 likes를 기록하며 주목받고 있는 text-classification 모델인 convaiinnovations/laya입니다. 약 421M 파라미터를 보유한 모델로 분류 작업에 특화되어 있습니다.

### 핵심 포인트
- convaiinnovations/laya 모델이 5,066 likes를 기록하며 트렌딩 중입니다.
- 모델의 주요 태그는 text-classification입니다.
- 모델의 파라미터 규모는 약 421,293,830개입니다.

**태그**: text-classification, HuggingFace, NLP

**Metrics**: {"likes": 5066, "downloads": 0, "num_parameters": 421293830, "pipeline_tag": "text-classification"}

### 원문 설명
likes=5066, downloads=0, pipeline_tag=text-classification

---

## 2. [Lightricks/LTX-2.5](https://huggingface.co/Lightricks/LTX-2.5)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Lightricks에서 공개한 LTX-2.5 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 image-to-video 파이프라인을 지원하는 것이 특징입니다.

### 핵심 포인트
- Lightricks에서 출시한 LTX-2.5 모델의 트렌드 상승
- 1,600,000회 이상의 높은 다운로드 수 기록
- image-to-video 기능을 제공하는 모델 파이프라인

**태그**: Lightricks, LTX-2.5, image-to-video

**Metrics**: {"likes": 6101, "downloads": 1629984, "num_parameters": 0, "pipeline_tag": "image-to-video"}

### 원문 설명
likes=6101, downloads=1629984, pipeline_tag=image-to-video

---

## 3. [Cloudflare/clef-flash](https://huggingface.co/Cloudflare/clef-flash)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Cloudflare에서 공개한 clef-flash 모델이 최근 주목받고 있습니다. 이 모델은 image-text-to-text 파이프라인을 지원하는 멀티모달 모델입니다.

### 핵심 포인트
- Cloudflare/clef-flash 모델이 높은 다운로드 수와 좋아요를 기록하며 트렌드에 진입했습니다.
- 약 9.4B 파라미터를 가진 모델로 분류됩니다.
- image-text-to-text 태그를 사용하는 멀티모달 작업용 모델입니다.

**태그**: Cloudflare, clef-flash, image-text-to-text

**Metrics**: {"likes": 344, "downloads": 4310, "num_parameters": 9409813744, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=344, downloads=4310, pipeline_tag=image-text-to-text

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

