# Model & Eval Signals (2026-08-15)

## 오늘의 요약
Hugging Face에서는 Qwen 27B 시리즈와 MiniMax의 오디오 생성 모델이 주목받았으며, LiveCodeBench에서는 Gemini 및 O4-Mini 모델들이 상위권 성적을 기록하며 코딩 성능 경쟁을 보여주었습니다.

### 오늘의 핵심 포인트
- Qwen 27B 모델 시리즈(GGUF 및 멀티모달)가 Hugging Face에서 높은 관심을 받으며 배포됨
- MiniMaxAI의 2.43B 규모 text-to-audio 모델인 MiniMax-Music3 공개
- LiveCodeBench 벤치마크에서 O4-Mini 및 Gemini 시리즈 모델들이 상위권 성적 기록

**오늘의 태그**: LLM, HuggingFace, LiveCodeBench, Qwen, Multi-modal

## 1. [unsloth/Qwen3.8-27B-GGUF](https://huggingface.co/unsloth/Qwen3.8-27B-GGUF)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
unsloth에서 공개한 Qwen3.8-27B-GGUF 모델이 Hugging Face에서 주목받고 있습니다. 해당 모델은 27B 규모의 파라미터를 가진 GGUF 양자화 모델입니다.

### 핵심 포인트
- unsloth에서 배포한 Qwen3.8-27B-GGUF 모델
- 657개의 likes를 기록하며 모델 트렌드에 진입
- 약 27.3B 규모의 파라미터를 보유한 모델

**태그**: unsloth, Qwen3.8-27B-GGUF, GGUF

**Metrics**: {"likes": 657, "downloads": 0, "num_parameters": 27320697856, "pipeline_tag": ""}

### 원문 설명
likes=657, downloads=0, pipeline_tag=

---

## 2. [Qwen/Qwen3.8-27B](https://huggingface.co/Qwen/Qwen3.8-27B)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Qwen/Qwen3.8-27B 모델이 Hugging Face에서 높은 likes를 기록하며 주목받고 있습니다. 이 모델은 image-text-to-text 파이프라인을 지원하는 27B 규모의 모델입니다.

### 핵심 포인트
- Qwen/Qwen3.8-27B 모델의 높은 사용자 관심(likes: 8706) 확인
- 27.7B 파라미터를 보유한 모델 규모
- image-text-to-text 기능을 지원하는 멀티모달 파이프라인

**태그**: Qwen, image-text-to-text, LLM

**Metrics**: {"likes": 8706, "downloads": 2, "num_parameters": 27781427952, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=8706, downloads=2, pipeline_tag=image-text-to-text

---

## 3. [MiniMaxAI/MiniMax-Music3](https://huggingface.co/MiniMaxAI/MiniMax-Music3)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
MiniMaxAI에서 공개한 MiniMax-Music3는 text-to-audio 태스크를 수행하는 모델입니다. 약 2.43B 파라미터를 보유하고 있으며, 최근 Hugging Face에서 주목받고 있습니다.

### 핵심 포인트
- MiniMaxAI에서 개발한 text-to-audio 모델인 MiniMax-Music3가 공개되었습니다.
- 모델의 파라미터 규모는 약 2.43B입니다.
- 최근 619개의 likes를 기록하며 모델 트렌드에 진입했습니다.

**태그**: MiniMax-Music3, text-to-audio, MiniMaxAI

**Metrics**: {"likes": 619, "downloads": 63, "num_parameters": 2431905920, "pipeline_tag": "text-to-audio"}

### 원문 설명
likes=619, downloads=63, pipeline_tag=text-to-audio

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

