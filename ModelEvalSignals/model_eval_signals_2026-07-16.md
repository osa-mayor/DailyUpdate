# Model & Eval Signals (2026-07-16)

## 오늘의 요약
Hugging Face의 신규 모델 트렌드와 SWE-bench 및 LiveCodeBench를 중심으로 한 에이전트/코딩 성능 평가 결과가 주요 흐름을 형성했습니다.

### 오늘의 핵심 포인트
- Hugging Face에서 오디오 처리(MOSS-Transcribe-Diarize) 및 텍스트 생성(Agents-A1, Bonsai-27B) 분야의 신규 모델들이 높은 관심을 받고 있습니다.
- SWE-bench 관련 업데이트로 목표 지향적 개발자 평가를 위한 CodeClash 도입, mini-SWE-agent의 성과, 에이전트 학습용 SWE-smith 출시가 확인되었습니다.
- LiveCodeBench 벤치마크에서 O4-Mini 및 Gemini 시리즈 모델들이 상위권 성적을 기록하며 코딩 능력을 입증했습니다.

**오늘의 태그**: LLM, AI Agents, Benchmark, Software Engineering, Hugging Face

## 1. [OpenMOSS-Team/MOSS-Transcribe-Diarize](https://huggingface.co/OpenMOSS-Team/MOSS-Transcribe-Diarize)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
OpenMOSS-Team에서 공개한 MOSS-Transcribe-Diarize 모델이 높은 다운로드 수를 기록하며 주목받고 있습니다. 이 모델은 audio-text-to-text 파이프라인을 지원하는 오디오 관련 모델입니다.

### 핵심 포인트
- MOSS-Transcribe-Diarize 모델의 높은 사용자 유입(downloads 65,109회) 확인
- audio-text-to-text 파이프라인을 활용한 모델
- 약 9억 개의 파라미터를 보유한 모델

**태그**: MOSS-Transcribe-Diarize, audio-text-to-text, OpenMOSS-Team

**Metrics**: {"likes": 211, "downloads": 65109, "num_parameters": 908513280, "pipeline_tag": "audio-text-to-text"}

### 원문 설명
likes=211, downloads=65109, pipeline_tag=audio-text-to-text

---

## 2. [InternScience/Agents-A1](https://huggingface.co/InternScience/Agents-A1)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
InternScience에서 공개한 Agents-A1 모델이 Hugging Face에서 주목받고 있습니다. 약 35B 파라미터 규모의 text-generation 모델로 높은 다운로드 수를 기록 중입니다.

### 핵심 포인트
- InternScience에서 공개한 Agents-A1 모델의 트렌딩 현황
- 약 35.1B 파라미터를 보유한 text-generation 모델
- 30,000회 이상의 높은 다운로드 수를 기록하며 사용자 관심을 받음

**태그**: Agents-A1, text-generation, LLM

**Metrics**: {"likes": 551, "downloads": 30539, "num_parameters": 35107181936, "pipeline_tag": "text-generation"}

### 원문 설명
likes=551, downloads=30539, pipeline_tag=text-generation

---

## 3. [prism-ml/Bonsai-27B-gguf](https://huggingface.co/prism-ml/Bonsai-27B-gguf)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
prism-ml에서 공개한 Bonsai-27B-gguf 모델이 text-generation 태그와 함께 주목받고 있습니다. 해당 모델은 약 3.6B 파라미터를 보유한 GGUF 포맷의 모델입니다.

### 핵심 포인트
- prism-ml의 Bonsai-27B-gguf 모델이 공개됨
- likes 245회, downloads 513회를 기록하며 관심을 받고 있음
- text-generation 파이프라인을 지원하는 약 3.6B 파라미터 규모의 모델임

**태그**: Bonsai-27B-gguf, text-generation, GGUF

**Metrics**: {"likes": 245, "downloads": 513, "num_parameters": 3645856513, "pipeline_tag": "text-generation"}

### 원문 설명
likes=245, downloads=513, pipeline_tag=text-generation

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

