# Model & Eval Signals (2026-06-09)

## 오늘의 요약
Hugging Face를 통한 멀티모달(음성, TTS, 이미지-텍스트) 특화 모델들의 활발한 공개와 함께, 소프트웨어 엔지니어링 에이전트의 역량을 측정하기 위한 새로운 벤치마크 및 성능 지표들이 주목받고 있습니다.

### 오늘의 핵심 포인트
- GGUF 포맷, ASR, TTS 등 특정 목적에 최적화된 다양한 규모의 모델들이 Hugging Face에서 트렌드로 부상
- 단순 작업 수행을 넘어 목표 지향적 개발 역량을 평가하는 CodeClash 등 소프트웨어 엔지니어링 에이전트용 벤치마크 진화
- LiveCodeBench를 통해 확인된 Gemini 및 O4-Mini 등 최신 모델들의 코딩 성능 경쟁

**오늘의 태그**: LLM, Software Engineering Agents, Benchmark, Multimodal, Coding

## 1. [unsloth/gemma-4-12b-it-GGUF](https://huggingface.co/unsloth/gemma-4-12b-it-GGUF)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
unsloth에서 공개한 gemma-4-12b-it-GGUF 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 image-text-to-text 파이프라인을 지원하는 GGUF 포맷의 모델입니다.

### 핵심 포인트
- unsloth/gemma-4-12b-it-GGUF 모델의 높은 인기로 인해 645,263회의 다운로드를 기록함
- image-text-to-text 파이프라인을 지원하는 멀티모달 성격의 모델임
- 약 11.9B 파라미터를 보유한 GGUF 포맷 모델임

**태그**: unsloth, gemma-4-12b-it-GGUF, image-text-to-text

**Metrics**: {"likes": 491, "downloads": 645263, "num_parameters": 11907350576, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=491, downloads=645263, pipeline_tag=image-text-to-text

---

## 2. [nvidia/nemotron-3.5-asr-streaming-0.6b](https://huggingface.co/nvidia/nemotron-3.5-asr-streaming-0.6b)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
NVIDIA에서 공개한 nemotron-3.5-asr-streaming-0.6b 모델이 Hugging Face에서 주목받고 있습니다. 이 모델은 automatic-speech-recognition 태그를 가진 음성 인식 특화 모델입니다.

### 핵심 포인트
- NVIDIA의 nemotron-3.5-asr-streaming-0.6b 모델이 Hugging Face에서 트렌딩 중입니다.
- 해당 모델은 automatic-speech-recognition(ASR) 파이프라인을 지원합니다.
- 현재 3,957회의 다운로드와 283개의 likes를 기록하고 있습니다.

**태그**: NVIDIA, ASR, Nemotron

**Metrics**: {"likes": 283, "downloads": 3957, "num_parameters": 0, "pipeline_tag": "automatic-speech-recognition"}

### 원문 설명
likes=283, downloads=3957, pipeline_tag=automatic-speech-recognition

---

## 3. [bosonai/higgs-audio-v3-tts-4b](https://huggingface.co/bosonai/higgs-audio-v3-tts-4b)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
BosonAI에서 공개한 higgs-audio-v3-tts-4b 모델이 Hugging Face에서 주목받고 있습니다. 이 모델은 텍스트 음성 변환(text-to-speech)을 위한 4B 규모의 파라미터를 가진 모델입니다.

### 핵심 포인트
- bosonai/higgs-audio-v3-tts-4b 모델의 Hugging Face 트렌딩 기록
- 약 4.65B 규모의 파라미터를 보유한 text-to-speech 모델
- 15,000회 이상의 다운로드와 237개의 likes를 기록하며 높은 관심을 받음

**태그**: bosonai, text-to-speech, TTS

**Metrics**: {"likes": 237, "downloads": 15005, "num_parameters": 4654850537, "pipeline_tag": "text-to-speech"}

### 원문 설명
likes=237, downloads=15005, pipeline_tag=text-to-speech

---

## 4. [Introducing CodeClash, our new eval of LMs as goal (not task) oriented developers! [ Link ]](https://codeclash.ai)
**Source**: SWE-bench | **Signal Type**: benchmark_update | **Category**: Benchmark News

### 요약
SWE-bench 팀에서 단순 작업 수행이 아닌 목표 지향적 개발자 역량을 평가하기 위한 새로운 벤치마크인 CodeClash를 공개했습니다. 이 평가는 언어 모델이 복잡한 개발 목표를 이해하고 해결할 수 있는지 측정하는 데 중점을 둡니다.

### 핵심 포인트
- 새로운 평가 프레임워크인 CodeClash 도입
- 단순 task 수행이 아닌 goal-oriented 개발자로서의 역량 평가
- LLM의 복잡한 소프트웨어 개발 문제 해결 능력 측정

**태그**: SWE-bench, CodeClash, LLM Evaluation

### 원문 설명
Introducing CodeClash, our new eval of LMs as goal (not task) oriented developers! [ Link ]

---

## 5. [mini-SWE-agent scores 65% on SWE-bench Verified in 100 lines of python code. [ Link ]](https://github.com/SWE-agent/mini-swe-agent)
**Source**: SWE-bench | **Signal Type**: benchmark_update | **Category**: Benchmark News

### 요약
mini-SWE-agent가 SWE-bench Verified 벤치마크에서 65%의 점수를 기록했습니다. 이 모델은 단 100라인의 Python 코드로 구현되었습니다.

### 핵심 포인트
- mini-SWE-agent의 SWE-bench Verified 점수 65% 달성
- 단 100라인의 Python 코드로 구현된 효율성
- SWE-bench Verified 벤치마크 결과 보고

**태그**: mini-SWE-agent, SWE-bench, Python

### 원문 설명
mini-SWE-agent scores 65% on SWE-bench Verified in 100 lines of python code. [ Link ]

---

## 6. [SWE-smith is out! Train your own models for software engineering agents. [ Link ]](https://swesmith.com)
**Source**: SWE-bench | **Signal Type**: benchmark_update | **Category**: Benchmark News

### 요약
소프트웨어 엔지니어링 에이전트 학습을 위한 SWE-smith가 출시되었습니다. 사용자가 직접 에이전트용 모델을 학습시킬 수 있는 환경을 제공합니다.

### 핵심 포인트
- SWE-smith 프로젝트 출시
- 소프트웨어 엔지니어링 에이전트 전용 모델 학습 지원
- 사용자 맞춤형 모델 학습 가능

**태그**: SWE-smith, Software Engineering, AI Agents

### 원문 설명
SWE-smith is out! Train your own models for software engineering agents. [ Link ]

---

## 7. [LiveCodeBench top model: O4-Mini (High)](https://livecodebench.github.io/leaderboard.html)
**Source**: LiveCodeBench | **Signal Type**: benchmark_snapshot | **Category**: Benchmark Leaderboard

### 요약
LiveCodeBench에서 O4-Mini (High) 모델이 상위 성적을 기록했습니다. 해당 모델은 4개의 문제를 대상으로 테스트를 진행했습니다.

### 핵심 포인트
- LiveCodeBench에서 O4-Mini (High) 모델이 우수한 성능을 보임
- 테스트에 사용된 문제 수는 총 4개임
- avg_pass@1 지표는 25.0을 기록함

**태그**: LiveCodeBench, O4-Mini (High), avg_pass@1

**Metrics**: {"avg_pass_at_1": 25.0, "problem_count": 4, "model": "O4-Mini (High)"}

### 원문 설명
avg_pass@1=25.0, problems=4

---

## 8. [LiveCodeBench top model: Gemini-2.5-Pro-06-05](https://livecodebench.github.io/leaderboard.html)
**Source**: LiveCodeBench | **Signal Type**: benchmark_snapshot | **Category**: Benchmark Leaderboard

### 요약
LiveCodeBench 벤치마크에서 Gemini-2.5-Pro-06-05 모델이 상위 성적을 기록했습니다. 해당 모델은 4개의 문제를 대상으로 avg_pass@1 25.0%의 성능을 보여주었습니다.

### 핵심 포인트
- Gemini-2.5-Pro-06-05 모델이 LiveCodeBench에서 top model로 기록됨
- 테스트에 사용된 문제 수는 총 4개임
- avg_pass@1 지표 기준 25.0%의 성능을 달성함

**태그**: LiveCodeBench, Gemini-2.5-Pro-06-05, avg_pass@1

**Metrics**: {"avg_pass_at_1": 25.0, "problem_count": 4, "model": "Gemini-2.5-Pro-06-05"}

### 원문 설명
avg_pass@1=25.0, problems=4

---

## 9. [LiveCodeBench top model: Gemini-2.5-Flash-04-17](https://livecodebench.github.io/leaderboard.html)
**Source**: LiveCodeBench | **Signal Type**: benchmark_snapshot | **Category**: Benchmark Leaderboard

### 요약
LiveCodeBench의 최신 스냅샷 결과, Gemini-2.5-Flash-04-17 모델이 상위 성능을 기록했습니다. 해당 모델은 4개의 문제를 대상으로 테스트를 진행했습니다.

### 핵심 포인트
- Gemini-2.5-Flash-04-17 모델이 LiveCodeBench에서 상위권을 기록함
- 테스트 결과 avg_pass@1 지표는 25.0을 달성함
- 총 4개의 문제를 대상으로 벤치마크가 수행됨

**태그**: LiveCodeBench, Gemini-2.5-Flash-04-17, benchmark_snapshot

**Metrics**: {"avg_pass_at_1": 25.0, "problem_count": 4, "model": "Gemini-2.5-Flash-04-17"}

### 원문 설명
avg_pass@1=25.0, problems=4

---

