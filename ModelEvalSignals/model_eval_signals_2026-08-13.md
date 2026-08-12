# Model & Eval Signals (2026-08-13)

## 오늘의 요약
Hugging Face에서는 새로운 비디오 생성 및 대규모 언어 모델(LLM)이 주목받고 있으며, LiveCodeBench에서는 코딩 성능을 중심으로 다양한 모델들의 벤치마크 결과가 업데이트되었습니다.

### 오늘의 핵심 포인트
- Lightricks 및 Minimax의 LTX-2.5, Minimax-h3-Turbo 등 image-to-video 파이프라인 모델 주목
- Qwen의 2.4T 파라미터 규모 대형 언어 모델(LLM) 공개
- LiveCodeBench에서 O4-Mini, Gemini 시리즈 등 코딩 성능 중심의 모델 벤치마크 결과 발표

**오늘의 태그**: LLM, Image-to-Video, LiveCodeBench

## 1. [Lightricks/LTX-2.5](https://huggingface.co/Lightricks/LTX-2.5)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Lightricks에서 공개한 LTX-2.5 모델이 Hugging Face에서 주목받고 있습니다. 이 모델은 image-to-video 파이프라인을 지원하는 것이 특징입니다.

### 핵심 포인트
- Lightricks에서 출시한 LTX-2.5 모델
- image-to-video 기능을 제공하는 pipeline_tag 보유
- 529개의 likes를 기록하며 모델 트렌드 형성

**태그**: Lightricks, LTX-2.5, image-to-video

**Metrics**: {"likes": 529, "downloads": 39, "num_parameters": 0, "pipeline_tag": "image-to-video"}

### 원문 설명
likes=529, downloads=39, pipeline_tag=image-to-video

---

## 2. [Qwen/Qwen3.8-2.4T-A95B](https://huggingface.co/Qwen/Qwen3.8-2.4T-A95B)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Qwen/Qwen3.8-2.4T-A95B 모델이 Hugging Face에서 텍스트 생성 태그와 함께 주목받고 있습니다. 해당 모델은 약 2.4T 파라미터를 보유한 대규모 모델로 확인됩니다.

### 핵심 포인트
- Qwen/Qwen3.8-2.4T-A95B 모델의 Hugging Face 트렌딩 데이터 확인
- likes 377회, downloads 978회를 기록하며 텍스트 생성(text-generation) 태그로 분류됨
- 약 2.45T 규모의 파라미터를 가진 대형 모델임

**태그**: Qwen, text-generation, LLM

**Metrics**: {"likes": 377, "downloads": 978, "num_parameters": 2446182725504, "pipeline_tag": "text-generation"}

### 원문 설명
likes=377, downloads=978, pipeline_tag=text-generation

---

## 3. [lightx2v/Minimax-h3-Turbo](https://huggingface.co/lightx2v/Minimax-h3-Turbo)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
lightx2v/Minimax-h3-Turbo 모델이 Hugging Face에서 주목받고 있습니다. 이 모델은 image-to-video 파이프라인을 지원하는 것이 특징입니다.

### 핵심 포인트
- lightx2v/Minimax-h3-Turbo 모델의 높은 다운로드 수 기록
- image-to-video 파이프라인 태그를 보유한 모델
- 405개의 likes와 20,376회의 downloads를 기록하며 트렌드 형성

**태그**: Minimax-h3-Turbo, image-to-video, Hugging Face

**Metrics**: {"likes": 405, "downloads": 20376, "num_parameters": 0, "pipeline_tag": "image-to-video"}

### 원문 설명
likes=405, downloads=20376, pipeline_tag=image-to-video

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

