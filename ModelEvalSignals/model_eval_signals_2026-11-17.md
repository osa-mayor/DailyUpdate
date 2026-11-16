# Model & Eval Signals (2026-11-17)

## 오늘의 요약
Hugging Face의 신규 모델 공개로 인한 멀티모달 및 TTS 분야의 활발한 트렌드와 LiveCodeBench 벤치마크에서의 상위 모델 성적 기록이 주요 흐름입니다.

### 오늘의 핵심 포인트
- MiniMax-H3-Image, Inkling-2-Small 등 텍스트-이미지 및 멀티모달 모델의 높은 주목도
- Zyphra의 ZONOS3-Mini(TTS) 모델이 높은 다운로드 수를 기록하며 최신 트렌드 형성
- LiveCodeBench 벤치마크에서 O4-Mini 및 Gemini 시리즈 모델들의 상위권 성적 기록

**오늘의 태그**: HuggingFace, Multimodal, LiveCodeBench

## 1. [MiniMaxAI/MiniMax-H3-Image](https://huggingface.co/MiniMaxAI/MiniMax-H3-Image)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
MiniMaxAI에서 공개한 MiniMax-H3-Image 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 text-to-image 태스크를 수행하는 모델입니다.

### 핵심 포인트
- MiniMax-H3-Image 모델의 높은 사용자 유입 확인
- 60만 회 이상의 downloads를 기록하며 높은 인기를 얻음
- text-to-image 파이프라인을 지원하는 모델

**태그**: MiniMax-H3-Image, text-to-image, MiniMaxAI

**Metrics**: {"likes": 1286, "downloads": 609130, "num_parameters": 0, "pipeline_tag": "text-to-image"}

### 원문 설명
likes=1286, downloads=609130, pipeline_tag=text-to-image

---

## 2. [thinkingmachines/Inkling-2-Small](https://huggingface.co/thinkingmachines/Inkling-2-Small)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
thinkingmachines에서 공개한 Inkling-2-Small 모델이 Hugging Face에서 주목받고 있습니다. 이 모델은 image-text-to-text 파이프라인을 지원하는 멀티모달 모델입니다.

### 핵심 포인트
- Inkling-2-Small 모델은 약 594B 파라미터를 보유한 대규모 모델입니다.
- image-text-to-text 태그를 사용하는 멀티모달 작업에 특화되어 있습니다.
- 출시 이후 16,918회의 다운로드와 386개의 likes를 기록하며 트렌드에 진입했습니다.

**태그**: Inkling-2-Small, image-text-to-text, multimodal

**Metrics**: {"likes": 386, "downloads": 16918, "num_parameters": 594050672720, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=386, downloads=16918, pipeline_tag=image-text-to-text

---

## 3. [Zyphra/ZONOS3-Mini](https://huggingface.co/Zyphra/ZONOS3-Mini)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Zyphra에서 공개한 ZONOS3-Mini는 text-to-speech 태그를 가진 최신 모델입니다. 약 8.8억 개의 파라미터를 보유하고 있으며, 최근 높은 다운로드 수를 기록하며 주목받고 있습니다.

### 핵심 포인트
- Zyphra/ZONOS3-Mini 모델은 text-to-speech 파이프라인을 지원합니다.
- 모델의 파라미터 규모는 약 886,342,504개입니다.
- 최근 69,946회의 다운로드를 기록하며 높은 관심을 받고 있습니다.

**태그**: Zyphra, ZONOS3-Mini, text-to-speech

**Metrics**: {"likes": 447, "downloads": 69946, "num_parameters": 886342504, "pipeline_tag": "text-to-speech"}

### 원문 설명
likes=447, downloads=69946, pipeline_tag=text-to-speech

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

