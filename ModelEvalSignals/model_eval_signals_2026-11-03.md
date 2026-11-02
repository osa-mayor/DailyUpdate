# Model & Eval Signals (2026-11-03)

## 오늘의 요약
Hugging Face에서는 멀티모달(Image-to-Text) 및 특정 목적(OCR, Coding) 특화 모델들이 주목받고 있으며, LiveCodeBench에서는 Gemini 및 O4-Mini 모델들이 상위권 성적을 기록하며 코딩 성능 경쟁을 보여주었습니다.

### 오늘의 핵심 포인트
- Mistral AI 및 Baidu의 멀티모달/OCR 특화 모델이 Hugging Face에서 높은 관심을 받음
- Qwen3.5 기반의 4.5B 규모 코딩 특화 모델(3D-Coder)의 활발한 활용
- LiveCodeBench 벤치마크에서 Gemini 시리즈와 O4-Mini 모델의 상위권 성적 기록

**오늘의 태그**: HuggingFace, LiveCodeBench, Multimodal, Coding-Model, OCR

## 1. [mistralai/Mistral-Large-4-1T-A52B](https://huggingface.co/mistralai/Mistral-Large-4-1T-A52B)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Mistral AI에서 공개한 Mistral-Large-4-1T-A52B 모델이 Hugging Face에서 주목받고 있습니다. 이 모델은 이미지와 텍스트를 동시에 처리하는 image-text-to-text 파이프라인을 지원합니다.

### 핵심 포인트
- Mistral-Large-4-1T-A52B 모델의 Hugging Face 트렌딩 기록
- likes 1,494회 및 downloads 5,500회를 기록하며 높은 관심을 받음
- image-text-to-text 파이프라인을 지원하는 멀티모달 모델

**태그**: Mistral-Large-4-1T-A52B, image-text-to-text, Hugging Face

**Metrics**: {"likes": 1494, "downloads": 5500, "num_parameters": 0, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=1494, downloads=5500, pipeline_tag=image-text-to-text

---

## 2. [baidu/Unlimited-OCR-2](https://huggingface.co/baidu/Unlimited-OCR-2)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Baidu에서 공개한 Unlimited-OCR-2 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 image-text-to-text 파이프라인을 지원하는 OCR 관련 모델입니다.

### 핵심 포인트
- Baidu에서 출시한 Unlimited-OCR-2 모델의 높은 트렌드 기록
- 약 3.34B 파라미터를 보유한 image-text-to-text 모델
- 14만 건 이상의 높은 다운로드 수를 기록하며 기술적 관심을 받음

**태그**: Baidu, Unlimited-OCR-2, OCR

**Metrics**: {"likes": 555, "downloads": 147588, "num_parameters": 3343978497, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=555, downloads=147588, pipeline_tag=image-text-to-text

---

## 3. [ccore/Qwen3.5-4B-3D-Coder](https://huggingface.co/ccore/Qwen3.5-4B-3D-Coder)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
ccore/Qwen3.5-4B-3D-Coder 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 약 4.5B 파라미터를 가진 이 모델은 최근 사용자들 사이에서 활발하게 활용되고 있습니다.

### 핵심 포인트
- ccore/Qwen3.5-4B-3D-Coder 모델의 높은 관심도 반영
- 63,499회의 downloads와 554개의 likes 기록
- 약 4.5B 규모의 파라미터를 보유한 모델

**태그**: Qwen3.5-4B-3D-Coder, Model Trending, Hugging Face

**Metrics**: {"likes": 554, "downloads": 63499, "num_parameters": 4539265536, "pipeline_tag": ""}

### 원문 설명
likes=554, downloads=63499, pipeline_tag=

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

