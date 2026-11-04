# Model & Eval Signals (2026-11-05)

## 오늘의 요약
Hugging Face를 중심으로 한 신규 모델 출시와 LiveCodeBench 벤치마크를 통한 코딩 성능 검증이 주요 흐름을 형성했습니다.

### 오늘의 핵심 포인트
- Hugging Face에서 Qwen3.5 기반 코딩 모델 및 LiquidAI의 소형 언어 모델(LFM3-1.7B)이 높은 관심을 받으며 배포됨
- Mistral AI의 Mistral-Large-4-1T-A52B 모델이 멀티모달(image-text-to-text) 기능을 선보이며 주목받음
- LiveCodeBench 벤치마크에서 O4-Mini, Gemini 시리즈 등 주요 모델들이 상위권 성적을 기록하며 코딩 성능 경쟁 가속화

**오늘의 태그**: HuggingFace, LiveCodeBench, LLM_Trending

## 1. [ccore/Qwen3.5-4B-3D-Coder](https://huggingface.co/ccore/Qwen3.5-4B-3D-Coder)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
ccore에서 공개한 Qwen3.5-4B-3D-Coder 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 약 4.5B 파라미터를 가진 이 모델은 최근 사용자들 사이에서 활발하게 활용되고 있습니다.

### 핵심 포인트
- ccore에서 공개한 Qwen3.5-4B-3D-Coder 모델의 트렌딩 현황
- 123,321회의 높은 downloads 기록
- 약 4.5B 규모의 num_parameters를 가진 모델

**태그**: Qwen3.5-4B-3D-Coder, Model Trending, HuggingFace

**Metrics**: {"likes": 647, "downloads": 123321, "num_parameters": 4539265536, "pipeline_tag": ""}

### 원문 설명
likes=647, downloads=123321, pipeline_tag=

---

## 2. [LiquidAI/LFM3-1.7B](https://huggingface.co/LiquidAI/LFM3-1.7B)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
LiquidAI에서 출시한 1.7B 규모의 text-generation 모델인 LFM3-1.7B가 Hugging Face에서 주목받고 있습니다. 약 5.5만 회의 다운로드와 1,400개 이상의 좋아요를 기록하며 높은 관심을 받고 있습니다.

### 핵심 포인트
- LiquidAI에서 공개한 1.7B 파라미터 규모의 text-generation 모델입니다.
- Hugging Face에서 54,959회의 다운로드와 1,472개의 likes를 기록하며 트렌딩 중입니다.
- 매우 효율적인 크기의 모델로 텍스트 생성 작업에 최적화되어 있습니다.

**태그**: LiquidAI, LFM3-1.7B, text-generation

**Metrics**: {"likes": 1472, "downloads": 54959, "num_parameters": 1728801536, "pipeline_tag": "text-generation"}

### 원문 설명
likes=1472, downloads=54959, pipeline_tag=text-generation

---

## 3. [mistralai/Mistral-Large-4-1T-A52B](https://huggingface.co/mistralai/Mistral-Large-4-1T-A52B)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Mistral AI에서 공개한 Mistral-Large-4-1T-A52B 모델이 Hugging Face에서 주목받고 있습니다. 이 모델은 이미지와 텍스트를 동시에 처리하는 image-text-to-text 파이프라인을 지원합니다.

### 핵심 포인트
- Mistral-Large-4-1T-A52B 모델의 Hugging Face 트렌딩 기록
- 8,200회의 downloads와 1,584개의 likes를 기록하며 높은 관심을 받음
- image-text-to-text 기능을 지원하는 멀티모달 모델

**태그**: Mistral-Large-4-1T-A52B, image-text-to-text, Hugging Face

**Metrics**: {"likes": 1584, "downloads": 8200, "num_parameters": 0, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=1584, downloads=8200, pipeline_tag=image-text-to-text

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

