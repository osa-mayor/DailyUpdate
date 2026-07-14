# Model & Eval Signals (2026-07-15)

## 오늘의 요약
Hugging Face의 다양한 멀티모달 및 텍스트 생성 모델들이 주목받는 가운데, SWE-bench와 LiveCodeBench를 중심으로 소프트웨어 엔지니어링 에이전트 및 코딩 능력 평가 체계가 고도화되고 있습니다.

### 오늘의 핵심 포인트
- Hugging Face에서 9B 규모의 멀티모달 모델 및 1B 규모의 텍스트 생성 모델 등 다양한 규모의 모델들이 높은 다운로드 수를 기록하며 트렌드를 형성함
- SWE-bench 팀이 목표 지향적 개발자 역량 측정을 위한 'CodeClash'를 도입하고, 에이전트 학습 환경인 'SWE-smith'를 출시하는 등 소프트웨어 엔지니어링 에이전트 분야의 기술적 진보가 나타남
- LiveCodeBench에서 Gemini 시리즈와 O4-Mini 모델이 상위권을 기록하며 코딩 벤치마크 성능 경쟁이 지속됨

**오늘의 태그**: LLM_Trending, Software_Engineering_Agents, Coding_Benchmarks

## 1. [empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF](https://huggingface.co/empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 image-text-to-text 파이프라인을 지원하는 9B 규모의 모델입니다.

### 핵심 포인트
- 2,000,000회 이상의 높은 downloads를 기록하며 트렌드 형성
- image-text-to-text 파이프라인을 지원하는 멀티모달 성격의 모델
- 약 8.9B 파라미터를 보유한 GGUF 포맷 모델

**태그**: Qwythos-9B-Claude-Mythos-5-1M-GGUF, image-text-to-text, GGUF

**Metrics**: {"likes": 2142, "downloads": 2006265, "num_parameters": 8953803264, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=2142, downloads=2006265, pipeline_tag=image-text-to-text

---

## 2. [OpenMOSS-Team/MOSS-Transcribe-Diarize](https://huggingface.co/OpenMOSS-Team/MOSS-Transcribe-Diarize)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
OpenMOSS-Team에서 공개한 MOSS-Transcribe-Diarize 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 audio-text-to-text 파이프라인을 지원하는 오디오 관련 모델입니다.

### 핵심 포인트
- MOSS-Transcribe-Diarize 모델의 높은 사용자 관심도(downloads 65,109회) 확인
- audio-text-to-text 파이프라인을 활용한 오디오 작업 수행
- 약 9억 개의 파라미터를 가진 모델 규모

**태그**: MOSS-Transcribe-Diarize, audio-text-to-text, HuggingFace

**Metrics**: {"likes": 184, "downloads": 65109, "num_parameters": 908513280, "pipeline_tag": "audio-text-to-text"}

### 원문 설명
likes=184, downloads=65109, pipeline_tag=audio-text-to-text

---

## 3. [GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-Thinking-GGUF](https://huggingface.co/GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-Thinking-GGUF)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
MiniCPM5-1B-Claude-Opus-Fable5-Thinking-GGUF 모델이 Hugging Face에서 높은 다운로드 수를 기록하며 주목받고 있습니다. 약 1B 파라미터를 가진 이 모델은 text-generation 파이프라인을 지원합니다.

### 핵심 포인트
- MiniCPM5-1B-Claude-Opus-Fable5-Thinking-GGUF 모델의 높은 관심도 확인
- 89,892회의 downloads와 229개의 likes 기록
- 약 1.08B 파라미터를 보유한 text-generation 모델

**태그**: MiniCPM5-1B, GGUF, text-generation

**Metrics**: {"likes": 229, "downloads": 89892, "num_parameters": 1080632832, "pipeline_tag": "text-generation"}

### 원문 설명
likes=229, downloads=89892, pipeline_tag=text-generation

---

## 4. [Introducing CodeClash, our new eval of LMs as goal (not task) oriented developers! [ Link ]](https://codeclash.ai)
**Source**: SWE-bench | **Signal Type**: benchmark_update | **Category**: Benchmark News

### 요약
SWE-bench 팀이 언어 모델을 단순 작업 수행자가 아닌 목표 지향적 개발자로 평가하기 위한 새로운 벤치마크인 CodeClash를 소개합니다. 이 평가는 모델이 주어진 과제를 넘어 최종 목표를 달성하는 능력을 측정하는 데 중점을 둡니다.

### 핵심 포인트
- 새로운 벤치마크인 CodeClash 도입
- 단순 task 수행이 아닌 goal-oriented 개발자로서의 능력을 평가
- LLM의 소프트웨어 엔지니어링 역량 측정 방식의 변화 시도

**태그**: SWE-bench, CodeClash, LLM_Evaluation

### 원문 설명
Introducing CodeClash, our new eval of LMs as goal (not task) oriented developers! [ Link ]

---

## 5. [mini-SWE-agent scores 65% on SWE-bench Verified in 100 lines of python code. [ Link ]](https://github.com/SWE-agent/mini-swe-agent)
**Source**: SWE-bench | **Signal Type**: benchmark_update | **Category**: Benchmark News

### 요약
mini-SWE-agent가 SWE-bench Verified 벤치마크에서 65%의 점수를 기록했습니다. 이 성과는 단 100라인의 Python 코드로 달성되었습니다.

### 핵심 포인트
- mini-SWE-agent가 SWE-bench Verified에서 65% 점수 달성
- 단 100라인의 Python 코드로 구현된 효율성
- SWE-bench Verified 벤치마크 성능 입증

**태그**: mini-SWE-agent, SWE-bench, Software Engineering Agent

### 원문 설명
mini-SWE-agent scores 65% on SWE-bench Verified in 100 lines of python code. [ Link ]

---

## 6. [SWE-smith is out! Train your own models for software engineering agents. [ Link ]](https://swesmith.com)
**Source**: SWE-bench | **Signal Type**: benchmark_update | **Category**: Benchmark News

### 요약
소프트웨어 엔지니어링 에이전트 학습을 위한 SWE-smith가 출시되었습니다. 사용자가 직접 모델을 학습시킬 수 있는 환경을 제공합니다.

### 핵심 포인트
- SWE-smith 프레임워크 출시
- 소프트웨어 엔지니어링 에이전트 특화 모델 학습 지원
- 사용자 맞춤형 모델 학습 가능

**태그**: SWE-smith, Software Engineering, AI Agents

### 원문 설명
SWE-smith is out! Train your own models for software engineering agents. [ Link ]

---

## 7. [LiveCodeBench top model: O4-Mini (High)](https://livecodebench.github.io/leaderboard.html)
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

## 8. [LiveCodeBench top model: Gemini-2.5-Pro-06-05](https://livecodebench.github.io/leaderboard.html)
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

## 9. [LiveCodeBench top model: Gemini-2.5-Flash-04-17](https://livecodebench.github.io/leaderboard.html)
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

