# Model & Eval Signals (2026-11-04)

## 오늘의 요약
Hugging Face에서는 소형 모델부터 멀티모달/OCR 특화 모델까지 다양한 목적의 모델들이 주목받았으며, LiveCodeBench에서는 Gemini 및 O4-Mini 등 코딩 성능이 우수한 모델들이 상위권을 기록했습니다.

### 오늘의 핵심 포인트
- LiquidAI의 LFM3-1.7B 등 소형 모델 및 Baidu의 OCR 특화 모델 등 특정 목적형 모델의 높은 사용자 유입
- Mistral-Large-4-1T-A52B와 같은 이미지-텍스트 통합 처리 모델의 주목
- LiveCodeBench 벤치마크를 통한 Gemini 및 O4-Mini 모델의 코딩 성능 검증

**오늘의 태그**: HuggingFace, LiveCodeBench, LLM_Trending

## 1. [LiquidAI/LFM3-1.7B](https://huggingface.co/LiquidAI/LFM3-1.7B)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
LiquidAI에서 공개한 1.7B 규모의 text-generation 모델인 LFM3-1.7B가 높은 다운로드 수를 기록하며 주목받고 있습니다. 약 1.7B 파라미터를 가진 소형 모델임에도 불구하고 활발한 사용자 유입을 보여주고 있습니다.

### 핵심 포인트
- LiquidAI에서 출시한 1.7B 규모의 text-generation 모델
- 47,817회의 다운로드와 1,385개의 likes를 기록하며 높은 관심을 받음
- 약 1.7B(1,728,801,536) 파라미터를 보유한 소형 모델

**태그**: LiquidAI, LFM3-1.7B, text-generation

**Metrics**: {"likes": 1385, "downloads": 47817, "num_parameters": 1728801536, "pipeline_tag": "text-generation"}

### 원문 설명
likes=1385, downloads=47817, pipeline_tag=text-generation

---

## 2. [mistralai/Mistral-Large-4-1T-A52B](https://huggingface.co/mistralai/Mistral-Large-4-1T-A52B)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Mistral AI에서 공개한 Mistral-Large-4-1T-A52B 모델이 Hugging Face에서 주목받고 있습니다. 이 모델은 이미지와 텍스트를 동시에 처리하는 image-text-to-text 파이프라인을 지원합니다.

### 핵심 포인트
- Mistral-Large-4-1T-A52B 모델의 Hugging Face 트렌딩 기록
- likes 1,533회 및 downloads 6,556회를 기록하며 높은 관심을 받음
- image-text-to-text 기능을 지원하는 멀티모달 모델

**태그**: Mistral-Large-4-1T-A52B, image-text-to-text, Hugging Face

**Metrics**: {"likes": 1533, "downloads": 6556, "num_parameters": 0, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=1533, downloads=6556, pipeline_tag=image-text-to-text

---

## 3. [baidu/Unlimited-OCR-2](https://huggingface.co/baidu/Unlimited-OCR-2)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Baidu에서 공개한 Unlimited-OCR-2 모델이 Hugging Face에서 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 image-text-to-text 파이프라인을 지원하는 OCR 특화 모델입니다.

### 핵심 포인트
- Baidu에서 출시한 image-text-to-text 파이프라인 모델인 Unlimited-OCR-2가 공개되었습니다.
- 약 189,897회의 높은 다운로드 수를 기록하며 기술적 관심을 받고 있습니다.
- 모델 파라미터 규모는 약 3.34B입니다.

**태그**: Baidu, Unlimited-OCR-2, OCR

**Metrics**: {"likes": 584, "downloads": 189897, "num_parameters": 3343978497, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=584, downloads=189897, pipeline_tag=image-text-to-text

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

