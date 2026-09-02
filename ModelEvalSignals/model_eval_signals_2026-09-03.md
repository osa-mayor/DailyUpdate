# Model & Eval Signals (2026-09-03)

## 오늘의 요약
Hugging Face에서는 멀티모달(Vision) 및 음성 합성(TTS) 분야의 신규 모델들이 주목받았으며, LiveCodeBench에서는 O4-Mini와 Gemini 시리즈 모델들이 상위권 성적을 기록하며 코딩 성능 경쟁을 보여주었습니다.

### 오늘의 핵심 포인트
- Hugging Face 내 멀티모달(Image-Text-to-Text) 및 TTS 모델의 높은 관심도 확인
- DeepSeek 및 Unsloth 등 주요 개발사의 신규 모델 출시 및 GGUF 포맷 활용 트렌드
- LiveCodeBench 벤치마크를 통한 O4-Mini 및 Gemini 모델의 코딩 성능 검증

**오늘의 태그**: HuggingFace, Multimodal, LiveCodeBench, LLM_Trending

## 1. [unsloth/Qwen3.8-Flash-Next-GGUF](https://huggingface.co/unsloth/Qwen3.8-Flash-Next-GGUF)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
unsloth에서 공개한 Qwen3.8-Flash-Next-GGUF 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 image-text-to-text 파이프라인을 지원하는 GGUF 포맷 모델입니다.

### 핵심 포인트
- unsloth에서 배포한 Qwen3.8-Flash-Next-GGUF 모델의 트렌딩 확인
- 431,339회의 높은 다운로드 수를 기록하며 사용자들의 높은 관심을 받음
- image-text-to-text 파이프라인을 지원하는 멀티모달 성격의 모델

**태그**: unsloth, Qwen3.8-Flash-Next-GGUF, image-text-to-text

**Metrics**: {"likes": 720, "downloads": 431339, "num_parameters": 176943899520, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=720, downloads=431339, pipeline_tag=image-text-to-text

---

## 2. [BreezeBlue/Breeze-TTS-2](https://huggingface.co/BreezeBlue/Breeze-TTS-2)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
BreezeBlue에서 공개한 Breeze-TTS-2 모델이 Hugging Face에서 주목받고 있습니다. 이 모델은 text-to-speech 파이프라인을 지원하는 음성 합성 모델입니다.

### 핵심 포인트
- Breeze-TTS-2는 text-to-speech 태그를 가진 음성 합성 모델입니다.
- 약 3.47B(3,466,363,713) 파라미터를 보유하고 있습니다.
- 최근 3,086회의 downloads와 345개의 likes를 기록하며 트렌드에 진입했습니다.

**태그**: Breeze-TTS-2, text-to-speech, Hugging Face

**Metrics**: {"likes": 345, "downloads": 3086, "num_parameters": 3466363713, "pipeline_tag": "text-to-speech"}

### 원문 설명
likes=345, downloads=3086, pipeline_tag=text-to-speech

---

## 3. [deepseek-ai/DeepSeek-V4-Flash-Vision-Exp](https://huggingface.co/deepseek-ai/DeepSeek-V4-Flash-Vision-Exp)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
DeepSeek-AI에서 출시한 DeepSeek-V4-Flash-Vision-Exp 모델이 Hugging Face에서 주목받고 있습니다. 이 모델은 이미지와 텍스트를 결합하여 처리하는 멀티모달 기능을 제공합니다.

### 핵심 포인트
- DeepSeek-AI의 새로운 vision 실험 모델인 DeepSeek-V4-Flash-Vision-Exp 출시
- image-text-to-text 파이프라인을 지원하는 멀티모달 모델
- 약 304.6B 파라미터를 보유하며 높은 다운로드 수를 기록 중

**태그**: DeepSeek-V4-Flash-Vision-Exp, DeepSeek-AI, image-text-to-text

**Metrics**: {"likes": 493, "downloads": 17893, "num_parameters": 304646824126, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=493, downloads=17893, pipeline_tag=image-text-to-text

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

