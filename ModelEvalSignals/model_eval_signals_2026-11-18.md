# Model & Eval Signals (2026-11-18)

## 오늘의 요약
Hugging Face에서는 멀티모달 및 이미지 생성 모델들이 높은 관심을 받고 있으며, LiveCodeBench에서는 Gemini 및 O4-Mini 모델들이 상위권 성적을 기록하며 코딩 성능 경쟁을 보여주었습니다.

### 오늘의 핵심 포인트
- Hugging Face 내 이미지 및 멀티모달(Image-to-Text, Text-to-Image) 모델들의 높은 트렌드 기록
- LiveCodeBench 벤치마크에서 Gemini 시리즈 및 O4-Mini 모델의 상위권 성적 달성
- 7.1B 규모의 양자화 모델 등 효율적인 파라미터 규모의 모델들에 대한 사용자 관심 증가

**오늘의 태그**: Multimodal, Text-to-Image, LiveCodeBench

## 1. [thinkingmachines/Inkling-2-Small](https://huggingface.co/thinkingmachines/Inkling-2-Small)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
thinkingmachines에서 공개한 Inkling-2-Small 모델이 Hugging Face에서 주목받고 있습니다. 이 모델은 image-text-to-text 파이프라인을 지원하는 멀티모달 모델입니다.

### 핵심 포인트
- 모델명은 thinkingmachines/Inkling-2-Small입니다.
- pipeline_tag는 image-text-to-text로 분류됩니다.
- 약 18,359회의 downloads와 435개의 likes를 기록하며 트렌딩 중입니다.

**태그**: Inkling-2-Small, image-text-to-text, multimodal

**Metrics**: {"likes": 435, "downloads": 18359, "num_parameters": 594050672720, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=435, downloads=18359, pipeline_tag=image-text-to-text

---

## 2. [MiniMaxAI/MiniMax-H3-Image](https://huggingface.co/MiniMaxAI/MiniMax-H3-Image)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
MiniMaxAI에서 공개한 MiniMax-H3-Image 모델이 Hugging Face에서 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 text-to-image 태스크를 수행하는 모델입니다.

### 핵심 포인트
- MiniMax-H3-Image 모델의 높은 다운로드 수(727,110회) 기록
- text-to-image 파이프라인을 지원하는 모델
- 1,421개의 likes를 기록하며 사용자 관심을 유도함

**태그**: MiniMax-H3-Image, text-to-image, Hugging Face

**Metrics**: {"likes": 1421, "downloads": 727110, "num_parameters": 0, "pipeline_tag": "text-to-image"}

### 원문 설명
likes=1421, downloads=727110, pipeline_tag=text-to-image

---

## 3. [chatrlabs/Qwen-Image-2.1-Uncensored-Omni-Quantized](https://huggingface.co/chatrlabs/Qwen-Image-2.1-Uncensored-Omni-Quantized)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
chatrlabs에서 공개한 Qwen-Image-2.1-Uncensored-Omni-Quantized 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 text-to-image 파이프라인을 지원하는 약 7.1B 파라미터 규모의 모델입니다.

### 핵심 포인트
- chatrlabs/Qwen-Image-2.1-Uncensored-Omni-Quantized 모델의 높은 인기도 확인
- 약 16만 회 이상의 downloads와 485 likes를 기록하며 트렌드 형성
- text-to-image 파이프라인을 지원하는 7.1B 규모의 모델

**태그**: Qwen-Image-2.1-Uncensored-Omni-Quantized, text-to-image, HuggingFace

**Metrics**: {"likes": 485, "downloads": 160748, "num_parameters": 7115124736, "pipeline_tag": "text-to-image"}

### 원문 설명
likes=485, downloads=160748, pipeline_tag=text-to-image

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

