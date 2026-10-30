# Model & Eval Signals (2026-10-31)

## 오늘의 요약
NVIDIA, Mistral AI, Baidu 등 주요 기업의 신규 모델 공개와 LiveCodeBench를 통한 코딩 성능 벤치마크 결과가 주요 흐름을 형성했습니다.

### 오늘의 핵심 포인트
- NVIDIA의 ASR 특화 모델 및 Mistral/Baidu의 멀티모달(OCR/Image-to-Text) 모델 공개
- LiveCodeBench 벤치마크에서 O4-Mini 및 Gemini 시리즈 모델들의 상위권 성적 기록
- 음성 인식, OCR, 코딩 등 특정 작업에 최적화된 전문 모델들의 트렌드 지속

**오늘의 태그**: HuggingFace, LiveCodeBench, ASR, OCR, Multimodal

## 1. [nvidia/NVIDIA-Nemotron-3.5-Transcribe-30B-A4B](https://huggingface.co/nvidia/NVIDIA-Nemotron-3.5-Transcribe-30B-A4B)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
NVIDIA에서 공개한 NVIDIA-Nemotron-3.5-Transcribe-30B-A4B 모델이 Hugging Face에서 주목받고 있습니다. 이 모델은 자동 음성 인식(ASR) 작업을 위해 설계된 30B 규모의 모델입니다.

### 핵심 포인트
- NVIDIA에서 출시한 30B 규모의 automatic-speech-recognition 모델입니다.
- Hugging Face에서 15,980회의 다운로드와 483개의 likes를 기록하며 트렌딩 중입니다.
- 약 33.7B 파라미터를 보유한 음성 인식 특화 모델입니다.

**태그**: NVIDIA-Nemotron-3.5-Transcribe-30B-A4B, automatic-speech-recognition, ASR

**Metrics**: {"likes": 483, "downloads": 15980, "num_parameters": 33697781029, "pipeline_tag": "automatic-speech-recognition"}

### 원문 설명
likes=483, downloads=15980, pipeline_tag=automatic-speech-recognition

---

## 2. [mistralai/Mistral-Large-4-1T-A52B](https://huggingface.co/mistralai/Mistral-Large-4-1T-A52B)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Mistral AI에서 공개한 Mistral-Large-4-1T-A52B 모델이 Hugging Face에서 주목받고 있습니다. 이 모델은 이미지와 텍스트를 동시에 처리하는 image-text-to-text 파이프라인을 지원합니다.

### 핵심 포인트
- Mistral-Large-4-1T-A52B 모델의 Hugging Face 공개
- 1,325개의 likes와 1,239회의 downloads를 기록하며 트렌드 형성
- image-text-to-text 기능을 지원하는 멀티모달 모델

**태그**: Mistral-Large-4-1T-A52B, image-text-to-text, Hugging Face

**Metrics**: {"likes": 1325, "downloads": 1239, "num_parameters": 0, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=1325, downloads=1239, pipeline_tag=image-text-to-text

---

## 3. [baidu/Unlimited-OCR-2](https://huggingface.co/baidu/Unlimited-OCR-2)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Baidu에서 공개한 Unlimited-OCR-2 모델이 Hugging Face에서 주목받고 있습니다. 이 모델은 image-text-to-text 파이프라인을 지원하는 OCR 관련 모델입니다.

### 핵심 포인트
- Baidu에서 개발한 Unlimited-OCR-2 모델이 Hugging Face에서 트렌딩 중입니다.
- 약 3.34B 파라미터를 가진 image-text-to-text 태그의 모델입니다.
- 높은 다운로드 수(24,276회)를 기록하며 관련 분야에서 활용도가 높습니다.

**태그**: Baidu, Unlimited-OCR-2, OCR

**Metrics**: {"likes": 442, "downloads": 24276, "num_parameters": 3343978497, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=442, downloads=24276, pipeline_tag=image-text-to-text

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

