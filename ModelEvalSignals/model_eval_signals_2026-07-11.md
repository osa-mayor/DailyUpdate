# Model & Eval Signals (2026-07-11)

## 오늘의 요약
Hugging Face의 신규 멀티모달 및 텍스트 생성 모델들이 트렌드로 부상하는 가운데, SWE-bench와 LiveCodeBench를 중심으로 소프트웨어 엔지니어링 에이전트 및 코딩 능력 평가에 관한 기술적 진보가 두드러졌습니다.

### 오늘의 핵심 포인트
- Hugging Face에서 27B~35B 규모의 신규 모델(ThinkingCap, Agents-A1, LongCat-2.0)들이 높은 관심을 받으며 트렌드에 진입함
- SWE-bench 팀이 목표 지향적 개발자 역량 측정을 위한 'CodeClash'를 도입하고, 에이전트 학습 도구인 'SWE-smith'를 출시함
- LiveCodeBench에서 O4-Mini 및 Gemini 시리즈 모델들이 상위권 성적을 기록하며 코딩 벤치마크 경쟁이 심화됨

**오늘의 태그**: LLM_Trending, Software_Engineering_Agents, Coding_Benchmarks

## 1. [bottlecapai/ThinkingCap-Qwen3.6-27B](https://huggingface.co/bottlecapai/ThinkingCap-Qwen3.6-27B)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Hugging Face에서 주목받고 있는 bottlecapai/ThinkingCap-Qwen3.6-27B 모델은 이미지와 텍스트를 동시에 처리하는 멀티모달 모델입니다. 약 27B 파라미터를 보유하고 있으며, 최근 높은 다운로드 수를 기록하며 트렌드에 진입했습니다.

### 핵심 포인트
- 모델명은 bottlecapai/ThinkingCap-Qwen3.6-27B이며, 약 27.3B 파라미터를 가진 모델입니다.
- pipeline_tag는 image-text-to-text로, 시각 정보와 텍스트를 결합하는 작업에 특화되어 있습니다.
- 최근 3,699회의 다운로드와 207개의 likes를 기록하며 모델 트렌드에 진입했습니다.

**태그**: ThinkingCap-Qwen3.6-27B, image-text-to-text, LLM

**Metrics**: {"likes": 207, "downloads": 3699, "num_parameters": 27356728560, "pipeline_tag": "image-text-to-text"}

### 원문 설명
likes=207, downloads=3699, pipeline_tag=image-text-to-text

---

## 2. [InternScience/Agents-A1](https://huggingface.co/InternScience/Agents-A1)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
InternScience에서 공개한 Agents-A1 모델이 Hugging Face에서 주목받고 있습니다. 약 35B 파라미터 규모의 text-generation 모델로, 높은 다운로드 수를 기록하며 트렌드에 진입했습니다.

### 핵심 포인트
- InternScience에서 공개한 Agents-A1 모델의 트렌드 발생
- 약 35.1B 규모의 파라미터를 가진 text-generation 모델
- 25,772회의 다운로드와 461개의 likes를 기록하며 높은 관심을 받음

**태그**: Agents-A1, text-generation, HuggingFace

**Metrics**: {"likes": 461, "downloads": 25772, "num_parameters": 35107181936, "pipeline_tag": "text-generation"}

### 원문 설명
likes=461, downloads=25772, pipeline_tag=text-generation

---

## 3. [meituan-longcat/LongCat-2.0](https://huggingface.co/meituan-longcat/LongCat-2.0)
**Source**: HF Model Trending | **Signal Type**: model_trending | **Category**: Model Trending

### 요약
Meituan에서 공개한 LongCat-2.0 모델이 Hugging Face에서 주목받고 있습니다. 해당 모델은 text-generation 태그를 사용하는 대규모 파라미터 규모의 모델입니다.

### 핵심 포인트
- Meituan에서 공개한 LongCat-2.0 모델의 트렌딩 현황
- 1,308회의 다운로드와 169개의 likes를 기록하며 관심을 모음
- 약 1.77T 파라미터 규모를 가진 text-generation 모델

**태그**: LongCat-2.0, text-generation, Meituan

**Metrics**: {"likes": 169, "downloads": 1308, "num_parameters": 1775560491136, "pipeline_tag": "text-generation"}

### 원문 설명
likes=169, downloads=1308, pipeline_tag=text-generation

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

