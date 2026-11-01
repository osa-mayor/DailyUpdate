# Model & Eval Signals (2026-11-02)

## 오늘의 요약
Hugging Face의 신규 모델 공개와 LiveCodeBench 벤치마크 결과가 주요 흐름을 형성하였으며, 코딩, 영상 생성, 음성 인식 등 다양한 도메인의 특화 모델들이 주목받고 있습니다.

### 오늘의 핵심 포인트
- Hugging Face에서 Qwen3.5 기반 코딩 모델, Pika-Labs의 비디오 생성 모델, NVIDIA의 ASR 특화 모델이 높은 관심을 받음
- LiveCodeBench 벤치마크에서 O4-Mini 및 Gemini 시리즈 모델들이 상위권 성적을 기록
- 특정 도메인(Coding, Video, ASR)에 최적화된 파라미터 규모의 모델들이 활발히 활용되는 추세

**오늘의 태그**: HuggingFace, LiveCodeBench, AI_Model_Trends

## 1. [ccore/Qwen3.5-4B-3D-Coder](https://huggingface.co/ccore/Qwen3.5-4B-3D-Coder)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
ccore/Qwen3.5-4B-3D-Coder 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 약 4.5B 파라미터를 가진 이 모델은 최근 사용자들 사이에서 활발히 활용되고 있습니다.

### 핵심 포인트
- ccore/Qwen3.5-4B-3D-Coder 모델의 높은 다운로드 수(44,825회) 기록
- 약 4.5B 규모의 파라미터를 보유한 모델
- 최근 Hugging Face에서 높은 관심을 받는 모델 트렌드 반영

**태그**: Qwen3.5-4B-3D-Coder, Model Trending, Hugging Face

**Metrics**: {"likes": 465, "downloads": 44825, "num_parameters": 4539265536, "pipeline_tag": ""}

### 원문 설명
likes=465, downloads=44825, pipeline_tag=

---

## 2. [Pika-Labs/Pika-H3-Flex](https://huggingface.co/Pika-Labs/Pika-H3-Flex)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Pika-Labs에서 공개한 Pika-H3-Flex 모델이 Hugging Face에서 주목받고 있습니다. 이 모델은 image-to-video 파이프라인을 지원하는 것이 특징입니다.

### 핵심 포인트
- Pika-Labs에서 출시한 Pika-H3-Flex 모델
- image-to-video 태그를 사용하는 비디오 생성 모델
- 약 33B 규모의 파라미터를 보유함

**태그**: Pika-H3-Flex, image-to-video, Pika-Labs

**Metrics**: {"likes": 302, "downloads": 404, "num_parameters": 33122992896, "pipeline_tag": "image-to-video"}

### 원문 설명
likes=302, downloads=404, pipeline_tag=image-to-video

---

## 3. [nvidia/NVIDIA-Nemotron-3.5-Transcribe-30B-A4B](https://huggingface.co/nvidia/NVIDIA-Nemotron-3.5-Transcribe-30B-A4B)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
NVIDIA에서 공개한 NVIDIA-Nemotron-3.5-Transcribe-30B-A4B 모델이 Hugging Face에서 주목받고 있습니다. 이 모델은 automatic-speech-recognition 태그를 가진 음성 인식 특화 모델입니다.

### 핵심 포인트
- NVIDIA에서 출시한 30B 규모의 automatic-speech-recognition 모델입니다.
- 약 29,364회의 downloads를 기록하며 높은 관심을 받고 있습니다.
- 모델 파라미터 수는 약 33.7B입니다.

**태그**: NVIDIA, automatic-speech-recognition, ASR

**Metrics**: {"likes": 582, "downloads": 29364, "num_parameters": 33697781029, "pipeline_tag": "automatic-speech-recognition"}

### 원문 설명
likes=582, downloads=29364, pipeline_tag=automatic-speech-recognition

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

